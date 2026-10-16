
FROM nginx
EXPOSE 80
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY index.html /usr/share/nginx/html/index.html
COPY static/ /usr/share/nginx/html/static/
COPY expense.conf /etc/nginx/conf.d/default.conf