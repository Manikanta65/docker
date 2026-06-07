FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY expense-frontend-v2/ /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/default.conf

