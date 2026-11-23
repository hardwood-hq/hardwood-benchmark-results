# Nightly 2026-11-23

| | |
|---|---|
| Version | 1.1.0-main5c42836-SNAPSHOT |
| Commit | [5c428366f](https://github.com/hardwood-hq/hardwood/commit/5c428366f47fe456958d8a9aa6959745c93b9c35) |
| Run | 2026-11-23T03:00:31+0100 |
| Machine | [md02f92f9f202](../machines/md02f92f9f202.json) |
| Duration | 39 min |

Each metric against the median of the series' last 5 nights.

| Benchmark | Contender | Wall | | CPU | | Allocated | | Live set | | |
|---|---|--:|--:|--:|--:|--:|--:|--:|--:|---|
| BinaryScan | hardwoodColumnViews | 223 ms | -0.7 % | 1,656 ms | -1.9 % | 369.8 MiB | +0.0 % | 156.9 MiB | +3.5 % |  |
| BinaryScan | hardwoodRowStrings | 998 ms | +0.2 % | 2,535 ms | -2.1 % | 767.5 MiB | +0.0 % | 290.7 MiB | +1.4 % |  |
| BloomFilter | hardwoodBloom[absent] | 0.399 ms | +1.9 % | 0.636 ms | +2.6 % | 40.0 KiB | +0.0 % | 71.5 MiB | -0.1 % |  |
| DictionaryFilter | hardwoodRowIn | 10.1 ms | -67.9 % | 52.4 ms | -11.8 % | 11.5 MiB | -4.7 % | 77.6 MiB | -5.8 % |  |
| DictionaryFilter | hardwoodRowLtWide | 46.1 ms | -39.2 % | 166 ms | -0.3 % | 32.6 MiB | -37.0 % | 104.6 MiB | -24.9 % |  |
| Filter | hardwoodDefault[matchAll] | 18 ms | -0.7 % | 90.4 ms | -1.9 % | 40.7 MiB | -0.3 % | 81.9 MiB | +1.9 % |  |
| Filter | hardwoodDefault[selective] | 5.71 ms | -3.2 % | 21.7 ms | -7.6 % | 6.0 MiB | -11.1 % | 77.1 MiB | +0.8 % |  |
| Filter | hardwoodRowReader[matchAll] | 38.9 ms | -1.0 % | 109 ms | +0.0 % | 29.6 MiB | -8.9 % | 73.8 MiB | -27.5 % |  |
| Filter | hardwoodRowReader[selective] | 6.88 ms | -1.6 % | 20.2 ms | -11.2 % | 5.4 MiB | -35.8 % | 76.3 MiB | -4.3 % | not settled |
| FixedSizeListScan | columnFast[768] | 12.3 ms | -17.5 % | 49.3 ms | -15.6 % | 31.8 MiB | +0.0 % | 79.0 MiB | -15.3 % |  |
| FixedSizeListScan | rowFast[768] | 19.5 ms | -14.7 % | 54 ms | -14.2 % | 31.9 MiB | +0.0 % | 90.6 MiB | -1.1 % |  |
| FlatScan | hardwoodColumnar | 271 ms | -6.5 % | 1,075 ms | -19.2 % | 609.1 MiB | -7.7 % | 403.8 MiB | +4.4 % |  |
| FlatScan | hardwoodRowReaderIndexed | 443 ms | +3.0 % | 1,170 ms | -17.6 % | 295.9 MiB | -13.0 % | 839.4 MiB | -24.1 % |  |
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.2 ms | -3.7 % | 140 ms | -1.8 % | 97.4 MiB | -0.0 % | 184.2 MiB | -2.0 % |  |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.1 ms | -31.2 % | 387 ms | -9.5 % | 99.3 MiB | -5.1 % | 207.2 MiB | +4.0 % |  |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 ms | -5.8 % | 654 ms | -5.7 % | 74.5 MiB | -0.1 % | 224.8 MiB | +1.3 % |  |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 203 ms | -1.3 % | 1,264 ms | -0.9 % | 170.9 MiB | +0.1 % | 249.5 MiB | -0.6 % |  |
| NarrowScan | hardwoodColumnar | 92.8 ms | -23.4 % | 532 ms | -27.7 % | 268.7 MiB | -17.5 % | 187.1 MiB | -36.0 % |  |
| NarrowScan | hardwoodRowReaderIndexed | 168 ms | -6.6 % | 567 ms | -16.9 % | 80.6 MiB | -41.1 % | 189.6 MiB | -48.1 % |  |
| NestedColumnScan | hardwoodColumnReaders | 2,873 ms | +0.4 % | 20,350 ms | +0.5 % | 6.0 GiB | -3.6 % | 230.5 MiB | -4.6 % |  |
| NestedScan | hardwoodRowReaderTyped | 164 ms | -0.7 % | 419 ms | -6.1 % | 180.8 MiB | -16.0 % | 530.8 MiB | -45.3 % |  |
| OneBrc | hardwoodColumnIds | 1,314 ms | -1.2 % | 2,528 ms | -11.5 % | 1.1 GiB | -1.2 % | 143.2 MiB | -1.0 % |  |
| OneBrc | hardwoodColumnSplits | 492 ms | -5.2 % | 3,597 ms | -6.9 % | 1.1 GiB | -0.7 % | 899.6 MiB | +38.1 % |  |
| S3Scan | hardwoodFixedSizeBloomLookup | 306 ms | -1.2 % | 138 ms | -14.1 % | 21.7 MiB | -0.1 % |  |  |  |
| S3Scan | hardwoodLargeBloomLookup | 112 ms | -0.3 % | 50 ms | -21.1 % | 7.2 MiB | -0.0 % | 73.9 MiB | -0.2 % |  |
| S3Scan | hardwoodMultiFileScan | 500 ms | -3.1 % | 1,125 ms | -16.0 % | 468.3 MiB | -6.9 % | 189.4 MiB | -1.8 % |  |
| S3Scan | hardwoodProjectedScan | 176 ms | -4.8 % | 277 ms | -15.3 % | 105.7 MiB | -17.9 % | 126.6 MiB | -7.0 % |  |
| S3Scan | hardwoodRemoteBesideWideRemote | 242 ms | -1.3 % | 666 ms | -26.6 % | 316.0 MiB | -16.6 % | 352.7 MiB | -19.1 % |  |
| S3Scan | hardwoodWideFilteredScan | 311 ms | -0.4 % | 310 ms | -7.5 % | 39.9 MiB | -2.7 % |  |  |  |
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.8 ms | -7.3 % | 73.7 ms | -1.1 % | 27.6 MiB | -5.6 % | 81.3 MiB | -4.9 % |  |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29 ms | -0.5 % | 90 ms | +1.7 % | 23.0 MiB | -1.1 % | 90.8 MiB | +4.1 % | bimodal |
| Write | hardwoodColumnar[ZSTD] | 102 ms | -1.9 % | 405 ms | -0.9 % | 81.5 MiB | +0.1 % | 143.7 MiB | +2.6 % |  |
| Write | hardwoodRow[ZSTD] | 313 ms | +0.2 % | 632 ms | -1.2 % | 131.1 MiB | +11.6 % |  |  |  |

## Change points

No new regression.
