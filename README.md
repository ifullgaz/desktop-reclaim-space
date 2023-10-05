# Desktop Reclaim Space

Reclaims unused space in the Docker image file.
Same as docker/desktop-reclaim-space but generated for linux/amd64 and,linux/arm64.

## Build
For local build, use for instance:

```
docker build -t desktop-reclaim-space:latest . 
```

For docker hub build, use:

```
docker pull ifullgaz/desktop-reclaim-space:latest
```

## Usage

```
docker run --privileged --pid=host ifullgaz/desktop-reclaim-space
```
