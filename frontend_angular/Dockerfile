# Stage 1: Create an Nginx container
FROM nginx:alpine

# Copy the built Angular app from the build stage to the Nginx web root
COPY dist/frontend_angular /usr/share/nginx/html

# Expose port 80 for Nginx
EXPOSE 80

# Start Nginx when the container is run
CMD ["nginx", "-g", "daemon off;"]