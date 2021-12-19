#  Using Redis Cache for Golang REST API

- $ps -ef | grep redis  > to check if redis server is running
- $redis-cli > enters Redis CLI
- $SELECT 10 > selects a db type using index from a list [0-15]
- $SET key1 value > sets a kv pair
- $GET key1 > response will be "value"
- $APPEND key1 1 > appends "1" to "value"
- $GET key1 > response will be "value1"

