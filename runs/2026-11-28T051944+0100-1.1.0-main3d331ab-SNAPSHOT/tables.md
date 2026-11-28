| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.8 | ±1.4 % |
| Filter | hardwoodDefault[selective] | 5.33 | ±3.9 % |
| Filter | hardwoodRowReader[matchAll] | 38.8 | ±0.6 % |
| Filter | hardwoodRowReader[selective] | 6.05 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.406 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.8 | ±1.0 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 27.8 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 43.9 | ±1.7 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,314 | ±0.1 % |
| OneBrc | hardwoodColumnSplits | 498 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 225 | ±0.4 % |
| BinaryScan | hardwoodRowStrings | 1,010 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 167 | ±2.0 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,822 | ±1.6 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 149 | ±1.0 % |
| FlatScan | hardwoodColumnar | 276 | ±0.5 % |
| FlatScan | hardwoodRowReaderIndexed | 428 | ±2.1 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 93.6 | ±0.3 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 375 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.7 | ±0.4 % |
| FixedSizeListScan | rowFast[768] | 19.7 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 103 | ±1.6 % |
| Write | hardwoodRow[ZSTD] | 270 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.5 | ±0.5 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.3 | ±1.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 109 | ±1.4 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 204 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main3d331ab-SNAPSHOT ms | 1.1.0-main3d331ab-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 305 | ±2.0 % |
| S3Scan | hardwoodLargeBloomLookup | 112 | ±1.9 % |
| S3Scan | hardwoodMultiFileScan | 496 | ±7.1 % |
| S3Scan | hardwoodProjectedScan | 175 | ±0.8 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 246 | ±1.7 % |
| S3Scan | hardwoodWideFilteredScan | 312 | ±0.2 % |
