# Use official NGINX image from Docker Hub
FROM nginx:alpine

# Copy the website content to the NGINX server directory
COPY html /usr/share/nginx/html
COPY css /usr/share/nginx/html/css
COPY js /usr/share/nginx/html/js

# Expose port 80 to access the website
EXPOSE 80
