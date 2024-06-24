---
{"dg-publish":true,"permalink":"/thesaurus/git/2008-d-git-hash/"}
---

# git-hash

Toda la información necesaria para representar el historial de un proyecto se almacena en archivos a los que se hace referencia mediante un "nombre de objeto" (Este nombre de objeto es un [[hash-SHA1\|hash-SHA1]])  de esta forma es extremadamente improbable que dos conjuntos de datos diferentes produzcan el mismo hash (esto se conoce como una [[hash-SHA1#colision\|colisión]])

Estos  hash se almacenan en `.git/objects/<sub-directory>`

---
### Ejemplos

#### Ruta hash{ #ruta-hash}


Si tenemos un hash: `2e65efe2a145dda7ee51d1741299f848e5bf752e`
Los dos primeros caracteres son la subcarpeta en la que se almacenara el hash: `2e/`
Los demás caracteres son el nombre del [[Thesaurus/Git/2008-c-git-objects\|objeto]]: `65efe2a145dda7ee51d1741299f848e5bf752e`
```bash
#Así queda al final:
.git/objects/2e/65efe2a145dda7ee51d1741299f848e5bf752e
```

---
# Bibliothecae
- 