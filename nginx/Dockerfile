FROM nginx:stable-alpine3.17
## Copy a new configuration file setting listen port to 8080
COPY ./nginx/default.conf /etc/nginx/conf.d/
#COPY index.html /usr/share/nginx/html/
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]