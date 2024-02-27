FROM nginx:latest
LABEL Author="Welber Macedo" 
COPY /client/public /var/www/public
# COPY ./nginx.conf /etc/nginx/nginx.conf
RUN chmod 755 -R /var/www/public
EXPOSE 80
# ENTRYPOINT [ "nginx" ]

CMD [ "-g", "daemon off;" ]