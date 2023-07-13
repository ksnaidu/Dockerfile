FROM centos
RUN ym install epel-release -y
RUN yum install nginx 
RUN rm -rf /usr/share/nginx/html/index.html
COPY /Devops Resume.pdf /usr/share/nginx