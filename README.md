# docker-demo

[![dockeri.co](http://dockeri.co/image/ahlrothanton/docker-demo)](https://registry.hub.docker.com/ahlrothanton/docker-demo)

This is just a simple node app built on top of Docker. It's purpose is just to demo Docker.

## Usage
To build the image locally:

```shell
docker build -t $NAME_OF_IMAGE .
```

To run the image:

```shell
docker run -p 3000:3000 $NAME_OF_IMAGE
```

You can also pull the image from the repository directly:

```shell
docker run -p 3000:3000 ahlrothanton/docker-demo
```
