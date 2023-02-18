https://tech.techtouch.jp/entry/kong-gateway

```
$ curl -i -X POST http://localhost:8001/services \
 --data name=user-api \
 --data url='http://user-api:8002'


$ curl -i -X POST http://localhost:8001/services \
 --data name=client-api \
 --data url='http://api-client:8003'
```
