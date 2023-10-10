# connect to container
```sh
docker-compose exec mongodb bash
```
## connect with mongosh
```sh
mongosh "mongodb://root:root@localhost:27017/?tls=false&authMechanism=DEFAULT"
mongosh "mongodb+srv://root:root@mongodb101.3taayxg.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use('platzi_store')
db.productos.find()
```

