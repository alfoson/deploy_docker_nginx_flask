FROM nginx:latest
RUN rm /etc/nginx/conf.d/default.conf
RUN rm /etc/nginx/nginx.conf
ADD ./nginx/nginx.conf /etc/nginx
EXPOSE 8888
CMD ["nginx"]