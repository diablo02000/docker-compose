# Redis

## Description

Start a Redis cluster with master/slave replication or a simplet replication cluster.

## Configuration

The cluster use [bitnami/redis](https://hub.docker.com/r/bitnami/redis) Docker image.
You can follow the documentation to change the settings thanks to the env variables.

# How to connect

```bash
docker run -it --network redis_redis-cluster --rm redis redis-cli -h redis-cluster-master
```
