FROM debian
RUN \
  apt update > /dev/null \
  && apt install -qy fish

WORKDIR /code
ENTRYPOINT ["/usr/bin/fish"]
