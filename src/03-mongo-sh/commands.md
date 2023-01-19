
#### PASO 1: Conectarnos al container docker con mongodb

```sh
docker-compose exec mongodb bash
```

#### PASO 2: Conectarnos a mongodb


```sh
mongosh "<URI>"
```
   *** verificar los puertos en que se configuro mongo en el container
   *** puede ser una URI local o remota(mongo atlas)

```sh
show dbs             // listar data bases
show collections     // listar las colecciones
```

```sh
use("platzi_store")
db.productos.find()
```
