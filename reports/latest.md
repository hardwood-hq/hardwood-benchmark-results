# Nightly 2026-11-22

| | |
|---|---|
| Version | 1.1.0-main5c42836-SNAPSHOT |
| Commit | [5c428366f](https://github.com/hardwood-hq/hardwood/commit/5c428366f47fe456958d8a9aa6959745c93b9c35) |
| Run | 2026-11-22T03:01:28+0100 |
| Machine | [md02f92f9f202](../machines/md02f92f9f202.json) |
| Duration | 47 min |

Each metric against the median of the series' last 5 nights.

| Benchmark | Contender | Wall | | CPU | | Allocated | | Live set | | |
|---|---|--:|--:|--:|--:|--:|--:|--:|--:|---|
| BinaryScan | hardwoodColumnViews | 220 ms | -48.9 % | 1,652 ms | -17.4 % | 369.8 MiB | -61.9 % | 181.0 MiB | +0.3 % |  |
| BinaryScan | hardwoodRowStrings | 998 ms | +5.0 % | 2,590 ms | -7.3 % | 769.0 MiB | -33.1 % | 286.0 MiB | +31.6 % |  |
| BloomFilter | hardwoodBloom[absent] | 0.394 ms | -2.1 % | 0.621 ms | -1.9 % | 40.2 KiB | +0.6 % | 71.3 MiB | -20.0 % |  |
| DictionaryFilter | hardwoodRowIn | 10.1 ms | -97.8 % | 52.4 ms | -92.8 % | 11.6 MiB | -97.1 % | 82.4 MiB | -47.5 % |  |
| DictionaryFilter | hardwoodRowLtWide | 45.7 ms | -93.4 % | 151 ms | -86.8 % | 32.8 MiB | -92.3 % | 139.3 MiB | -1.8 % |  |
| Filter | hardwoodDefault[matchAll] | 17.9 ms | -70.0 % | 92.1 ms | -75.8 % | 40.7 MiB | -75.1 % | 83.1 MiB | -2.0 % |  |
| Filter | hardwoodDefault[selective] | 5.55 ms | -17.3 % | 19.8 ms | -23.2 % | 6.0 MiB | -68.1 % | 76.3 MiB | -8.1 % | bimodal |
| Filter | hardwoodRowReader[matchAll] | 39.1 ms | -0.4 % | 109 ms | -0.3 % | 29.6 MiB | -0.0 % | 100.6 MiB | -1.1 % |  |
| Filter | hardwoodRowReader[selective] | 6.97 ms | +0.0 % | 21.1 ms | +3.2 % | 5.4 MiB | -0.1 % | 77.4 MiB | +0.6 % | not settled |
| FixedSizeListScan | columnFast[768] | 12.3 ms | -33.3 % | 50.6 ms | -28.8 % | 31.8 MiB | -33.0 % | 92.6 MiB | +0.3 % |  |
| FixedSizeListScan | rowFast[768] | 19.5 ms | -15.9 % | 54.2 ms | -28.2 % | 31.9 MiB | -32.9 % | 91.1 MiB | -9.7 % |  |
| FlatScan | hardwoodColumnar | 272 ms | -36.8 % | 1,060 ms | -57.5 % | 609.4 MiB | -52.8 % | 390.6 MiB | -73.0 % |  |
| FlatScan | hardwoodRowReaderIndexed | 430 ms | -35.7 % | 1,157 ms | -60.8 % | 295.8 MiB | -65.6 % | 598.0 MiB | -59.7 % |  |
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.3 ms | +0.8 % | 143 ms | +1.1 % | 97.4 MiB | +0.0 % | 190.4 MiB | +1.3 % |  |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70 ms | -25.9 % | 386 ms | -9.2 % | 99.3 MiB | -44.6 % | 214.4 MiB | +10.4 % |  |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 ms | -1.4 % | 656 ms | -1.1 % | 74.5 MiB | -0.0 % | 221.6 MiB | -1.9 % |  |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 ms | -67.9 % | 1,273 ms | +9.0 % | 170.7 MiB | +3.0 % | 261.9 MiB | +4.9 % |  |
| NarrowScan | hardwoodColumnar | 91.1 ms | -47.4 % | 533 ms | -53.5 % | 268.3 MiB | -53.9 % | 145.3 MiB | -54.8 % |  |
| NarrowScan | hardwoodRowReaderIndexed | 169 ms | -24.2 % | 568 ms | -45.7 % | 80.8 MiB | -76.0 % | 237.7 MiB | +11.5 % |  |
| NestedColumnScan | hardwoodColumnReaders | 2,861 ms | -52.4 % | 20,250 ms | -55.9 % | 6.0 GiB | -74.3 % | 223.8 MiB | -88.0 % |  |
| NestedScan | hardwoodRowReaderTyped | 165 ms | -13.7 % | 416 ms | -26.0 % | 180.8 MiB | -37.5 % | 772.6 MiB | -21.0 % |  |
| OneBrc | hardwoodColumnIds | 1,315 ms | +0.1 % | 2,515 ms | +0.4 % | 1.1 GiB | +0.0 % | 143.4 MiB | -0.8 % |  |
| OneBrc | hardwoodColumnSplits | 494 ms | -0.1 % | 3,607 ms | -0.1 % | 1.1 GiB | +0.0 % | 941.8 MiB | -2.2 % |  |
| S3Scan | hardwoodFixedSizeBloomLookup | 308 ms | -70.9 % | 152 ms | -23.8 % | 21.7 MiB | -5.5 % | 73.6 MiB | +0.0 % |  |
| S3Scan | hardwoodLargeBloomLookup | 112 ms | -69.5 % | 57 ms | -22.3 % | 7.2 MiB | -0.0 % | 73.8 MiB | -61.8 % |  |
| S3Scan | hardwoodMultiFileScan | 501 ms | -85.5 % | 1,120 ms | -32.5 % | 468.4 MiB | -48.8 % | 193.0 MiB | +49.5 % |  |
| S3Scan | hardwoodProjectedScan | 176 ms | -41.2 % | 277 ms | -20.4 % | 105.6 MiB | -50.5 % | 136.2 MiB | -12.4 % |  |
| S3Scan | hardwoodRemoteBesideWideRemote | 245 ms | -29.2 % | 656 ms | -44.6 % | 315.9 MiB | -46.1 % | 402.5 MiB | -50.6 % |  |
| S3Scan | hardwoodWideFilteredScan | 312 ms | -91.5 % | 282 ms | -65.5 % | 40.0 MiB | -72.7 % |  |  |  |
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.7 ms | -57.6 % | 73.7 ms | -64.7 % | 27.6 MiB | -69.1 % | 82.6 MiB | -13.3 % | not settled |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.5 ms | -1.5 % | 87.6 ms | -2.0 % | 23.2 MiB | +0.4 % | 81.8 MiB | -17.1 % |  |
| Write | hardwoodColumnar[ZSTD] | 103 ms | -54.6 % | 407 ms | +7.4 % | 81.5 MiB | +2.6 % | 139.5 MiB | -0.4 % |  |
| Write | hardwoodRow[ZSTD] | 312 ms | -24.7 % | 638 ms | +8.5 % | 131.1 MiB | +7.2 % |  |  |  |

## Change points

No new regression.
