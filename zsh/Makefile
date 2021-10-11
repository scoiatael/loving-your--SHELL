NAME = zsh

.PHONY: run build

run: build
	lima docker run -v $(abspath ../):/code --rm -it --hostname loving-${NAME} loving-${NAME}

build: Dockerfile
	lima docker build -t loving-${NAME} .
