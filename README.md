# Supported tags and respective `Dockerfile` links

- [`5.7`, `latest` (*5.1/Dockerfile*)](https://github.com/5ndn/docker-phpunit/blob/master/5.7/Dockerfile) 

# How to use this image.

```console
phpunit () {
    docker run \
    -t \
    --rm \
    --volume $(pwd):/app:rw \
    5ndn/phpunit \
    "$@"
}
```
