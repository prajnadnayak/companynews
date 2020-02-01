FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
COPY ./static/ /usr/share/nginx/html/company/
COPY ./companynews.conf /etc/nginx/conf.d/
