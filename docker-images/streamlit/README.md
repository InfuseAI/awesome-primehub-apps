# Streamlit service docker image

This is the method to build up Streamlit service docker image.

## How to use it?

- Build the docker image
```bash
$ make build
```

- Push the docker image
```bash
$ make push
```

## Makefile variable
- `VERSION`: The version tag of docker image.
- `IMAGE_NAME_BASE`: The name of docker image.
- `IMAGE_BASE`: The orginization of docker image.