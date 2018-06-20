FROM  http://10.24.101.99:8081/artifactory/docker/ubuntu:latest

MAINTAINER Stanley Fong stanleyf@jfrog.com

ADD war/*.war /home/exec/tomcat/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run
