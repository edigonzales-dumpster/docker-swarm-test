# docker-swarm-test

```
docker swarm init
```

```
Swarm initialized: current node (tdchv07x7bvul4e5ruce93l1f) is now a manager.

To add a worker to this swarm, run the following command:

    docker swarm join --token SWMTKN-1-39q4iym2wrrgjl5mrs535koexy164xs4pdaz5ctxtas2nfxoxh-bvw11ezhbj03p88x0bk1rm3gh 192.168.65.3:2377

To add a manager to this swarm, run 'docker swarm join-token manager' and follow the instructions.
```

```
docker stack deploy -c docker-compose.yml ilivalidatorapp
```

```
docker container ls

docker service ls

docker service ps ilivalidatorapp_ilivalidator
```

