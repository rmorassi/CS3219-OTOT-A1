FROM nginx:latest

# Create app directory
WORKDIR /nginx-sample

# Configure nginx
RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx

# Bundle app source
COPY *.html ./hidden/

# Expose port
EXPOSE 8080
