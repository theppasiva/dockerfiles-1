FROM almalinux:8
RUN yum install nginx -y
CMD ["nginx","-g","daemon off;"]
COPY index.html /usr/share/nginx/html/index.html