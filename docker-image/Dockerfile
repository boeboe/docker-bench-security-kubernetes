FROM docker/docker-bench-security:latest
MAINTAINER Bart Van Bos <bartvanbos@gmail.com>
LABEL version="1.3.3"
LABEL description="Docker Bench for Security: checks best-practices for deploying Docker containers in production."
LABEL source-repo="https://github.com/boeboe/docker-bench-security-kubernetes.git"

ADD run.sh /run.sh
RUN chmod +x /run.sh
ENTRYPOINT ["/run.sh"]
