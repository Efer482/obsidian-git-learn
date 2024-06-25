---
{"dg-publish":true,"permalink":"/thesaurus/2008-b-comandos-git-commit/"}
---

# git-commit
Cada que ejecutamos este comando asignamos una nueva versión del archivo, para poder rastrear sus cambios con el CVS, pero no se suben a nuestra rama remota hasta ejecutar [[Thesaurus/2008-b-comandos-git-push\|git push]].

---
## ¿Como funciona?
El comando commit tiene tres pasos. 
- Crea un gráfico de árbol para representar el contenido de la versión del proyecto que se está confirmando.
- Crea un objeto commit.
- Apunta la rama actual al nuevo objeto de confirmación.

---
### Ejemplos y sintaxis

---
# Bibliothecae
-  
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/bibliothecae/40017-git-from-the-inside-out/#make-a-commit" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



- [Make a commit](https://codewords.recurse.com/issues/two/git-from-the-inside-out#make-a-commit)

</div></div>
