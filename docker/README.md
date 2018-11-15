## Image vs Container

An instance of an image is called a container. You can have multiple containers
for the same image.

Imagese are created with `docker build`. Images are stored in a docker registry.


- List all images

```
docker images
```

- List all containers

```
docker ps -a
```

- List all running containers

```
docker ps
```

- Login on a shell on a container of an Image

```
docker run -i -t <IMAGE_TAG> /bin/bash
```
