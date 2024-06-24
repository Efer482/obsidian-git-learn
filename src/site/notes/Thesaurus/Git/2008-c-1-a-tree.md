---
{"dg-publish":true,"permalink":"/thesaurus/git/c-1-a-tree/"}
---

# git object arbol
Un árbol es un objeto simple que tiene un montón de punteros a blobs y otros árboles - generalmente representa el contenido de un directorio o subdirectorio.
{ #576af4}


![[c-1-a-arbol.excalidraw\|300]]

El siempre comando [git show](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-show.html) puede usarse para examinar objetos árbol, pero [git ls-tree](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-ls-tree.html) te dará más detalles.

## ¿Que objetos puede tener un arbol?

Un objeto referenciado por un árbol puede ser un blob, que representa el contenido de un archivo, u otro árbol, que representa el contenido de un subdirectorio. Como los árboles y los blobs, al igual que el resto de objetos, se nombran por el hash SHA1 de sus contenidos, dos árboles tienen el mismo nombre SHA1 si y sólo si sus contenidos (incluyendo, recursivamente, los contenidos de todos los subdirectorios) son idénticos. Esto permite a git determinar rápidamente las diferencias entre dos objetos árbol relacionados, ya que puede ignorar cualquier entrada con nombres de objeto idénticos.

(Nota: en presencia de submódulos, los árboles también pueden tener commits como entradas.).

---
# Bibliothecae
- 