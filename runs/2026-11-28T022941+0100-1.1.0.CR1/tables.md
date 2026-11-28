| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.8 | ±1.5 % |
| Filter | hardwoodDefault[selective] | 5.47 | ±2.8 % |
| Filter | hardwoodRowReader[matchAll] | 38.7 | ±0.4 % |
| Filter | hardwoodRowReader[selective] | 6.61 | ±0.2 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.401 | ±1.1 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.7 | ±1.0 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.7 (bimodal) | ±11.2 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.0 | ±1.0 % |
| DictionaryFilter | hardwoodRowLtWide | 43.9 | ±2.4 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,314 | ±0.5 % |
| OneBrc | hardwoodColumnSplits | 499 | ±0.4 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 221 | ±1.0 % |
| BinaryScan | hardwoodRowStrings | 1,001 | ±0.6 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 163 | ±2.2 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,813 | ±0.2 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 148 | ±1.0 % |
| FlatScan | hardwoodColumnar | 278 | ±1.1 % |
| FlatScan | hardwoodRowReaderIndexed | 438 (bimodal) | ±2.8 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 92.3 | ±1.4 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.4 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 41,661 | ±4.2 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.3 | ±0.4 % |
| FixedSizeListScan | rowFast[768] | 19.6 | ±0.1 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 102 | ±1.1 % |
| Write | hardwoodRow[ZSTD] | 316 | ±0.3 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.5 | ±1.0 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.3 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 201 | ±1.1 % |
| Benchmark | Contender | 1.1.0.CR1 ms | 1.1.0.CR1 spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 306 | ±1.4 % |
| S3Scan | hardwoodLargeBloomLookup | 113 | ±1.8 % |
| S3Scan | hardwoodMultiFileScan | 478 | ±4.9 % |
| S3Scan | hardwoodProjectedScan | 175 | ±1.2 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 236 | ±1.2 % |
| S3Scan | hardwoodWideFilteredScan | 309 | ±2.1 % |
