FROM nginx:alpine
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY index.html /usr/share/nginx/html/index.html
COPY beatbox-verity.mp3 /usr/share/nginx/html/beatbox-verity.mp3
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]