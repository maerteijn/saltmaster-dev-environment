# saltmaster-dev-environment

A simple docker based dev environment with a saltmaster with a single minion

Usage:

`docker-compose build`
`docker-compose up`


See the docker containers running:
`docker ps`

To run a shell on the saltmaster:
`docker exec -ti saltmaster-local /bin/bash`


To run a shell on the saltminion
`docker exec -ti saltminion-ubuntu-local /bin/bash`
