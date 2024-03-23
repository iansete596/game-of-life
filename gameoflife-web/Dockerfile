FROM tomcat:8-jre8

RUN rm -rf /usr/local/tomcat/webapps/*

COPY target/gameoflife.war /usr/local/tomcat/webapps/ROOT1.war

EXPOSE 8060
CMD ["catalina.sh", "run"]
