# Minimum demo camunda 8 process
Build to run on camunda 8.5.0 (rc2)

I don't know why it was so complicated to find a minimum example process that was build for camunda 8.5 without any deprecated annotations and such.

Running against a local installation created via https://github.com/camunda/camunda-platform/blob/main/docker-compose-core.yaml
using docker compose on linux.

environment variables set before running docker compose
```bash
export CAMUNDA_PLATFORM_VERSION=8.5.0
export CAMUNDA_CONNECTORS_VERSION=8.5.0
export ELASTIC_VERSION=8.13.2
```
