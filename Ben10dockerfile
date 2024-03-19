FROM nginx:1.24-alpine

# Copy the entire application source code to the default nginx location
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx with daemon off
CMD ["nginx", "-g", "daemon off;"]