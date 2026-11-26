# Práctica 1 Docker – Node.js + MongoDB Atlas

## Antes de correr
1. Abre `.env` y reemplaza `MONGODB_URI` por tu cadena de conexión de Atlas (Connect > Drivers),
   con tu usuario y clave. En Atlas, Network Access debe permitir tu IP (o 0.0.0.0/0 para la práctica).
2. Inicia Docker Desktop.

## Correr (desde esta carpeta, en PowerShell)
    docker compose up --build

Cuando veas "Conectado a MongoDB Atlas", abre http://localhost:3000

## Probar
- Registrar un producto, editarlo y eliminarlo.
- En Atlas: base `inv` > colección `producto` debe mostrar los documentos.

## Detener
    docker compose down

## Capturas sugeridas para la evidencia
1. Estructura de carpetas en VS Code. 2. .env, .dockerignore, docker-compose.yml y Dockerfile.
3. `docker compose up --build` con "Conectado a MongoDB Atlas". 4. Docker Desktop con el contenedor `project` en ejecución.
5. http://localhost:3000 con la app y productos. 6. Atlas con la colección `producto`.
