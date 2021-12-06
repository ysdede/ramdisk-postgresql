This script downloads and extracts a ready-to-use Jesse database from github to ramdisk.  
The archive contains Binance Spot BTC/ETH/BNB candle data since 2018-03.  
You can make it permanent by redirecting output to the default postgresql db directory (but be careful not to break any existing databases if you have one already).  

It requires at least 3 GB of additional memory on debian/ubuntu-based systems with Postgresql version 14.  
The database creation process takes about a minute.  
This may appear to be a waste of time, but it allows me to create 1000 Quantstats reports at once.  

TODO: Add a multithreading uncompression algorithm to help it run faster.

See releases for links.
