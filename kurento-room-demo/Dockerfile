FROM maven:3.3-jdk-8-onbuild-alpine
COPY . /usr/src/app
CMD [ "mvn", "compile", "-o", "exec:java"]
EXPOSE 8443