FROM devopsedu/webapp
RUN apt-get update && \
    apt-get upgrade
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY ./../website/* /usr/src/app
CMD ["php", "./index.php"]

