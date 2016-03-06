FROM mesos_base
MAINTAINER Igor Moochnick <igor@igorshare.com>

# Mesos fetcher uses unzip to extract staged zip files

RUN \
  apt-get install -y unzip && \
  apt-get clean

EXPOSE 5051
CMD ["mesos-slave"]
