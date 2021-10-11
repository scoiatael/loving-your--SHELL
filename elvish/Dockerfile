FROM debian
RUN \
  apt update > /dev/null \
  && apt install -qy elvish

WORKDIR /code
ENTRYPOINT ["/usr/bin/elvish"]
