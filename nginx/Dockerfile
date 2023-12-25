FROM nginx

#Delete the Existing default.conf
RUN rm /etc/nginx/conf.d/default.conf

COPY ./index.html /usr/share/nginx/html/index.html
COPY default.conf /etc/nginx/conf.d/
EXPOSE 80