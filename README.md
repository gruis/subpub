The subpub project is a set of servers that implement the Redis
Publish/Subscribe protocol in various languages. It is entirely a
self-education project. None of the servers are recommended for real
use.

# Requirements
Each server must be able to parse the unified request protocol and
inline commands. The servers must also implement all of the following
commands:

* [SHUTDOWN](http://redis.io/commands/shutdown)
* [QUIT](http://redis.io/commands/quit)
* [PUBLISH](http://redis.io/commands/publish)
* [SUBSCRIBE](http://redis.io/commands/subscribe)
* [UNSUBSCRIBE](http://redis.io/commands/unsubscribe)
* [PSUBSCRIBE](http://redis.io/commands/psubscribe)
* [PUNSUBSCRIBE](http://redis.io/commands/punsubscribe)

# References
* http://redis.io/topics/protocol
* http://redis.io/topics/pubsub
