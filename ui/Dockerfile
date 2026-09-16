FROM nginx:1.31.6-alpine

COPY ./build /var/www
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 8080

ENTRYPOINT ["nginx","-g","daemon off;"]

