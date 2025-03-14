FROM almalinux:9
RUN dnf install nginx -y
ENV course="Devops"\
      time="120 hrs"\
      learner="Sreenivas" 
RUN echo "Hi I am ${learner}"> /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]