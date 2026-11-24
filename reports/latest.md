# Nightly 2026-11-24

| | |
|---|---|
| Version | 1.1.0-main25e397d-SNAPSHOT |
| Commit | [25e397dd4](https://github.com/hardwood-hq/hardwood/commit/25e397dd44b5652ea25c9927f61728c374c78c4f) |
| Run | 2026-11-24T03:01:28+0100 |
| Machine | [md02f92f9f202](../machines/md02f92f9f202.json) |
| Duration | 58 min |

Each metric against the median of the series' last 5 nights.

| Benchmark | Contender | Wall | | CPU | | Allocated | | Live set | | |
|---|---|--:|--:|--:|--:|--:|--:|--:|--:|---|
| BinaryScan | hardwoodColumnViews | 224 ms | +0.3 % | 1,676 ms | -0.4 % | 370.3 MiB | +0.1 % | 169.8 MiB | +8.2 % |  |
| BinaryScan | hardwoodRowStrings | 1,003 ms | +0.6 % | 2,570 ms | -0.8 % | 769.0 MiB | +0.2 % | 293.4 MiB | +1.0 % |  |
| BloomFilter | hardwoodBloom[absent] | 0.398 ms | +1.1 % | 0.641 ms | +3.3 % | 40.1 KiB | +0.1 % | 71.2 MiB | -0.4 % |  |
| DictionaryFilter | hardwoodRowIn | 10.1 ms | -0.3 % | 52.4 ms | +0.0 % | 11.6 MiB | -0.7 % | 85.3 MiB | +4.5 % |  |
| DictionaryFilter | hardwoodRowLtWide | 45.9 ms | -0.5 % | 156 ms | -5.9 % | 32.4 MiB | -1.0 % | 101.1 MiB | -17.1 % |  |
| Filter | hardwoodDefault[matchAll] | 17.9 ms | -0.7 % | 88.8 ms | -1.7 % | 40.7 MiB | -0.0 % | 92.8 MiB | +13.3 % |  |
| Filter | hardwoodDefault[selective] | 5.5 ms | -6.6 % | 19.6 ms | -13.1 % | 6.0 MiB | -9.9 % | 72.9 MiB | -4.7 % |  |
| Filter | hardwoodRowReader[matchAll] | 39.2 ms | -0.0 % | 106 ms | -2.6 % | 29.6 MiB | +0.0 % | 74.4 MiB | -26.9 % |  |
| Filter | hardwoodRowReader[selective] | 6.89 ms | -1.5 % | 20.6 ms | -9.4 % | 5.4 MiB | -36.0 % | 77.3 MiB | -3.0 % | not settled |
| FixedSizeListScan | columnFast[768] | 12.4 ms | -1.8 % | 49.5 ms | -5.5 % | 31.8 MiB | +0.0 % | 75.9 MiB | -18.0 % |  |
| FixedSizeListScan | rowFast[768] | 19.6 ms | -0.8 % | 54.3 ms | -1.8 % | 31.9 MiB | +0.0 % | 91.6 MiB | +0.5 % |  |
| FlatScan | hardwoodColumnar | 272 ms | -0.5 % | 1,080 ms | -0.9 % | 608.8 MiB | -2.6 % | 363.6 MiB | -6.9 % |  |
| FlatScan | hardwoodRowReaderIndexed | 435 ms | +1.2 % | 1,170 ms | -16.4 % | 294.3 MiB | -13.0 % | 1.7 GiB | +103.9 % |  |
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.5 ms | -2.3 % | 142 ms | +0.3 % | 97.4 MiB | +0.0 % | 190.9 MiB | +1.6 % |  |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.6 ms | -0.6 % | 385 ms | -9.8 % | 99.3 MiB | -0.0 % | 213.4 MiB | +3.0 % |  |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 ms | -0.7 % | 652 ms | -1.7 % | 74.4 MiB | -0.1 % | 219.2 MiB | -1.4 % |  |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 ms | -0.6 % | 1,274 ms | -0.2 % | 170.8 MiB | -0.0 % | 252.4 MiB | +1.1 % |  |
| NarrowScan | hardwoodColumnar | 92.3 ms | -2.9 % | 531 ms | -1.4 % | 268.4 MiB | -0.1 % | 158.1 MiB | -15.5 % |  |
| NarrowScan | hardwoodRowReaderIndexed | 169 ms | -0.0 % | 565 ms | -0.9 % | 80.7 MiB | -0.1 % | 312.2 MiB | +31.4 % |  |
| NestedColumnScan | hardwoodColumnReaders | 2,783 ms | -2.7 % | 19,650 ms | -3.0 % | 6.0 GiB | -0.4 % | 234.5 MiB | +1.7 % |  |
| NestedScan | hardwoodRowReaderTyped | 166 ms | +0.7 % | 419 ms | -0.7 % | 181.1 MiB | -13.6 % | 630.0 MiB | -35.1 % |  |
| OneBrc | hardwoodColumnIds | 1,306 ms | -0.7 % | 2,515 ms | -0.5 % | 1.1 GiB | -0.0 % | 144.1 MiB | -0.3 % |  |
| OneBrc | hardwoodColumnSplits | 493 ms | -0.4 % | 3,609 ms | -0.1 % | 1.1 GiB | +0.0 % | 802.4 MiB | -10.8 % |  |
| S3Scan | hardwoodFixedSizeBloomLookup | 308 ms | -0.2 % | 128 ms | -20.3 % | 21.7 MiB | -0.1 % |  |  |  |
| S3Scan | hardwoodLargeBloomLookup | 111 ms | -1.4 % | 52 ms | -8.8 % | 7.2 MiB | -0.0 % | 74.2 MiB | +0.5 % |  |
| S3Scan | hardwoodMultiFileScan | 469 ms | -6.5 % | 1,117 ms | -0.7 % | 468.2 MiB | -0.1 % | 195.0 MiB | +1.0 % |  |
| S3Scan | hardwoodProjectedScan | 175 ms | -2.6 % | 258 ms | -6.6 % | 105.6 MiB | -0.0 % | 142.0 MiB | +7.0 % |  |
| S3Scan | hardwoodRemoteBesideWideRemote | 243 ms | -0.5 % | 658 ms | -2.1 % | 316.3 MiB | -1.8 % | 333.5 MiB | -17.2 % |  |
| S3Scan | hardwoodWideFilteredScan | 310 ms | -0.7 % | 388 ms | +25.0 % | 39.9 MiB | -0.3 % |  |  |  |
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.7 ms | -5.3 % | 72.9 ms | -1.0 % | 27.6 MiB | -5.5 % | 84.1 MiB | +1.9 % |  |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.6 ms | +1.9 % | 90.7 ms | +2.4 % | 23.2 MiB | -0.4 % | 97.9 MiB | +12.4 % | bimodal |
| Write | hardwoodColumnar[ZSTD] | 104 ms | +0.5 % | 419 ms | +2.4 % | 81.6 MiB | +0.1 % | 139.8 MiB | -0.3 % |  |
| Write | hardwoodRow[ZSTD] | 320 ms | +2.4 % | 658 ms | +2.7 % | 131.1 MiB | +0.0 % |  |  |  |

## Change points

No new regression.
