# Alpine Docker Base Image

## Input Arguments

| Name    | Description                                    | Default Value |
| ------- | ---------------------------------------------- | ------------- |
| VERSION | Version of OS you want use for this base Image | 3.11          |

### Usage

```bash
docker build --build-arg VERSION=3.11 -t quay.io/fosscafe/alpine:3.11 .
docker push quay.io/fosscafe/alpine:3.11
```
