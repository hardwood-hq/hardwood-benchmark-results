# Nightly 2026-11-27

| | |
|---|---|
| Version | 1.1.0-main98097e6-SNAPSHOT |
| Commit | [98097e675](https://github.com/hardwood-hq/hardwood/commit/98097e6750d6daa7a6cc06238269d14d3a1df026) |
| Run | 2026-11-27T03:01:35+0100 |
| Machine | [md02f92f9f202](../machines/md02f92f9f202.json) |
| Duration | 65 min |

Each metric against the median of the series' last 5 nights. The caller share is the CPU time of the thread calling the benchmark against wall time; in bold from 0.8, where that thread hardly waits on Hardwood and wall time misses decode changes that CPU time still shows.

| Benchmark | Contender | Wall | | CPU | | Allocated | | Heap after GC | | Caller share | |
|---|---|--:|--:|--:|--:|--:|--:|--:|--:|--:|---|
| BinaryScan | hardwoodColumnViews | 220 ms | -1.3 % | 1,644 ms | -1.9 % | 369.8 MiB | -0.0 % | 168.2 MiB | -0.9 % | 0.53 |  |
| BinaryScan | hardwoodRowStrings | 997 ms | -0.1 % | 2,520 ms | -2.7 % | 768.6 MiB | +0.1 % | 297.1 MiB | +2.3 % | **0.96** |  |
| BloomFilter | hardwoodBloom[absent] | 0.402 ms | +1.1 % | 0.636 ms | +0.4 % | 40.7 KiB | +1.6 % | 71.8 MiB | +0.4 % | 0.66 |  |
| DictionaryFilter | hardwoodRowIn | 10.1 ms | +0.4 % | 52.3 ms | -0.2 % | 11.6 MiB | +0.3 % | 81.5 MiB | -0.2 % | 0.44 |  |
| DictionaryFilter | hardwoodRowLtWide | 42.9 ms | -6.4 % | 153 ms | -2.2 % | 32.3 MiB | -0.9 % | 98.1 MiB | -6.3 % | 0.29 |  |
| Filter | hardwoodDefault[matchAll] | 17.6 ms |  | 89.7 ms |  | 40.7 MiB |  | 83.7 MiB |  | **0.81** |  |
| Filter | hardwoodDefault[selective] | 5.43 ms |  | 20.6 ms |  | 6.0 MiB |  | 76.5 MiB |  | 0.50 |  |
| Filter | hardwoodRowReader[matchAll] | 38.8 ms |  | 104 ms |  | 29.6 MiB |  | 75.8 MiB |  | **0.93** |  |
| Filter | hardwoodRowReader[selective] | 6.03 ms |  | 20.1 ms |  | 5.4 MiB |  | 75.1 MiB |  | 0.57 |  |
| FixedSizeListScan | columnFast[768] | 12.4 ms | +0.3 % | 50.6 ms | +0.0 % | 31.8 MiB | +0.0 % | 84.2 MiB | +6.6 % | **0.89** |  |
| FixedSizeListScan | rowFast[768] | 19.5 ms | -0.2 % | 54.8 ms | +0.9 % | 31.9 MiB | +0.0 % | 91.1 MiB | -0.6 % | **0.95** |  |
| FlatScan | columnarDrain | 148 ms |  | 914 ms |  | 542.0 MiB |  | 427.1 MiB |  | 0.39 |  |
| FlatScan | hardwoodColumnar | 275 ms | +0.9 % | 1,088 ms | +0.7 % | 609.9 MiB | +0.1 % | 376.5 MiB | -3.6 % | **0.85** |  |
| FlatScan | hardwoodRowReaderIndexed | 419 ms | -2.6 % | 1,150 ms | -1.7 % | 294.6 MiB | -0.4 % | 788.2 MiB | -52.8 % | **0.93** |  |
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.2 ms | +0.4 % | 144 ms | +1.3 % | 97.4 MiB | +0.0 % | 181.0 MiB | -3.7 % | 0.54 |  |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.5 ms | +0.6 % | 386 ms | -0.2 % | 99.4 MiB | +0.0 % | 209.3 MiB | -1.9 % | 0.23 |  |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 109 ms | +0.7 % | 659 ms | +0.5 % | 74.5 MiB | -0.0 % | 218.5 MiB | -1.4 % | 0.75 |  |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 ms | +0.0 % | 1,272 ms | -0.2 % | 170.8 MiB | -0.0 % | 252.3 MiB | -0.1 % | 0.79 |  |
| NarrowScan | hardwoodColumnar | 93.6 ms | +0.9 % | 531 ms | -0.3 % | 268.6 MiB | -0.0 % | 186.1 MiB | +17.7 % | 0.69 |  |
| NarrowScan | hardwoodRowReaderIndexed | 169 ms | +0.1 % | 567 ms | -0.3 % | 80.6 MiB | -0.1 % | 228.1 MiB | -4.0 % | **0.87** |  |
| NestedColumnScan | hardwoodColumnReaders | 2,842 ms | -0.7 % | 20,100 ms | -0.7 % | 6.0 GiB | -0.0 % | 223.7 MiB | -3.0 % | 0.29 |  |
| NestedScan | hardwoodRowReaderTyped | 164 ms | -0.7 % | 418 ms | -0.1 % | 180.8 MiB | -0.2 % | 553.0 MiB | -28.4 % | **0.95** |  |
| OneBrc | hardwoodColumnIds | 1,314 ms | +0.0 % | 2,510 ms | -0.2 % | 1.1 GiB | +0.0 % | 143.6 MiB | -0.4 % | **0.99** |  |
| OneBrc | hardwoodColumnSplits | 493 ms | -0.2 % | 3,605 ms | -0.1 % | 1.1 GiB | +0.0 % | 795.4 MiB | -11.6 % | 0.01 | not settled |
| S3Scan | hardwoodFixedSizeBloomLookup | 307 ms | -0.2 % | 110 ms | -27.9 % | 21.6 MiB | -0.3 % |  |  | 0.01 |  |
| S3Scan | hardwoodLargeBloomLookup | 109 ms | -2.5 % | 53 ms | -2.7 % | 7.1 MiB | -0.2 % | 73.6 MiB | -0.6 % | 0.03 |  |
| S3Scan | hardwoodMultiFileScan | 490 ms | -2.2 % | 1,100 ms | -1.8 % | 468.6 MiB | +0.1 % | 194.1 MiB | +0.6 % | 0.24 |  |
| S3Scan | hardwoodProjectedScan | 174 ms | -0.8 % | 267 ms | -3.6 % | 105.7 MiB | +0.0 % | 135.9 MiB | +2.3 % | 0.15 |  |
| S3Scan | hardwoodRemoteBesideWideRemote | 250 ms | +2.6 % | 696 ms | +4.5 % | 315.9 MiB | -0.1 % | 360.4 MiB | +2.2 % | 0.11 |  |
| S3Scan | hardwoodWideFilteredScan | 310 ms | -0.4 % | 360 ms | +16.1 % | 39.9 MiB | +0.1 % |  |  | 0.06 |  |
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.5 ms | -1.6 % | 72.4 ms | -0.8 % | 27.6 MiB | -0.0 % | 83.4 MiB | +1.0 % | 0.66 |  |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28 ms | -3.9 % | 88.6 ms | +0.1 % | 22.0 MiB | -5.5 % | 94.8 MiB | +8.8 % | **0.83** |  |
| WideScan | hardwoodColumnar | 357 ms |  | 763 ms |  | 231.3 MiB |  | 414.1 MiB |  | 0.72 |  |
| Write | hardwoodColumnar[ZSTD] | 101 ms | -1.7 % | 410 ms | +0.2 % | 81.6 MiB | +0.1 % | 141.8 MiB | +1.4 % | 0.75 |  |
| Write | hardwoodRow[ZSTD] | 269 ms | -14.0 % | 592 ms | -7.4 % | 119.9 MiB | -8.6 % |  |  | **0.87** |  |

## Change points

No new regression.
