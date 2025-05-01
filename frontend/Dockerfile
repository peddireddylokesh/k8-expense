FROM nginx

# Remove default site files
RUN rm -rf /usr/share/nginx/html/*

# Optional: Add a default static page (or skip to use Nginx default)
# RUN echo "<h1>Hello from frontend</h1>" > /usr/share/nginx/html/index.html

# Replace Nginx config to listen on port 8080
COPY default.conf /etc/nginx/conf.d/default.conf
