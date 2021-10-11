FROM debian
RUN \
  apt update > /dev/null \
  && apt install -qy git \
# https://github.com/Bash-it/bash-it
  && git clone --depth=1 https://github.com/Bash-it/bash-it.git ~/.bash_it \
  && bash ~/.bash_it/install.sh

WORKDIR /code
