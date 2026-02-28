# Use the lightweight Apache image
FROM httpd:2.4-alpine

# Copy your website files to the Apache document root
COPY ./website/index.html /usr/local/apache2/htdocs/index.html

# Apache listens on port 80 by default
EXPOSE 80
