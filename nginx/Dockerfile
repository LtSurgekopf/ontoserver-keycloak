FROM nginx:alpine
RUN mkdir /var/nginx
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./cors_support /etc/nginx/cors_support
COPY ./ssl.conf /etc/nginx/ssl.conf
COPY ./certs/certificate.key /certs/
COPY ./certs/certificate-chain.pem /certs/
COPY ./certs/dhparam /certs/

#you can also create an index.html that lists the endpoints for your server that will be served at the root of your server.
#COPY ./index.html /usr/share/nginx/html/index.html
