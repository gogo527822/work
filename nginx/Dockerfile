# nginx
FROM nginx:latest

COPY sre.txt /usr/share/nginx/html/sre.txt
#RUN echo "Hello SRE!" > /usr/share/nginx/html/sre.txt

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

