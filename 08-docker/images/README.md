# 🖼️ Docker Images

Docker images are immutable application templates built from layers.

## Build / inspect

```bash
docker build -t demo-app:1.0 .
docker images
docker image inspect demo-app:1.0
```

## Good practices

- Pin base images thoughtfully
- Use multi-stage builds
- Keep images small
- Avoid secrets in Dockerfiles
- Scan images for vulnerabilities
- Use descriptive tags and immutable release references where possible
