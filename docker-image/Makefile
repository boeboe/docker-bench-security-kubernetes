.PHONY:	docker-bench-security

# cfr https://hub.docker.com/r/docker/docker-bench-security/tags
# cfr https://github.com/docker/docker-bench-security
IMAGE_DOCKER_BENCH_SECURITY = boeboe/docker-bench-security
TAG_DOCKER_BENCH_SECURITY = v1.3.3

default: docker-bench-security

docker-bench-security:
	docker build --pull -t ${IMAGE_DOCKER_BENCH_SECURITY}:latest .
	docker tag ${IMAGE_DOCKER_BENCH_SECURITY}:latest ${IMAGE_DOCKER_BENCH_SECURITY}:${TAG_DOCKER_BENCH_SECURITY}
	docker push $(IMAGE_DOCKER_BENCH_SECURITY):${TAG_DOCKER_BENCH_SECURITY}
	docker push $(IMAGE_DOCKER_BENCH_SECURITY):latest
