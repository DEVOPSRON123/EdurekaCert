FROM devopsedu/webapp
RUN mkdir -p /usr/src/app
WORKDIR /var/lib/jenkins/workspace/pull_from_github_scm


COPY  /var/lib/jenkins/workspace/pull_from_github_scm/index.php /usr/src/app/
CMD ["php", "./index.php"]

