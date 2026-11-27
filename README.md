# hardwood-benchmark-results

Regression results of [Hardwood](https://github.com/hardwood-hq/hardwood), as
[hardwood-benchmarks](https://github.com/hardwood-hq/hardwood-benchmarks)' `run-regression.sh`
measures them, one series per benchmark contender, for [Apache Otava](https://otava.apache.org/)
to find change points in.

hardwood-benchmarks' nightly job (`nightly.sh`) writes everything here: once a night, and after
each batch of backfills of older versions. Its `charts/record-results.py` writes the series and
`charts/nightly.py` the rest.
Nothing is edited by hand. The [history page](https://hardwood.dev/hardwood-benchmark-results/)
charts every series.

## Layout

| Path | Holds |
| --- | --- |
| `series/<machine epoch>/<Benchmark>/<contender>@<epoch>.csv` | one row per recorded run of the contender: the measured Hardwood commit's time, the commit, the version, when the run began, the schema version, and the metrics below |
| `series/…/<contender>@<epoch>.unsettled.csv` | the rows of runs in which the contender did not settle or its forks disagreed; Otava does not read them |
| `epochs/<Benchmark>/<contender>/<epoch>.json` | what a contender's epoch measures: its script, preset, the iteration counts every preset shares, its benchmark method's source and a digest of each piece of benchmark code the method reaches, its parameters and the files it reads, each by name and size |
| `machines/<machine epoch>.json` | the machine and JVM of a machine epoch: CPU, cores, microcode, JDK build, heap and collector flags, governor, clock and turbo; each run's manifest under `runs/` also records the kernel |
| `runs/<start>-<version>/` | each recorded run as it was: its manifest (with the benchmarks commit it ran), its tables and what it did not run, and per round the results files and `RegressionProfiler`'s per-iteration metrics |
| `otava.yaml` | one Otava test per series file |
| `nights.csv` | each night the job measured as its own: date, commit, version, run |
| `changes.json` | every change point Otava found: series, commit before and after, each metric's change, and its status (regression at a commit a night measured, history at one only a backfill measured, improvement, or unstable for a contender that stopped settling), with the side-by-side run of a new regression and the issue it opened |
| `reports/<date>.md`, `reports/latest.md` | each night's report: the version measured, each metric against the median of the series' last five nights, what did not run, the change points found that night; or why the night recorded nothing |
| `index.html`, `history.json` | the history page and the index of series, machines and change points it reads |

A change to what a contender measures starts a new epoch, and a new machine or JDK a new
machine epoch; either starts a new series, so that no series mixes two definitions or two
machines, and the new series is backfilled with every release. A new kernel does not: a step
it causes shows as a change point at a commit where Hardwood did not change, which the
side-by-side run, on one kernel, does not reproduce.

## Metrics

| Column | What | Otava |
| --- | --- | --- |
| `wall_ms` | the median of the forks' mean time per operation | yes |
| `wall_spread_pct` | half the range of the forks' means, against their median | |
| `wall_forks_ms` | each fork's mean, `;`-separated | |
| `cpu_ms` | the process's CPU time per operation, the median over every fork's measurement iterations | yes |
| `jit_ms`, `gc_ms` | the JIT compiler's and the collector's share of it | |
| `alloc_bytes` | bytes allocated per operation by every thread | yes |
| `caller_ms` | the CPU time per operation of the threads calling the benchmark method, JMH's workers, the median over every fork's measurement iterations | |
| `live_bytes` | the heap-after-collection peak, the most heap in use right after a collection, over every measurement iteration: live data plus objects promoted and not yet reclaimed, so it moves with when collections fall | |

Each is better lower. A column added later is empty in older rows; `schema` gives the row's
layout.

## Analysing

```sh
pip install apache-otava
otava list-tests --config-file otava.yaml
otava analyze --config-file otava.yaml '<test>'
```

`--config-file` follows the command. Run from this repository's root, since `otava.yaml`
names its files relative to it.

## License

The contents of this repository are licensed under [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
