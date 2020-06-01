# Buidl Docker image
```
docker build -t danielnaranjo/node-web-app .
```

# Execute 
```
docker run -p 49160:3000 -d danielnaranjo/node-web-app
```

# Get container ID
```
$ docker ps
```

# Print app output
```
$ docker logs <container id>
$ docker exec -it <container id> /bin/bash
$ docker ps
```

# Test
```
curl -i localhost:49160
```
