docker-jenkins-swarm
====================

Docker image for Jenkins, with swarm plugin installed.
Based on the [official image](https://registry.hub.docker.com/_/jenkins/).

Can be used with Docker slaves from [`nboncoure/jenkins-swarm-slave`](https://registry.hub.docker.com/u/nboncoure/jenkins-swarm-slave/)

# Running

    docker run --name jenkins -p 8080:8080 -p 50000:50000 -v /var/jenkins_home nboncoure/jenkins-swarm

# Building

    docker build -t nboncoure/jenkins-swarm .
