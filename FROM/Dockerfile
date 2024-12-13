ARG version=latest
FROM almalinux:"$version"
ARG course="devops"
ENV course=$course
RUN echo $course
RUN echo $version
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]
      
