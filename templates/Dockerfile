# Step 1: Use official Nginx image
FROM nginx:alpine

# Step 2: Remove default nginx website
RUN rm -rf /usr/share/nginx/html/*

# Step 3: Copy your website files into nginx html directory
COPY . /usr/share/nginx/html

# Step 4: Expose port 80 for HTTP
EXPOSE 80

# Step 5: Start nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
