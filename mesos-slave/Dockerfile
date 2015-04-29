FROM mesos
MAINTAINER  Igor Moochnick <igor@igorshare.com>

CMD ["--master=zk://zookeeper:2181/mesos", "--log_dir=/var/log/mesos"]

ENTRYPOINT ["mesos-slave"]
