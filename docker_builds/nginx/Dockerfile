FROM ubuntu/nginx

# WORKDIR /src

# ENV DEBUG=True

RUN apt update
RUN apt install mc -y

COPY home /etc/nginx/sites-available
RUN ln -s /etc/nginx/sites-available/home /etc/nginx/sites-enabled/
RUN rm /etc/nginx/sites-enabled/default

# COPY html/home/ /www/home

EXPOSE 80

