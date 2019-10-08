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


