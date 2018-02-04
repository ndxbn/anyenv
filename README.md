# anyenv - all in one for \*\*env

This is a simple wrapper for [rbenv](https://github.com/sstephenson/rbenv) style environment managers. You don't have to git clone or modify your shell profile for each \*\*env anymore if you install anyenv.

## INSTALL

```ShellSession
$ git clone https://github.com/ndxbn/anyenv ~/.anyenv
$ echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.your_profile
$ echo 'eval "$(anyenv init -)"' >> ~/.your_profile
$ exec $SHELL -l
```

## USAGE    

```ShellSession
$ anyenv install rbenv
$ anyenv install plenv
$ anyenv install pyenv
$ anyenv install phpenv
$ anyenv install ndenv
$ anyenv install denv
$ anyenv install jenv
$ anyenv install luaenv
$ anyenv install goenv
$ exec $SHELL -l
$ anyenv version
denv: 2.063 (set by /home/ndxbn/.anyenv/envs/denv/version)
jenv: system (set by /home/ndxbn/.anyenv/envs/jenv/version)
luaenv: system (set by /home/ndxbn/.anyenv/envs/luaenv/version)
ndenv: v0.10.12 (set by /home/ndxbn/.anyenv/envs/ndenv/version)
phpenv: system (set by /home/ndxbn/.anyenv/envs/phpenv/version)
plenv: 5.18.0 (set by /home/ndxbn/.anyenv/envs/plenv/version)
pyenv: venv27 (set by /home/ndxbn/.anyenv/envs/pyenv/version)
rbenv: 1.9.3-p327 (set by /home/ndxbn/.anyenv/envs/rbenv/version)
goenv: 1.2.2
```
## PLUGINS

- [znz/anyenv-update](https://github.com/znz/anyenv-update)
- [znz/anyenv-git](https://github.com/znz/anyenv-git)
