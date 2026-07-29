## How to run

Prerequisites: 

- Make sure to have Docker or podman installed
- Make sure to have initialized the submodule

Use Docker or podman

For Development:
``` bash
docker compose up -f docker-compose.dev.yml
podman compose up -f docker-compose.dev.yml
```

For Production:
``` bash
docker compose up -f docker-compose.yml
podman compose up -f docker-compose.yml
```
