# anyenv - all in one for \*\*env [![Build Status](https://travis-ci.org/ndxbn/anyenv.svg?branch=master)](https://travis-ci.org/ndxbn/anyenv)

This is a simple wrapper for [rbenv](https://github.com/sstephenson/rbenv) style environment managers.
You don't have to git clone or modify your shell profile for each \*\*env anymore if you install anyenv.

## Install

### bash

```bash
git clone https://github.com/ndxbn/anyenv ~/.anyenv
echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(anyenv init -)"' >> ~/.bash_profile
exec $SHELL -l
```

### zsh

```zsh
git clone https://github.com/ndxbn/anyenv ~/.anyenv
echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(anyenv init -)"' >> ~/.zshrc
exec $SHELL -l
```

### ksh

```ksh
git clone https://github.com/ndxbn/anyenv ~/.anyenv
echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.profile
echo 'eval "$(anyenv init -)"' >> ~/.profile
exec $SHELL -l
```

### fish

```fish
git clone https://github.com/ndxbn/anyenv ~/.anyenv
echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.config/fish/config.fish
echo 'eval "$(anyenv init -)"' >> ~/.config/fish/config.fish
exec $SHELL -l
```


## Usage

### Install **env

```bash
anyenv install rbenv
anyenv install phpenv
anyenv install ndenv
exec $SHELL -l
```

## Available \*\*env
see [share/anyenv-install directory](./share/anyenv-install).
You can install them.

## Plugins

- [znz/anyenv-update](https://github.com/znz/anyenv-update)
- [znz/anyenv-git](https://github.com/znz/anyenv-git)
