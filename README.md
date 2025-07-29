# Proyecto Nomade – Infraestructura Dockerizada

Este proyecto contiene la infraestructura de los servicios principales de Nomade:

- **Django**: Backend administrativo
- **Metabase**: Plataforma de visualización de datos
- **NGINX**: Proxy inverso para exponer ambos servicios por subrutas (/django y /metabase)

---

## ⚙️ Requisitos previos

- Docker
- Docker Compose v2
- Red Docker externa creada:

```bash
docker network create nomade_net
docker compose up -d
```