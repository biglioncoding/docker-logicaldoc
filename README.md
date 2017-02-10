Introduction
============
Docker for LogicalDoc Community Edition

Base On
==========
This image base on cloudesire/docker-tomcat, which ultimate based upon ubuntu:trusty.

I read the dockerfile and they are trustworthy. 


Usage
=====
docker run --name docker-logicaldoc -it -d -p 8081:8080 -v path-to-repository:/documents biglioncoding/docker-logicaldoc:[latest:7.5.3:7.5.1]

External Links
==============
https://sourceforge.net/projects/logicaldoc
https://github.com/ClouDesire/docker-tomcat
https://github.com/ClouDesire/docker-java
