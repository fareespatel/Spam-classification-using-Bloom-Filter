# Bloom-Filter
Bloom Filter Implementation

Uses http://www.stopforumspam.com/downloads/listed username 30.zip as set S (set of usernames known to be spam for the last 30 days). 

Uses http://www.stopforumspam.com/downloads/listed username 365.zip as stream (the spam usernames for the last 365 days).

Implemented a bloom filter using multiple hash functions of murmurHash, FNV and Jenkins Hash functions to identify spam emails based on a stream of 10M+ spam usernames.
