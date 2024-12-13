ARG version=latest

RUN dnf install nginx -y
COPY index.html /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]
      
