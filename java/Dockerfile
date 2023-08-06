# Tomacat install using Docker file 

FROM tomacat
WORKDIR webapps
COPY target/webapps.war .
RUN rm -rf ROOT && mv webapps.war ROOT.war
ENTRYPOINT [ "sh","/usr/local/tomacat/bin/startup.sh" ]