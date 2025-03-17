FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# This Executes if any user uses your images as their base OS
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]