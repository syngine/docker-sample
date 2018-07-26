FROM nginx:alpine
EXPOSE 80
WORKDIR /
COPY nginx.conf /etc/nginx/nginx.conf
CMD ["nginx", "-g", "daemon off;"]