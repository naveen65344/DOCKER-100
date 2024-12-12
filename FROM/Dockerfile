FROM almalinux
RUN dnf install nginx -y 
ENV course="devops"
ARG duration="120"
RUN echo "$course"

CMD ["nginx", "-g","daemon off;"]