# Use the official Nginx image
FROM nginx:stable

# Update package list and install vim
RUN apt-get update && apt-get install -y vim

# Copy custom Nginx configuration file (optional)
# COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80
EXPOSE 80

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
