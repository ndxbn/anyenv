# anyenv - all in one for \*\*env [![Build Status](https://travis-ci.org/ndxbn/anyenv.svg?branch=master)](https://travis-ci.org/ndxbn/anyenv)

This is a simple wrapper for [rbenv](https://github.com/sstephenson/rbenv) style environment managers.
You don't have to git clone or modify your shell profile for each \*\*env anymore if you install anyenv.

## Install

### bash

```bash
git clone https://github.com/ndxbn/anyenv ~/.anyenv
echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(anyenv init - bash)"' >> ~/.bash_profile
exec bash -l
```

### zsh

```zsh
git clone https://github.com/ndxbn/anyenv ~/.anyenv
echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(anyenv init - zsh)"' >> ~/.zshrc
exec zsh -l
```

## Usage

### Install **env

```bash
anyenv install rbenv
anyenv install phpenv
anyenv install ndenv
```

and restart current shell ( e.g. `exec bash -l` , `exec zsh -l` )

## Available \*\*env
see [share/anyenv-install directory](./share/anyenv-install).
You can install them.

## Plugins

- [znz/anyenv-update](https://github.com/znz/anyenv-update)
- [znz/anyenv-git](https://github.com/znz/anyenv-git)
