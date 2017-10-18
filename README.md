# Docker Bench for Security

![Docker Bench for Security running](https://raw.githubusercontent.com/docker/docker-bench-security/master/benchmark_log.png "Docker Bench for Security running")

The Docker Bench for Security is a script that checks for dozens of common
best-practices around deploying Docker containers in production. The tests are
all automated, and are inspired by the [CIS Docker Community Edition Benchmark v1.1.0](https://benchmarks.cisecurity.org/tools2/docker/CIS_Docker_Community_Edition_Benchmark_v1.1.0.pdf).
We are releasing this as a follow-up to our [Understanding Docker Security and Best Practices](https://blog.docker.com/2015/05/understanding-docker-security-and-best-practices/)
blog post.

We are making this available as an open-source utility so the Docker community
can have an easy way to self-assess their hosts and docker containers against
this benchmark.