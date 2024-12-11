# Use an official Nginx image as the base
FROM nginx:alpine

# Copy the index.html file into the Nginx document root
COPY index.html /usr/share/nginx/html/

# Expose the port
EXPOSE 80

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
