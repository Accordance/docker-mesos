docker-mesos
=====

A distributed computing cluster-in-a-box: Mesos, zookeeper, chronos, marathon.

This is a basic block for a development environment for Mesos components.

This setup is used to run Mesos Docker workloads on development environment, while it is in itself running inside Docker.

###Use:
* Clone repository
* ./build.sh
* fig up

To open up the Mesos UI, open http://your docker host's IP:15050

Chronos UI: open http://your docker host's IP:14400

Marathon UI: open http://your docker host's IP:18080

If you're using boot2docker, to find out your docker host's IP, run <br/>$> boot2docker ip

## Credits:
This is a simplification of: https://github.com/yaronr/docker-mesos
