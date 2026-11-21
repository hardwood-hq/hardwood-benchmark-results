| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 63.0 | ±1.3 % |
| Filter | hardwoodDefault[selective] | 7.34 | ±1.0 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.194 | ±8.3 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 482 | ±0.4 % |
| DictionaryFilter | hardwoodRowLtWide | 702 | ±1.9 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 431 | ±0.7 % |
| BinaryScan | hardwoodRowStrings | 950 | ±0.3 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 192 | ±1.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| NestedScan | hardwoodColumnReaders | 6,007 | ±1.1 % |
| NestedScan | hardwoodRowReaderTyped | 192 | ±1.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 430 | ±2.9 % |
| FlatScan | hardwoodRowReaderIndexed | 594 | ±0.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 173 | ±1.2 % |
| NarrowScan | hardwoodRowReaderIndexed | 223 | ±0.4 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 351 | ±1.6 % |
| Write | hardwoodRow[ZSTD] | 514 | ±0.9 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 121 | ±2.0 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 1,056 | ±0.2 % |
| Benchmark | Contender | 1.1.0.Beta1 ms | 1.1.0.Beta1 spread |
|---|---|---:|---:|
| S3Scan | hardwoodLargeBloomLookup | 1,666 | ±0.4 % |
| S3Scan | hardwoodMultiFileScan | 3,466 | ±0.2 % |
| S3Scan | hardwoodProjectedScan | 298 | ±0.4 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 346 | ±1.0 % |
| S3Scan | hardwoodWideFilteredScan | 3,704 | ±0.1 % |
