# Redis

```bash
docker exec -it sq-keystore-main_keystore-db-1_1 redis-cli --pass redisadmin

or

docker exec -it sq-keystore-main_keystore-db-1_1 sh 
redis-cli --pass redisadmin

KEYS *
SET NAME ROHIT
GET NAME
DEL NAME
```
