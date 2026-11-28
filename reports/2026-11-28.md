# Nightly 2026-11-28

| | |
|---|---|
| Version | 1.1.0-main7dcb71f-SNAPSHOT |
| Commit | [7dcb71f86](https://github.com/hardwood-hq/hardwood/commit/7dcb71f86f249cdd2eb9e049c07d1d0ccf8f1249) |
| Run | 2026-11-28T07:18:51+0100 |
| Machine | [md02f92f9f202](../machines/md02f92f9f202.json) |
| Duration | 46 min |

Each metric against the median of the series' last 5 nights. The caller share is the CPU time of the thread calling the benchmark against wall time; in bold from 0.8, where that thread hardly waits on Hardwood and wall time misses decode changes that CPU time still shows.

| Benchmark | Contender | Wall | | CPU | | Allocated | | Heap after GC | | Caller share | |
|---|---|--:|--:|--:|--:|--:|--:|--:|--:|--:|---|
| BinaryScan | hardwoodColumnViews | 223 ms | -0.5 % | 1,666 ms | -0.1 % | 369.8 MiB | -0.1 % | 158.8 MiB | -7.8 % | 0.53 |  |
| BinaryScan | hardwoodRowStrings | 999 ms | -0.2 % | 2,530 ms | -1.9 % | 767.9 MiB | +0.0 % | 296.4 MiB | +1.2 % | **0.96** |  |
| BloomFilter | hardwoodBloom[absent] | 0.401 ms | -0.2 % | 0.641 ms | +0.6 % | 40.8 KiB | +1.3 % | 71.6 MiB | -0.1 % | 0.65 |  |
| DictionaryFilter | hardwoodRowIn | 10.1 ms | +0.1 % | 52.4 ms | +0.2 % | 11.7 MiB | +0.8 % | 87.1 MiB | +8.2 % | 0.44 |  |
| DictionaryFilter | hardwoodRowLtWide | 42.5 ms | -3.1 % | 149 ms | -1.7 % | 32.3 MiB | -1.2 % | 103.3 MiB | -3.6 % | 0.30 |  |
| Filter | hardwoodDefault[matchAll] | 17.6 ms | -1.2 % | 90.5 ms | +0.4 % | 40.7 MiB | -0.0 % | 84.0 MiB | -1.9 % | **0.81** |  |
| Filter | hardwoodDefault[selective] | 5.22 ms | -2.2 % | 21.1 ms | +3.5 % | 6.0 MiB | -0.3 % | 76.9 MiB | -0.1 % | 0.40 |  |
| Filter | hardwoodRowReader[matchAll] | 39 ms | +0.7 % | 104 ms | -0.4 % | 29.6 MiB | -0.0 % | 77.0 MiB | -1.9 % | **0.93** |  |
| Filter | hardwoodRowReader[selective] | 6.1 ms | -7.4 % | 20.2 ms | +0.9 % | 5.4 MiB | -0.3 % | 75.2 MiB | -0.2 % | 0.57 |  |
| FixedSizeListScan | columnFast[768] | 12.6 ms | +1.4 % | 51.5 ms | +2.3 % | 31.8 MiB | +0.0 % | 74.6 MiB | -12.9 % | **0.90** |  |
| FixedSizeListScan | rowFast[768] | 19.8 ms | +1.3 % | 56.1 ms | +2.1 % | 31.9 MiB | +0.0 % | 90.6 MiB | -0.5 % | **0.94** |  |
| FlatScan | columnarDrain | 150 ms | +1.5 % | 929 ms | +0.5 % | 542.1 MiB | +0.0 % | 429.5 MiB | +3.3 % | 0.39 |  |
| FlatScan | hardwoodColumnar | 274 ms | -1.0 % | 1,078 ms | -1.8 % | 609.5 MiB | -0.0 % | 384.5 MiB | -4.0 % | **0.86** |  |
| FlatScan | hardwoodRowReaderIndexed | 440 ms | +2.0 % | 1,177 ms | +1.1 % | 295.4 MiB | +0.1 % | 2.0 GiB | +128.7 % | **0.92** |  |
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.5 ms | +0.4 % | 144 ms | +0.9 % | 97.4 MiB | +0.0 % | 187.1 MiB | +1.3 % | 0.55 |  |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.6 ms | -0.1 % | 387 ms | +0.0 % | 99.3 MiB | +0.0 % | 209.7 MiB | +0.1 % | 0.24 |  |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 110 ms | +0.8 % | 667 ms | +1.1 % | 74.5 MiB | +0.1 % | 216.8 MiB | -1.6 % | 0.75 |  |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 ms | -0.3 % | 1,268 ms | -1.4 % | 170.8 MiB | +0.1 % | 252.3 MiB | +0.1 % | 0.79 |  |
| NarrowScan | hardwoodColumnar | 93.9 ms | +0.7 % | 538 ms | -0.2 % | 268.9 MiB | +0.1 % | 196.1 MiB | +16.9 % | 0.68 |  |
| NarrowScan | hardwoodRowReaderIndexed | 169 ms | +0.2 % | 577 ms | +1.2 % | 80.7 MiB | +0.1 % | 218.2 MiB | -15.9 % | **0.87** |  |
| NestedColumnScan | hardwoodColumnReaders | 2,822 ms | -1.7 % | 20,040 ms | -1.1 % | 6.0 GiB | -0.0 % | 226.7 MiB | +1.5 % | 0.29 |  |
| NestedScan | hardwoodRowReaderTyped | 168 ms | +1.4 % | 413 ms | -0.4 % | 180.8 MiB | +0.0 % | 652.9 MiB | -0.8 % | **0.96** |  |
| OneBrc | hardwoodColumnIds | 1,314 ms | +0.1 % | 2,520 ms | +0.2 % | 1.1 GiB | -0.0 % | 142.8 MiB | -0.6 % | **0.99** |  |
| OneBrc | hardwoodColumnSplits | 501 ms | +0.5 % | 3,626 ms | -0.1 % | 1.1 GiB | +0.0 % | 631.2 MiB | -18.1 % | 0.01 |  |
| S3Scan | hardwoodFixedSizeBloomLookup | 305 ms | -0.4 % | 122 ms | -15.5 % | 21.7 MiB | +0.2 % |  |  | 0.01 |  |
| S3Scan | hardwoodLargeBloomLookup | 111 ms | -1.2 % | 51 ms | -12.1 % | 7.2 MiB | +0.1 % | 73.4 MiB | -1.6 % | 0.03 |  |
| S3Scan | hardwoodMultiFileScan | 502 ms | +4.8 % | 1,120 ms | +1.8 % | 468.5 MiB | +0.1 % | 187.0 MiB | -0.4 % | 0.23 |  |
| S3Scan | hardwoodProjectedScan | 175 ms | +0.1 % | 278 ms | -0.6 % | 105.7 MiB | +0.2 % | 129.3 MiB | -11.8 % | 0.15 |  |
| S3Scan | hardwoodRemoteBesideWideRemote | 239 ms | -2.4 % | 668 ms | -8.2 % | 315.8 MiB | -0.1 % | 376.8 MiB | +4.0 % | 0.11 |  |
| S3Scan | hardwoodWideFilteredScan | 309 ms | -0.7 % | 345 ms | -4.8 % | 39.9 MiB | +0.3 % |  |  | 0.06 |  |
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.6 ms | -1.0 % | 73.2 ms | +0.1 % | 27.6 MiB | +0.0 % | 85.0 MiB | +2.5 % | 0.67 |  |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28 ms | -3.1 % | 88.6 ms | -0.3 % | 22.0 MiB | -4.9 % | 85.2 MiB | -9.3 % | **0.83** |  |
| WideScan | hardwoodColumnar | 358 ms | -99.1 % | 760 ms | -98.2 % | 232.8 MiB | +0.8 % | 463.1 MiB | -0.9 % | 0.73 |  |
| Write | hardwoodColumnar[ZSTD] | 103 ms | +0.4 % | 410 ms | -0.4 % | 81.5 MiB | -0.0 % | 140.6 MiB | +0.8 % | 0.74 |  |
| Write | hardwoodRow[ZSTD] | 266 ms | -15.1 % | 600 ms | -5.5 % | 119.6 MiB | -8.7 % |  |  | **0.89** |  |

## Change points

Found tonight: a regression at a commit a night measured, a contender unstable when it has not settled for 3 nights in a row, history at a commit only a backfill measured, and improvements.

- **improvement** FilterBenchmark.hardwoodRowReader[selective]: wall_ms -8.9 % from 3c42b98a9 to 3d331abd6
