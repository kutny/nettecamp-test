FROM nginx:latest

ADD vhosts/nettecamp-test.dev.conf /etc/nginx/conf.d/nettecamp-test.dev.conf

ENV TZ=Europe/Prague
RUN echo $TZ > /etc/timezone

EXPOSE 80