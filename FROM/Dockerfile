ARG version="latest"
FROM almalinux:$version

RUN dnf install nginx -y 
ARG course="devops"
ARG duration="120"
RUN echo "$course"
RUN echo "version"

CMD ["nginx", "-g","daemon off;"]