# FIXED - corrected "nginx:latests" to "nginx:latest"
FROM nginx:latest           

# FIXED - corrected filename from "nginix.conf" to "nginx.conf"
COPY nginx.conf /etc/nginx/nginx.conf

# (Optional) Copy HTML files
# COPY ./html /usr/share/nginx/html  

# Expose port 80
EXPOSE 80       

# FIXED - corrected "daemon of;" to "daemon off;"
CMD ["nginx", "-g", "daemon off;"]  
