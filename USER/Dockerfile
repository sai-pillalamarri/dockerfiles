FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
RUN useradd roboshop
RUN chown -R roboshop:roboshop /var/log/nginx /var/lib/nginx /var/run
USER roboshop
CMD ["nginx","-g","daemon off;"]