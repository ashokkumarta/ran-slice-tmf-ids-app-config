ARG BASE_IMAGE=ashokkumarta/dataapps-ran-slice:latest
FROM $BASE_IMAGE
LABEL AUTHOR="Ashokkumar T A"
COPY ./application.properties /application.properties
ENTRYPOINT ["java","-jar","/app.jar","--spring.config.location=/application.properties"]

