---
{"dg-publish":true,"dg-path":"2008-b-comandos-git-status.md","permalink":"/2008-b-comandos-git-status/"}
---

# git-status
Git estatus es un comando simple, nos muestra que archivos modificados hemos añadido a un [[Thesaurus/2008-b-comandos-git-commit\|commit]], y cuales están pendientes de subir.

---
## ¿Como funciona?

---
### Ejemplos y sintaxis

#### Cambios pendientes:
```bash
$ git status

On branch main

No commits yet

Changes to be commited:
	(use "git rm --cached <file>..." to unstage)
		new file: file2.txt
		new file: script.js
Changes not staged for commit:
	(use "git add <file>..." to update what will be committed)
	(use "git store <file>.." to discard changes in working directory)
		modified: file3.txt
```

#### Sin cambios
```bash
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```
---
# Bibliothecae
- [[bibliothecae/40015-inspecting-a-repository\|inspecting a respository]]