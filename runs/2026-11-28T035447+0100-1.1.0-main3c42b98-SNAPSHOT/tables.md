| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.8 | ±1.6 % |
| Filter | hardwoodDefault[selective] | 5.40 | ±4.5 % |
| Filter | hardwoodRowReader[matchAll] | 38.7 | ±0.6 % |
| Filter | hardwoodRowReader[selective] | 6.59 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.398 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.5 | ±1.0 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.9 (bimodal) | ±10.2 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.0 | ±0.5 % |
| DictionaryFilter | hardwoodRowLtWide | 43.7 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,306 (not settled) | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 497 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 224 | ±0.5 % |
| BinaryScan | hardwoodRowStrings | 994 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 164 | ±1.2 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,881 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 147 | ±1.1 % |
| FlatScan | hardwoodColumnar | 275 | ±0.5 % |
| FlatScan | hardwoodRowReaderIndexed | 432 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 93.3 | ±2.0 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 41,364 (bimodal) | ±8.7 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.4 | ±0.1 % |
| FixedSizeListScan | rowFast[768] | 19.5 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 103 | ±0.3 % |
| Write | hardwoodRow[ZSTD] | 315 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.4 | ±1.6 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.5 | ±0.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±1.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 203 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3c42b98-SNAPSHOT ms | 1.1.0-main3c42b98-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 307 | ±0.9 % |
| S3Scan | hardwoodLargeBloomLookup | 113 | ±1.9 % |
| S3Scan | hardwoodMultiFileScan | 483 | ±4.8 % |
| S3Scan | hardwoodProjectedScan | 175 | ±1.5 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 250 | ±3.9 % |
| S3Scan | hardwoodWideFilteredScan | 311 | ±1.3 % |
