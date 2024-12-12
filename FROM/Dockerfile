ARG version="1.0"
FROM almalinux:$version

RUN dnf install nginx -y 
ARG course="devops"
ARG duration="120"
RUN echo "$course"

CMD ["nginx", "-g","daemon off;"]