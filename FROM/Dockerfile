ARG version=latest
FROM almalinux:"$version"
ENV course="devops"
RUN echo $course
RUN echo $version
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]
      
