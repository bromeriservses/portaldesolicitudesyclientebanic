FROM nginx:1.27-alpine

COPY index.html /usr/share/nginx/html/index.html
COPY bos.webp /usr/share/nginx/html/bos.webp
COPY bos2.webp /usr/share/nginx/html/bos2.webp

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
