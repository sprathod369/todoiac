FROM docker.io/nginx:latest
COPY docker/default.conf /etc/nginx/conf.d/default.conf
ADD http://example.com/package.zip /temp
EXPOSE 60 443
RUN chown -R nginx:nginx /usr/share/nginx/html/