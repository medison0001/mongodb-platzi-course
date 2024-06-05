## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
```

```sh
show dbs
```

```sh
use platzi_store
```

```sh
show collections
```

```sh
db.products.find()
```
