# JupyterLab Colab Docker

[**DockerHub Repository Link**](https://hub.docker.com/r/registryhj/jupyterlab-colab)

<br />

## Supported Tags

- [`3.6.3`](https://hub.docker.com/repository/docker/registryhj/jupyterlab-colab/tags/3.6.3/sha256-a4acc730965440f38f9f0773906f73e8bffd7cfaa08688dd0289ef17930b8695): (`3.6.3-jammy`)

<br />

## How to use

**Pull this image:**

```
docker pull registryhj/jupyterlab-colab:<tag_name>
```

**Create container in background process:**

```
docker run -d \
    --name <container_name> \
    -p <port>:8888 \
    -v <dir_name>:/workspace \
    -v <dir_name>/images:/workspace/images \
    -v <dir_name>/data:/workspace/data \
    -e JUPYTER_TOKEN=<token> \
    registryhj/jupyterlab-colab:<tag_name>
```

Now, You can access the browser by entering `http://localhost:<port>`.

<br />

## Supported Architectures

- `linux/amd64`
- `linux/arm64`

# <br />

Copyright © 2025 RegistryHJ
