# 1. Tiny base image that already has nginx + the correct ENTRYPOINT
FROM nginx:alpine

# 2. Copy _everything in this folder_ into nginx’s web root
COPY . /usr/share/nginx/html

# 3. (optional clarity) document container port
EXPOSE 80
