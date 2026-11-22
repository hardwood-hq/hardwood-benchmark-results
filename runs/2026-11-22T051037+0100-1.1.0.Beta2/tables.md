| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 25.2 | ±0.8 % |
| Filter | hardwoodDefault[selective] | 5.89 | ±0.6 % |
| Filter | hardwoodRowReader[matchAll] | 39.3 | ±0.1 % |
| Filter | hardwoodRowReader[selective] | 7.02 | ±0.2 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.107 | ±11.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 18.5 | ±1.6 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.6 | ±0.4 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 35.8 | ±0.3 % |
| DictionaryFilter | hardwoodRowLtWide | 75.9 | ±0.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,447 | ±0.1 % |
| OneBrc | hardwoodColumnSplits | 799 | ±0.4 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 469 | ±0.3 % |
| BinaryScan | hardwoodRowStrings | 959 | ±0.0 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 207 | ±1.8 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 5,039 | ±1.1 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 379 | ±0.6 % |
| FlatScan | hardwoodRowReaderIndexed | 524 | ±1.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 164 | ±0.6 % |
| NarrowScan | hardwoodRowReaderIndexed | 219 | ±0.5 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 303 | ±5.3 % |
| Write | hardwoodRow[ZSTD] | 436 | ±2.3 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 114 | ±0.0 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 1,114 | ±1.4 % |
| Benchmark | Contender | 1.1.0.Beta2 ms | 1.1.0.Beta2 spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 400 | ±0.4 % |
| S3Scan | hardwoodLargeBloomLookup | 336 | ±0.3 % |
| S3Scan | hardwoodMultiFileScan | 1,437 | ±0.4 % |
| S3Scan | hardwoodProjectedScan | 293 | ±1.1 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 390 | ±2.0 % |
| S3Scan | hardwoodWideFilteredScan | 1,071 | ±0.2 % |
