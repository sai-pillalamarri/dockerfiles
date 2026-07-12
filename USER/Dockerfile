FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
RUN useradd roboshop
USER roboshop
CMD ["nginx","-g","daemon off;"]