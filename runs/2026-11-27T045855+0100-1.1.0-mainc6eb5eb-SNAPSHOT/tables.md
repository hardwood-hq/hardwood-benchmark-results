| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.3 % |
| Filter | hardwoodDefault[selective] | 5.80 | ±0.9 % |
| Filter | hardwoodRowReader[matchAll] | 39.6 | ±0.1 % |
| Filter | hardwoodRowReader[selective] | 7.36 | ±0.5 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.369 | ±0.5 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.4 | ±0.4 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 36.3 (bimodal) | ±8.0 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.4 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 65.7 (not settled) | ±0.3 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,335 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 546 | ±0.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 222 | ±0.5 % |
| BinaryScan | hardwoodRowStrings | 1,002 | ±1.5 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 160 | ±0.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,769 | ±0.2 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 179 | ±0.9 % |
| FlatScan | hardwoodColumnar | 290 | ±0.2 % |
| FlatScan | hardwoodRowReaderIndexed | 426 | ±0.6 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 120 | ±0.4 % |
| NarrowScan | hardwoodRowReaderIndexed | 190 | ±0.3 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 5,260 | ±0.7 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 15.1 | ±1.0 % |
| FixedSizeListScan | rowFast[768] | 23.8 | ±0.3 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±1.3 % |
| Write | hardwoodRow[ZSTD] | 297 | ±0.1 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 35.1 | ±0.8 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 | ±0.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 121 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 207 | ±0.3 % |
| Benchmark | Contender | 1.1.0-mainc6eb5eb-SNAPSHOT ms | 1.1.0-mainc6eb5eb-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 400 | ±1.5 % |
| S3Scan | hardwoodLargeBloomLookup | 345 | ±0.4 % |
| S3Scan | hardwoodMultiFileScan | 540 | ±1.5 % |
| S3Scan | hardwoodProjectedScan | 182 | ±1.0 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 252 | ±2.0 % |
| S3Scan | hardwoodWideFilteredScan | 312 | ±0.7 % |
