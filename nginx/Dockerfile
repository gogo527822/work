# Start with the official NGINX base image
FROM nginx:latest

# Add the custom text file into the NGINX served directory
COPY sre.txt /usr/share/nginx/html/sre.txt

# Expose the default NGINX port
EXPOSE 80

# Command to run NGINX
CMD ["nginx", "-g", "daemon off;"]

