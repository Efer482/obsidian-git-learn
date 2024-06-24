---
{"dg-publish":true,"permalink":"/thesaurus/git/c-1-c-blob/"}
---

# git-object-blob

Un objeto "blob" no es más que un trozo de datos binarios. No hace referencia a nada más ni tiene atributos de ningún tipo, ni siquiera un nombre de archivo.
{ #99d1e0}


![[c-1-c-blob.excalidraw\|c-1-c-blob.excalidraw]]

Dado que el blob está totalmente definido por sus datos, si dos archivos en un árbol de directorios (o en varias versiones diferentes del repositorio) tienen el mismo contenido, compartirán el mismo objeto blob. El objeto es totalmente independiente de su ubicación en el árbol de directorios, y renombrar un archivo no cambia el objeto al que está asociado ese archivo.

