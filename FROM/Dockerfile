ARG version="latest"
FROM almalinux:$version

RUN dnf install nginx -y 
ARG course="devops"
ENV duration=$course
RUN echo "$course"
RUN echo "version"

CMD ["nginx", "-g","daemon off;"]