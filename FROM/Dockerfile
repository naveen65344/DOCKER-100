FROM almalinux
ARG name="naveen"
RUN dnf install nginx -y

RUN echo "$name"
CMD [ "nginx","-g","daemon off;" ]
