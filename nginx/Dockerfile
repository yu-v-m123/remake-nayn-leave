FROM nginx:latest

RUN rm -f /etc/nginx/conf.d/*

COPY default.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]
