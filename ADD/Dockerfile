FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/DAWS-82s/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod 644 /usr/share/nginx/html/index.html
ADD MobaXterm_Portable_v25.0 /tmp/
CMD ["nginx", "-g", "daemon off;"]
