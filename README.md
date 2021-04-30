# saltmaster-dev-environment

A simple docker based dev environment with a saltmaster with a single minion

Usage:

`docker-compose build`
`docker-compose up`


To run a shell on the saltmaster:
`docker exec -ti saltmaster-local /bin/bash`


To run a shell on the saltminion
`docker exec -ti saltminion-ubuntu-local /bin/bash`
