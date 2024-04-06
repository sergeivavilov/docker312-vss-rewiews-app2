FROM --platform=linux/amd64 nginx
WORKDIR /usr/share/nginx/html
COPY . . 
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]