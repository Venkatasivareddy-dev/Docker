FROM almalinux:9
RUN dnf install nginx -y
#there is no functionality to expose
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]