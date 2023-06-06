FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
LABEL AUTHOR="ARUNKUMAR"\
      AGE="24"
COPY VI /usr/share/nginx/html/
EXPOSE 8080/tcp
