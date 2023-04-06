FROM almalinux:8
RUN yum update -y 
RUN yum install stress-ng -y 
CMD [ "stress-ng","--help" ]

docker run --name jenkins_1 -d -p 8081:8080 jenkins 