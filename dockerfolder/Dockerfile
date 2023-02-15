FROM devopsedu/webapp
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY /var/lib/jenkins/workspace/pull from github scm/* /usr/src/app
CMD ["php", "./index.php"]

