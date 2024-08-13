VERSION := dagster-v1.8.0
IMAGE_NAME_BASE=primehub-apps
IMAGE_BASE=infuseai/${IMAGE_NAME_BASE}

build:
	docker build . -t ${IMAGE_BASE}:${VERSION}

push:
	docker push ${IMAGE_BASE}:${VERSION}
