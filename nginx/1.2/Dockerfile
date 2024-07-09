FROM nginx:1.2

# Copy configuration files
COPY default.conf /etc/nginx/conf.d/

# Set up the document root
WORKDIR /var/www/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
