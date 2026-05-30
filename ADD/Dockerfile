FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/index.html
ADD https://raw.githubusercontent.com/DAWS-82s/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/index.html
CMD ["nginx", "-g", "daemon off;"]
