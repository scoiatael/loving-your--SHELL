FROM debian
RUN \
  apt update > /dev/null \
  && apt install -qy git zsh \
  && git clone --depth=1 --recursive https://github.com/sorin-ionescu/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"

SHELL ["/bin/zsh", "-c"]

RUN \
  setopt EXTENDED_GLOB; \
  for rcfile in "${ZDOTDIR:-$HOME}"/.zprezto/runcoms/^README.md(.N); do \
    ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"; \
  done

WORKDIR /code
ENTRYPOINT ["/bin/zsh"]
