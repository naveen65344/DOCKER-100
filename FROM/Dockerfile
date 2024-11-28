FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx" ,"-g","daemon off;"]
RUN rm -f /usr/share/nginx/html 
COPY index.html /usr/share/nginx/html