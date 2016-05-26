FROM centos:6.6

RUN yum clean all && yum install -y wget git sudo tar curl openssh-server openssh-clients vim net-tools httpd libxml2 libxslt createrepo && chkconfig httpd on

VOLUME /var/log
EXPOSE 80

ENV PS1 "[\u@docker-foo \W]# "