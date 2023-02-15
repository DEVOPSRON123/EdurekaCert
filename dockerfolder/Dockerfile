FROM devopsedu/webapp
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY -a /var/lib/jenkins/workspace/pull_from_github_scm/* /usr/src/app
CMD ["php", "./index.php"]

