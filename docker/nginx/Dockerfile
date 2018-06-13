From nginx
COPY mysite.conf /etc/nginx/conf.d/mysite.conf
RUN rm /etc/nginx/conf.d/default.conf
COPY ssl/cert /etc/ssl/cert
COPY ssl/private /etc/ssl/private
EXPOSE 80 443