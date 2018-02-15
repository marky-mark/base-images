Note: Before you use these images

* [What is tini?](https://github.com/krallin/tini)
* [Advantages](https://github.com/krallin/tini/issues/8)
* [Ubuntu Images](https://hub.docker.com/_/ubuntu/)

NOTE: If you are using Docker 1.13 or greater, Tini is included in Docker itself. This includes all versions of Docker CE. To enable Tini, just pass the --init flag to docker run.
This is added to ECS...so only use if tini is not included in cluster management tool.

* [Can use Init instead](https://github.com/docker-library/official-images#init)
* [AWS ECS added init flag](https://aws.amazon.com/about-aws/whats-new/2017/11/amazon-ecs-adds-support-for-docker-device-and-init-flags-in-container-task-definitions/)
