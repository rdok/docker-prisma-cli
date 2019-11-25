# docker-prisma-cli
Docker mage - alpine box with prisma cli installed. 

## Deploy

```
docker build --tag rdok/prisma-cli:latest
docker build --file Dockerfile --tag rdok/prisma-cli:latest .
docker push rdok/prisma-cli:latest
```

## TODO
Automate deployment either through GitHub, or through a Jenkins declarative pipeline.
