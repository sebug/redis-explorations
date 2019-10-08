# Redis, ce n'est pas que pour faire du cache
webmardi

https://www.meetup.com/de-DE/webmardi/events/264525592/

Interesting data structures to look at

Two modes of persistence:

RDB - snapshot
AOF - append-only file, log of actions

## Data Structures
Bloom filters - is this element in the set? -> probability

Hashes - key-values below the name, avoids race conditions.

Sets - SADD, SCARD. Can do union, intersect, segmentation.

Sorted sets - leaderboards :-)

HyperLogLog - allows to estimate the number of elements we're gonna have.

## Cluster / Replication
Data Set doesn't fit in RAM - Redis Cluster

Data Set fits in RAM, but you want high availability - Redis Sentinel

## Pub / Sub
You can, but do you want to? If you use streams, then you can have message confirmation.

## Lua!
Avoids back-and forth, and it's atomic.


