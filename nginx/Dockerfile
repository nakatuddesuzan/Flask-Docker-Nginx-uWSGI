# use Nginx image
FROM nginx

# remove the default nginx file
RUN rm /etc/nginx/conf.d/default.conf

# replace with yoiur own nginx file
COPY nginx.conf /etc/nginx/nginx.d/

