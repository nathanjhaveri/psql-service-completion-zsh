zsh psql service completion script
==================================


# About

https://github.com/nathanjhaveri/psql-service-completion-zsh

This script provides zsh tab completion for services listed in ~/.pg_service.conf.  A [bash version](https://github.com/nathanjhaveri/psql-service-completion) is also available.

# Installation

1. Clone repo, or copy the file [_psql_service](./_psql_service) to a directory.
2. Add directory containing the completion script to fpath in .zshrc like:

```.zshrc
# Ensure zsh can find completion script
fpath=(/User/$USER/code/psql-service-completion-zsh $fpath)

# Load completions
autoload -Uz compinit && compinit -D
```
