---
{"dg-publish":true,"permalink":"/thesaurus/git/c-git-objects/"}
---

# git-objects
Git almacena los objetos por medio de [[d-git-hash\|hash]], al estos ser únicos nos da ciertas ventajas:

- Git puede determinar rápidamente si dos objetos son idénticos o no, simplemente comparando los nombres.
- [[c-git-objects#Deteccion de Errores al Leer un Objeto\|Manejo de errores y seguridad]].

Todos los objetos consisten de tres cosas
- [[c-1-tipos-objetos\|tipo de objeto]]
- Tamaño: El tamaño del contenido.
- contenido.
 Estos archivos se almacenan en `.git/objects` dentro de un subdirectorio de la base de datos de objetos ver el ejemplo [[d-git-hash#^ruta-hash\|ruta hash]].

![[c-2-git-objects-seguridad#Deteccion de Errores al Leer un Objeto\|c-2-git-objects-seguridad#Deteccion de Errores al Leer un Objeto]]


## Ejemplos

### Estructura simple
Imaginemos que tenemos la siguiente estructura:
```
$>tree
.
|-- README
`-- lib
    |-- inc
    |   `-- tricks.rb
    `-- mylib.rb

2 directories, 3 files
```
En ese caso nuestra estructura de git se vería de la siguiente forma:
![[c-git-objects-estructura-simple.excalidraw\|c-git-objects-estructura-simple.excalidraw]]

---
# Bibliothecae
- 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/bibliothecae/git/40016-git-object-model/#url" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



### URL
[git object model](https://shafiul.github.io//gitbook/1_the_git_object_model.html)

</div></div>
