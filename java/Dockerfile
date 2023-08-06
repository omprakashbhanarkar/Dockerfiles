# This is a Java Docker file
# Tomacat install using Docker file 

FROM Tomacat
WORKDIR webapps
COPY target/webapps.war .
RUN rm -rf ROOT && mv webapps.war ROOT.war
ENTRYPOINT [ "sh","/usr/" ]