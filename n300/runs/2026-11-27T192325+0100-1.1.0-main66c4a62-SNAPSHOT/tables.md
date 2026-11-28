| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.5 % |
| Filter | hardwoodDefault[selective] | 5.81 | ±0.9 % |
| Filter | hardwoodRowReader[matchAll] | 39.5 | ±0.2 % |
| Filter | hardwoodRowReader[selective] | 7.28 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.369 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.3 | ±1.3 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 31.0 (bimodal) | ±9.2 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.4 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 65.5 (not settled) | ±3.2 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,323 | ±0.5 % |
| OneBrc | hardwoodColumnSplits | 545 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 222 | ±0.4 % |
| BinaryScan | hardwoodRowStrings | 997 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 161 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,771 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 180 | ±1.0 % |
| FlatScan | hardwoodColumnar | 292 | ±0.7 % |
| FlatScan | hardwoodRowReaderIndexed | 427 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 121 | ±0.2 % |
| NarrowScan | hardwoodRowReaderIndexed | 190 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 5,377 | ±4.3 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 15.2 | ±1.0 % |
| FixedSizeListScan | rowFast[768] | 23.8 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 105 | ±0.5 % |
| Write | hardwoodRow[ZSTD] | 297 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 34.7 | ±0.5 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 78.3 | ±0.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 121 | ±0.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 208 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main66c4a62-SNAPSHOT ms | 1.1.0-main66c4a62-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 398 | ±0.8 % |
| S3Scan | hardwoodLargeBloomLookup | 347 | ±0.2 % |
| S3Scan | hardwoodMultiFileScan | 540 | ±1.6 % |
| S3Scan | hardwoodProjectedScan | 185 | ±0.6 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 250 | ±3.8 % |
| S3Scan | hardwoodWideFilteredScan | 312 | ±1.5 % |
