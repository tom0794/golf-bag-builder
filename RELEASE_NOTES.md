## Release Notes
Run this version of Golf Bag Builder:
```sh
docker compose -f oci://ghcr.io/tom0794/golf-bag-builder/compose:GITHUB_RELEASE up --wait && start http://localhost:8080
```

Run the latest version of Golf Bag Builder:
```sh
docker compose -f oci://ghcr.io/tom0794/golf-bag-builder/compose:latest up --wait && start http://localhost:8080
```

Customize configurations by pulling the docker-compose.yml file:
```sh
docker compose pull ghcr.io/tom0794/golf-bag-builder/compose:latest
```
