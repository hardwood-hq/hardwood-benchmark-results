| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 61.9 | ±2.2 % |
| Filter | hardwoodDefault[selective] | 7.57 | ±0.1 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.137 | ±31.5 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 35.4 | ±2.0 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 482 | ±0.5 % |
| DictionaryFilter | hardwoodRowLtWide | 734 | ±1.6 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 431 | ±0.4 % |
| BinaryScan | hardwoodRowStrings | 951 | ±0.7 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 197 | ±1.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 6,042 | ±0.5 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 327 | ±5.3 % |
| FlatScan | hardwoodColumnar | 442 | ±8.7 % |
| FlatScan | hardwoodRowReaderIndexed | 631 | ±2.6 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 173 | ±0.3 % |
| NarrowScan | hardwoodRowReaderIndexed | 224 | ±0.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 2,261 | ±1.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 25.0 | ±0.1 % |
| FixedSizeListScan | rowFast[768] | 26.8 | ±0.2 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 337 | ±0.9 % |
| Write | hardwoodRow[ZSTD] | 504 | ±2.5 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 122 | ±0.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 1,043 | ±0.2 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 1,056 | ±0.2 % |
| S3Scan | hardwoodLargeBloomLookup | 366 | ±0.4 % |
| S3Scan | hardwoodMultiFileScan | 3,465 | ±0.3 % |
| S3Scan | hardwoodProjectedScan | 296 | ±0.2 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 368 | ±3.2 % |
| S3Scan | hardwoodWideFilteredScan | 3,698 | ±0.1 % |
