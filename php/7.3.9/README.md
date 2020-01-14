# PHP 7.3.9 Docker Base Image

## Input Arguments

| Name       | Description                       | Default Value                |
| ---------- | --------------------------------- | ---------------------------- |
| BASE_IMAGE | Alpine base image you want to use | quay.io/fosscafe/alpine:3.11 |

### Usage

```bash
docker build --build-arg BASE_IMAGE=quay.io/fosscafe/alpine:3.11 -t quay.io/fosscafe/php:7.3.9 .
docker push uay.io/fosscafe/php:7.3.9
```
