FROM ubuntu

RUN apt-get update

RUN apt-get install -y python3

RUN apt-get install -y python3-pip

RUN apt-get install -y git gcc apt-utils

RUN apt-get install -y libpng-dev libfreetype6-dev libfreetype6 pkg-config

RUN pip3 install git+https://github.com/mesosphere/dcos-perf-test-driver
