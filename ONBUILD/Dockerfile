FROM almalinux:8
RUN yum install nginx -y
RUN yum -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]