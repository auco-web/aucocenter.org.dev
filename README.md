# aucocenter.org
# Great resource for getting unicode index of special Vietnamese characters
# http://www.fileformat.info/info/unicode/char/search.htm?q=%E1%BA%A3&preview=entity
# ---- DOCKER ----
# start jekyll for local testing on docker/ubuntu:
# jekyll serve --host 0.0.0.0 --incremental --config _config.yml,_config_dev.yml &
# ---- UBUNTU ----
# start jekyll for local testing on ubuntu:
# jekyll serve --host 127.0.0.1 --incremental --config _config.yml,_config_dev.yml &
# ---- NITROUS ----
# start jekyll for local testing on nitrous:
# jekyll serve --incremental --host 0.0.0.0 --config _config.yml,_config_nitrous.yml &
# Preview nitrous in browser: http://jekyll-142416.nitrousapp.com:4000/
# ---- CLOUD9 ----
# start jekyll for local testing on c9:
# jekyll serve --incremental --host $IP --port $PORT --config _config.yml,_config_c9.yml &
# Preview c9 in browser: https://aucocenter-dev-nghin.c9users.io:8080/
# ---- JEKYLL ----
# Required for jekyll 3.0
# sudo gem install jekyll-paginate
# gem install jekyll-gist
# ---- ALIASES ----
# alias js='jekyll serve --host localhost --incremental --drafts --config _config.yml,_config_dev.yml &'
# alias jbd='jekyll build --drafts --config _config.yml,_config_dev.yml'
# alias jbs='jekyll build --config _config.yml,_config_site.yml'
# alias git-org='git config --get remote.origin.url'
# alias git-cache-exit='git credential-cache exit'
# alias git-cache="git config credential.helper 'cache --timeout=1000'"
# 
# Docker stuff
# apt-get install -y locales
# dpkg-reconfigure locales &&  locale-gen C.UTF-8 &&  /usr/sbin/update-locale LANG=C.UTF-8
# dpkg-reconfigure locales &&  locale-gen en_US.UTF-8 &&  /usr/sbin/update-locale LANG=en_US.UTF-8
# echo 'en_US.UTF-8 UTF-8' >> /etc/locale.gen &&   locale-gen
# export LC_ALL=C.UTF-8
# export LANG=en_US.UTF-8
# export LANGUAGE=en_US.UTF-8
