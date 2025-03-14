FROM almalinux:9
RUN dnf install nginx -y
ADD https://filesamples.com/formats/ods  /tmp/
CMD ["nginx", "-g", "daemon off;"]