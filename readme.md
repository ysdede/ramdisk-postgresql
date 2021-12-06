This script downloads a ready to use jesse database from github and extracts to ramdisk. Archive contains Binance Spot BTC/ETH/BNB candle data since 2018-03. You can redirect db folder output to default postgresql db directory to make it permanent (Be careful if you already have a database, don't break it). It works on debian/ubuntu based systems with Postgresql version 14, requires at least 3 GB additional memory. It takes about 1 minute to create database. It works for me :slight_smile: This may seem like unnecessary effort, but it helps me a lot to create 1000 Quantstats report at once.

TODO: Add a multithreading uncompression algorithm to help it run faster.

See releases for links.
