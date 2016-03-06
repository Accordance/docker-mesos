docker-mesos
=====

A distributed computing cluster-in-a-box: Mesos, zookeeper, marathon.

This is a basic block for a development environment for Mesos components.

This setup is used to run Mesos Docker workloads on development environment, while it is in itself running inside Docker.

###Use:
* Clone repository
* bundle install
* docker_rack exec mesos:start

To open up the Mesos UI, open http://your docker host's IP:5050

Marathon UI: open http://your docker host's IP:8282
