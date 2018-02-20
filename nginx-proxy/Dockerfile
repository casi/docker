FROM nginx:stable

COPY rootfs/_site /usr/share/nginx/html
COPY rootfs/etc/nginx/conf.d/default.conf /etc/nginx/conf.d/
COPY rootfs/usr/share/nginx/html/50x.html /usr/share/nginx/html/50x.html

RUN chown -R nginx:nginx /usr/share/nginx/html

EXPOSE 8080
