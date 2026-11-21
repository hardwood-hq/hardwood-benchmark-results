| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 59.9 | ±0.7 % |
| Filter | hardwoodDefault[selective] | 6.71 | ±0.7 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 74.3 | ±0.2 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 34.7 | ±1.9 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 469 | ±0.4 % |
| DictionaryFilter | hardwoodRowLtWide | 697 (not settled) | ±3.4 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 432 | ±0.5 % |
| BinaryScan | hardwoodRowStrings | 934 | ±0.7 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 590 | ±1.2 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| NestedScan | hardwoodColumnReaders | 16,763 | ±1.2 % |
| NestedScan | hardwoodRowReaderTyped | 590 | ±1.2 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 590 | ±1.8 % |
| FlatScan | hardwoodRowReaderIndexed | 742 | ±8.0 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 224 | ±0.2 % |
| NarrowScan | hardwoodRowReaderIndexed | 266 | ±0.6 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| S3Scan | hardwoodLargeBloomLookup | 414 | ±0.2 % |
| S3Scan | hardwoodMultiFileScan | 3,509 | ±0.0 % |
| S3Scan | hardwoodProjectedScan | 312 | ±0.3 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 424 | ±7.1 % |
| S3Scan | hardwoodWideFilteredScan | 3,709 | ±0.0 % |
