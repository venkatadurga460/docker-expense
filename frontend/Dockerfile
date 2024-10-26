FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
# COPY code /usr/share/nginx/html
# USER nginx
COPY expense.conf /etc/nginx/default.d/expense.conf

