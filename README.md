# Loving your $SHELL

## Bash

Default for most Linux distros (and WSL).

Pimp it with [bash-it](https://github.com/Bash-it/bash-it.git).

## Zsh

Default for macOS. Has more features than Bash. Is mostly Bash compatibly - so things copy-pasted from the Internet (don't do that!) will stil work.

Use [prezto](https://github.com/sorin-ionescu/prezto.git) as a starting point for configuration.

## [Fish](https://fishshell.com/)

>  a command line shell for the 90s 

Very productive defaults with autocompletion that rivals IDEs. Having better scripting language was prioritized over Bash compatibility at the beginning, but lately has been reversed a little. MEANING STUFF YOU COPY PASTE WON'T WORK. But most CLI tools offer Fish-compatible versions nowadays.

## [Elvish](https://elv.sh/)

>  an expressive programming language and a versatile interactive shell, combined into one seamless package

For the brave. Functional programming language that (might) rival Powershell for scripting purposes. But no Bash compatibility at all, plus few tools support it natively. On the bright side, you can easily manipulate JSON in Elvish (unlike previous shells), so making your own integration is easy.
