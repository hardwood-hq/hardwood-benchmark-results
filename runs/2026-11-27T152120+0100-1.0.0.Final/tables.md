| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 59.9 | ±1.2 % |
| Filter | hardwoodDefault[selective] | 6.64 | ±0.6 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 74.0 | ±0.2 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 33.4 | ±0.6 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 470 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 719 | ±3.3 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 436 | ±0.9 % |
| BinaryScan | hardwoodRowStrings | 938 | ±0.2 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 547 | ±2.5 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 18,732 | ±0.9 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 441 | ±4.4 % |
| FlatScan | hardwoodColumnar | 588 | ±2.0 % |
| FlatScan | hardwoodRowReaderIndexed | 817 | ±8.1 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 224 | ±1.2 % |
| NarrowScan | hardwoodRowReaderIndexed | 268 | ±0.8 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 893 | ±1.3 % |
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.0.0.Final ms | 1.0.0.Final spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 1,158 | ±0.3 % |
| S3Scan | hardwoodLargeBloomLookup | 972 | ±0.2 % |
| S3Scan | hardwoodMultiFileScan | 3,459 | ±0.2 % |
| S3Scan | hardwoodProjectedScan | 303 | ±0.4 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 420 | ±8.2 % |
| S3Scan | hardwoodWideFilteredScan | 3,698 | ±0.1 % |
