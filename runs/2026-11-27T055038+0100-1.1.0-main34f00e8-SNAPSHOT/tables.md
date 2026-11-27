| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.4 % |
| Filter | hardwoodDefault[selective] | 5.80 | ±2.3 % |
| Filter | hardwoodRowReader[matchAll] | 39.5 | ±0.2 % |
| Filter | hardwoodRowReader[selective] | 7.30 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.369 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.5 | ±1.4 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 36.1 (bimodal) | ±8.7 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.4 | ±0.3 % |
| DictionaryFilter | hardwoodRowLtWide | 65.9 (not settled) | ±1.1 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,323 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 545 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 221 | ±0.4 % |
| BinaryScan | hardwoodRowStrings | 991 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 159 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,770 | ±1.5 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 177 | ±0.9 % |
| FlatScan | hardwoodColumnar | 292 | ±0.7 % |
| FlatScan | hardwoodRowReaderIndexed | 425 | ±1.1 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 121 | ±0.1 % |
| NarrowScan | hardwoodRowReaderIndexed | 189 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 5,141 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 15.3 | ±1.4 % |
| FixedSizeListScan | rowFast[768] | 23.7 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±0.6 % |
| Write | hardwoodRow[ZSTD] | 298 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 34.8 | ±0.6 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 121 | ±0.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 208 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main34f00e8-SNAPSHOT ms | 1.1.0-main34f00e8-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 397 | ±1.1 % |
| S3Scan | hardwoodLargeBloomLookup | 347 | ±0.0 % |
| S3Scan | hardwoodMultiFileScan | 527 | ±1.2 % |
| S3Scan | hardwoodProjectedScan | 184 | ±2.1 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 254 | ±4.6 % |
| S3Scan | hardwoodWideFilteredScan | 312 | ±1.0 % |
