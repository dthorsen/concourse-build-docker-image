FROM centos:7

RUN yum -y install git curl
RUN curl -LO https://omnitruck.chef.io/install.sh && bash ./install.sh -v 12.11.18 && rm install.sh
