# .gitignore_global

My global .gitignore

## Install

Cloned this repo into your home directory:

    git clone https://github.com/GitBruno/.gitignore_global.git ~/.gitignore_global

Add to the global ignore to your global config file:

    git config --global core.excludesfile ~/.gitignore_global/ignore

So your config file looks like this:

```
[core]
	excludesfile = ~/.gitignore_global/ignore
```
