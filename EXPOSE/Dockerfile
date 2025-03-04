FROM almalinux:9
RUN dnf install nginx -y
#there is no functionality for EXPOSE, it is just for information this is containter port
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]