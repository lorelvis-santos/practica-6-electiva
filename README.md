# Práctica: servidor web Nginx con Docker Compose

El directorio `src` se monta en el contenedor como contenido web de Nginx.

## Ejecutar

```sh
docker compose up -d
```

Abre <http://localhost:8080> para ver la página `Hola mundo`.

Para detener el contenedor:

```sh
docker compose down
```
