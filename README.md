# apartments

Bot for finding apartments on Craigslist.

## Installation

If you have Docker installed and running, you can start the bot by running:

```
$ make
```

If the image doesn't exist locally, Docker will pull it from [Docker Hub](https://hub.docker.com/r/rlucioni/apartments/), create a container, and start it.

Tail a running container's logs:

```
$ make logs
```

Open a shell on a running container:

```
$ make shell
```

For information about additional Make targets:

```
$ make help
```

## Development

Run quality checks:

```
$ make quality
```

Build a new image:

```
$ make image
```

Push it to Docker Hub:

```
$ make push
```
