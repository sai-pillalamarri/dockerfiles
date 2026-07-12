FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
EXPOSE 80
COPY content/index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g","daemon off;"]