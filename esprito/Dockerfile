FROM nginx:alpine
COPY . usr/share/nginx/html
RUN rm usr/share/nginx/html/index.html
COPY engine/templates/engine/index.html usr/share/nginx/html
COPY engine/static usr/share/nginx/html/static