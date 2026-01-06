## Amazon ElastiCache
- RAM is 1000s of times quicker than disk IO systems so accessing things from RAM will always improve performance
- Database in-memory caching service - data types/high availability/replication

### Amazon ElastiCache engine options
#### Memcached or Redis

### Memcached 
- Simple key-value storage
- No built in replication
- Listens on port 11211

### Redis
- Supports more complex data beyond value pairs (hashes, lists, bitmaps)
- Supports build in replication, node failover, backup and restore functionality
- Listens on port 6379