# MicroManager Demo

This repo is about Docker images for micromanager demos.

## Usage

Use the already built image from docker hub:
```
docker pull oeway/micromanager-demo
```

An environment variables can be used to find out the path of micromanager: `MMCORE_PATH`

You can also find a demo config file via `MMCONFIG_DEMO_PATH`.

Build the docker file:
```bash
docker build --tag micromanger-demo .
```