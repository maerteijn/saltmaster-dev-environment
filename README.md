# saltmaster-dev-environment

A simple docker based dev environment with a saltmaster with a single minion

Usage:
```bash
docker-compose build
docker-compose up
```


See the docker containers running:
```bash
docker ps
```

To run a shell on the saltmaster:
```bash
docker exec -ti saltmaster-local /bin/bash
```

To run a shell on the saltminion
```bash
docker exec -ti saltminion-ubuntu-local /bin/bash
```
