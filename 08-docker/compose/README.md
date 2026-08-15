# 🧩 Docker Compose

Compose is useful for defining multi-container environments for local development and testing.

```yaml
services:
  web:
    image: nginx
    ports:
      - "8080:80"
```

## Typical use cases

- Application + database
- Local integration testing
- Developer environments
- Reproducing service dependencies
