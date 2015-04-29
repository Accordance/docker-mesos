FROM mesos
MAINTAINER  Igor Moochnick <igor@igorshare.com>

#EXPOSE 5050

##### For Marathon and Chronos:
RUN echo "zk://zookeeper:2181/mesos" > /etc/mesos/zk

# Configure process supervisor
ADD supervisord.conf /etc/supervisor/supervisord.conf

CMD ["supervisord", "-c", "/etc/supervisor/supervisord.conf"]
