## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://josuehernandez:contraseña@mongodb101.wbxsnx8.mongodb.net/test"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
