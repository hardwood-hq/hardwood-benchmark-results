| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.0 | ±0.1 % |
| Filter | hardwoodDefault[selective] | 5.82 | ±2.2 % |
| Filter | hardwoodRowReader[matchAll] | 39.5 | ±0.1 % |
| Filter | hardwoodRowReader[selective] | 7.29 | ±0.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.368 | ±0.7 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.2 | ±1.6 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 36.3 | ±0.1 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.3 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 63.6 (not settled) | ±2.7 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,335 | ±0.1 % |
| OneBrc | hardwoodColumnSplits | 544 | ±0.1 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 224 | ±0.9 % |
| BinaryScan | hardwoodRowStrings | 996 | ±1.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 160 | ±1.3 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,769 | ±1.1 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 177 | ±0.8 % |
| FlatScan | hardwoodColumnar | 291 | ±0.5 % |
| FlatScan | hardwoodRowReaderIndexed | 435 | ±3.7 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 122 | ±0.5 % |
| NarrowScan | hardwoodRowReaderIndexed | 190 | ±0.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 5,265 | ±4.9 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 15.3 | ±0.8 % |
| FixedSizeListScan | rowFast[768] | 23.7 | ±0.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±0.2 % |
| Write | hardwoodRow[ZSTD] | 299 | ±0.5 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 34.8 | ±1.0 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 | ±0.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 120 | ±0.4 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 208 | ±0.4 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 398 | ±0.8 % |
| S3Scan | hardwoodLargeBloomLookup | 347 | ±0.5 % |
| S3Scan | hardwoodMultiFileScan | 540 | ±1.1 % |
| S3Scan | hardwoodProjectedScan | 185 | ±0.5 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 249 | ±2.6 % |
| S3Scan | hardwoodWideFilteredScan | 308 | ±1.0 % |
