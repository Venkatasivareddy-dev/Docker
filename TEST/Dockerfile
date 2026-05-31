FROM almalinux:9
# Install nginx
RUN dnf install -y nginx && dnf clean all
# Create user
RUN useradd sivareddy
# Set password non-interactively
RUN echo "sivareddy:Password123" | chpasswd
# Start nginx
CMD ["nginx", "-g", "daemon off;"]
