| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 25.1 | ±0.6 % |
| Filter | hardwoodDefault[selective] | 5.57 | ±2.2 % |
| Filter | hardwoodRowReader[matchAll] | 38.9 | ±0.2 % |
| Filter | hardwoodRowReader[selective] | 7.00 | ±0.6 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.064 (not settled) | ±6.9 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 18.6 | ±1.0 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.5 | ±0.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 35.9 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 77.6 | ±1.1 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,446 | ±0.1 % |
| OneBrc | hardwoodColumnSplits | 798 | ±0.1 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 475 | ±1.8 % |
| BinaryScan | hardwoodRowStrings | 958 | ±0.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 210 | ±2.4 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 5,101 | ±0.5 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 250 | ±0.7 % |
| FlatScan | hardwoodColumnar | 384 | ±0.3 % |
| FlatScan | hardwoodRowReaderIndexed | 530 | ±1.1 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 163 | ±0.4 % |
| NarrowScan | hardwoodRowReaderIndexed | 219 | ±0.9 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 2,870 | ±0.5 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 25.1 | ±0.2 % |
| FixedSizeListScan | rowFast[768] | 27.1 | ±0.1 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 276 | ±5.4 % |
| Write | hardwoodRow[ZSTD] | 431 | ±1.9 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 115 | ±0.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 1,107 | ±2.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 400 | ±0.7 % |
| S3Scan | hardwoodLargeBloomLookup | 335 | ±0.3 % |
| S3Scan | hardwoodMultiFileScan | 1,436 | ±0.5 % |
| S3Scan | hardwoodProjectedScan | 292 | ±0.7 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 395 | ±2.1 % |
| S3Scan | hardwoodWideFilteredScan | 1,072 | ±0.1 % |
