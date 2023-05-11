Everything is compressed into parquet format, as it allows you to compress the original txt up to 10 times. + increases the speed of reading data from parquet (compared to txt). Plus some cleans are made here as well:
1. Delete incomplete lines
2. We bring the tables to the necessary types
3. Removing duplicate hatters

