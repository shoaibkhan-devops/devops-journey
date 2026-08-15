# 📦 Docker Containers

A container is a running instance of an image.

```bash
docker run -d --name demo -p 8080:80 nginx
docker ps
docker logs demo
docker exec -it demo sh
docker stop demo
```

## Lifecycle

```text
Create → Start → Observe → Stop → Remove
```

The same lifecycle thinking applies to production workloads managed by orchestration platforms.
