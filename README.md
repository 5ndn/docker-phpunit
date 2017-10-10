# Supported tags and respective `Dockerfile` links

- `5.7`, `latest`

# Run phpunit using bashrc or zshrc file

``` sh
phpunit () {
    docker run \
    -t \
    --rm \
    --volume $(pwd):/app:rw \
    5ndn/phpunit \
    "$@"
}
```
