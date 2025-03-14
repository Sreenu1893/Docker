FROM almalinux:9
RUN dnf install nginx -y
ADD https://filesamples.com/samples/document/ott/sample3.ott  /tmp/
CMD ["nginx", "-g", "daemon off;"]