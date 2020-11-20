# Git Aliases

### Changing default editor

```bash
git config --global core.editor code
```
Define VSCode as default editor.


## Editing Global Settings

```bash
git config --global --edit
```

## Aliases

```bash
[alias]
	s = !git status -s
	a = !git add
	c = !git commit -m
	l = !git log --pretty=format:'%C(yellow)%h %C(red)%d %C(bold)%C(white)%s -> %C(reset)%C(white)%cn, %cr'
	ac = !git add --all && git commit -m
	co = !git checkout
	cb = !git checkout -b
	cm = !git checkout master
	cmain = !git checkout main
```
