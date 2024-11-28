FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx" ,"-g","daemon off;"]
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://github.com/naveen65344/k8-practice-25/blob/main/expense-k8/namespace.yml /usr/share/nginx/html