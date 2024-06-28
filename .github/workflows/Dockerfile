# Use the official Nginx base image
FROM nginx:latest

# Remove the default Nginx index page
RUN rm /usr/share/nginx/html/index.html

# Copy your custom index.html to the Nginx web directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 to the host
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]
