FROM nginx:stable

COPY rootfs/etc/nginx/conf.d/default.conf /etc/nginx/conf.d/

RUN chown -R nginx:nginx /usr/share/nginx/html

EXPOSE 8080
