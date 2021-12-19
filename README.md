#  Using Redis Cache for Golang REST API

- $ps -ef | grep redis  > to check if redis server is running
- $redis-cli > enters Redis CLI
- $SELECT 10 > selects a db type using index from a list [0-15]
- $SET key1 value > sets a kv pair
- $GET key1 > response will be "value"
- $APPEND key1 1 > appends "1" to "value"
- $GET key1 > response will be "value1"
- $KEYS * > response will be list of all keys in the dictionary
- $SET key3 value3 EX 10 > sets a kv pair that expires in 10 secs
- $GET key3 > after 10s will return null