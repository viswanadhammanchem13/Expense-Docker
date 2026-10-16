
FROM nginx
EXPOSE 80
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY static /usr/share/nginx/html/
COPY expense.conf /etc/nginx/expense.conf