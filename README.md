# MySQL + phpMyAdmin

Configuración mínima con Docker Compose para levantar MySQL y phpMyAdmin.

## Requisitos

- Docker
- Docker Compose

## Archivos

- `docker-compose.yml`
- `.env.example`

## Configuración

Copia el archivo de ejemplo y crea tu archivo `.env`:

```bash
cp .env.example .env
```

## Levantar servicios

```bash
docker compose up -d
```

## Acceso

- phpMyAdmin: `http://localhost:8080`

## Detener servicios

```bash
docker compose down
```

## Eliminar también los datos

```bash
docker compose down -v
```
