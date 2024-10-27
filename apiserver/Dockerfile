FROM nginx:1.26.2

RUN mkdir /etc/nginx/njs

COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html/
COPY ./njs/jwt.js /etc/nginx/njs/
