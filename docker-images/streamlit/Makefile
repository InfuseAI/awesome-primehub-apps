VERSION := v1.9.2
IMAGE_NAME_BASE=streamlit
IMAGE_BASE=infuseaidev/${IMAGE_NAME_BASE}

build:
	docker build . -t ${IMAGE_BASE}:${VERSION}

push:
	docker push ${IMAGE_BASE}:${VERSION}