# IMemcacheClient v.0.2 #
Improved Memcache client (currently only for PHP, but it can be written on any language).
It also supports [Redis](http://code.google.com/p/redis) protocol.

It extends standart features with the following implementations:

  * 'prefix' setting for all keys.

  * Locks. acquire()/release()/isLocked() methods.

  * Distributed queues with multi-views support.

  * Multiple delete.

  * Optional tracing all commands for debugging.
And more.