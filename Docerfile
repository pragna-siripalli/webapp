FROM nginx:1.19.8
COPY . /usr/share/nginx/html/
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
EXPOSE 8085
CMD ["nginx", "-g", "daemon off;"]
