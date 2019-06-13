# Demo of how to use conda with docker

See the full commit history to see step by step how to use
conda with docker.

# Python + Docker: Hello world sample

Go to "python + docker" commit to see the "Hello World" sample
that uses the most basic configuration for Python + Docker

To build a Docker image do:

```
docker build -t my-docker-python .
```

And to run a docker container from the Docker image created do:
```
docker run my-docker-python
```

