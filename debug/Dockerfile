FROM centos:7

COPY  . /tmp/debug

RUN \
mv /tmp/debug/mongodb.repo /etc/yum.repos.d; \
yum install -y mongodb-org-shell-4.0.5 mongodb^org-tools-4.0.5; \
yum clean all;