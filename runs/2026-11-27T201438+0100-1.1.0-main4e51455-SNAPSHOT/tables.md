| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.0 | ±0.1 % |
| Filter | hardwoodDefault[selective] | 5.88 | ±1.5 % |
| Filter | hardwoodRowReader[matchAll] | 39.8 | ±0.5 % |
| Filter | hardwoodRowReader[selective] | 7.05 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.375 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.4 | ±0.1 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 35.0 (bimodal) | ±7.5 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.4 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 64.7 (not settled) | ±3.0 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,335 | ±0.2 % |
| OneBrc | hardwoodColumnSplits | 544 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 225 | ±0.8 % |
| BinaryScan | hardwoodRowStrings | 996 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 160 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,760 | ±2.3 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 179 | ±0.5 % |
| FlatScan | hardwoodColumnar | 293 | ±0.6 % |
| FlatScan | hardwoodRowReaderIndexed | 409 | ±1.5 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 122 | ±0.4 % |
| NarrowScan | hardwoodRowReaderIndexed | 179 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 5,223 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 15.2 | ±1.3 % |
| FixedSizeListScan | rowFast[768] | 23.7 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±7.0 % |
| Write | hardwoodRow[ZSTD] | 297 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 35.1 | ±0.7 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 (bimodal) | ±11.7 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 121 | ±0.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 208 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 401 | ±1.3 % |
| S3Scan | hardwoodLargeBloomLookup | 345 | ±0.3 % |
| S3Scan | hardwoodMultiFileScan | 527 | ±1.9 % |
| S3Scan | hardwoodProjectedScan | 185 | ±0.2 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 243 | ±1.8 % |
| S3Scan | hardwoodWideFilteredScan | 313 | ±0.5 % |
