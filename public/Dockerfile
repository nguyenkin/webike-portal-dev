# production environment
FROM nginx:stable-alpine
RUN mkdir -p /usr/share/nginx/html/.well-known
COPY nginx.conf /etc/nginx
COPY apple-app-site-association /usr/share/nginx/html/.well-known
CMD ["nginx", "-g", "daemon off;"]