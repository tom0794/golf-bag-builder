## golf-bag-builder
> [!NOTE]
> docker must be installed and running to run this app.

To start the latest version of the app, open a terminal and run:
```sh
docker compose -f oci://ghcr.io/tom0794/golf-bag-builder/compose:latest up --wait && start http://localhost:8080
```
To stop the app:
```sh
docker compose down
```
To pull the docker-compose file:
```sh
docker compose pull ghcr.io/tom0794/golf-bag-builder/compose:latest
```
