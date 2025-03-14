FROM almalinux:9
RUN dnf install nginx -y
ADD https://raw.githubusercontent.com/Sreenu1893/Docker/refs/heads/main/Dockerfiles/RUN/Dockerfile  /tmp/
CMD ["nginx", "-g", "daemon off;"]