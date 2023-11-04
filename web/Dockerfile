FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD roboshop.conf /etc/nginx/default.d/roboshop.conf
COPY /usr/share/nginx/html