FROM nginx:latest

# Configure nginx
RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx

# Expose port
EXPOSE 5000
