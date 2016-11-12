FROM jenkinsci/jenkins:2.9
MAINTAINER Jianxin Zhong <jianxin_home@163.com>
USER root
RUN mkdir /var/log/jenkins
RUN mkdir /var/cache/jenkins
RUN chown -R jenkins:jenkins /var/log/jenkins
RUN chown -R jenkins:jenkins /var/cache/jenkins
USER jenkins
EXPOSE 8080
ENV JAVA_OPTS="-Xmx8192m"
