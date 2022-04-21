# openshift-exporter

Openshift exporter for objects metrics

Openshift version 3.11 with operator: https://github.com/integr8ly/application-monitoring-operator/releases/tag/v1.5.0


## build

~~~~
docker login
docker-compose -f docker-compose-build.yml build
docker-compose -f docker-compose-build.yml push
~~~~

## configuration

customize your configuration via environment variables (see example in `docker-compose.yml`)

## run

~~~~
docker-compose up
~~~~

## dependencies if want to run without container

~~~~
pip3 install --user pyaml prometheus_client
~~~~

