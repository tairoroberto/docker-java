# Java 8 (1.8.0_111)
### based on Ubuntu 16.04 (Xenial Xerus)
----
### Pull from Docker Hub
```
docker pull tairoroberto/java:latest
```

### Build from GitHub
```
docker build -t tairoroberto/java github.com/tairoroberto/docker-java
```

### Run image
```
docker run -it tairoroberto/java bash
```

### Use as base image
```Dockerfile
FROM tairoroberto/java:latest
```