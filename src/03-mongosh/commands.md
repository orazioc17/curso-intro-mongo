## Entrar a la terminal del contenedor que esta ejecutandose

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh ""
```

### Comandos desde mongosh

```sh
show dbs  # Esto nos mostraria las db que tiene ese cluster de informacion

show collections  # ESt nos mostraria las collections de una db
```

### Dentro de mongosh tambien sirven instrucciones como las que hemos ejecutado en el playground
```sh
use("platzi_store")

db.products.find()
```
