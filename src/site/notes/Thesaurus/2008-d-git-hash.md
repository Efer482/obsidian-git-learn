---
{"dg-publish":true,"permalink":"/thesaurus/2008-d-git-hash/"}
---

# git-hash

#anki/start
```anki-config
id: 
deck: Programación::Clasica::Git
```
## ¿Que es un HASH en git?
#anki/---
Toda la información necesaria para representar el historial de un proyecto se almacena en archivos a los que se hace referencia mediante un "nombre de objeto" (Este nombre de objeto es un [[hash-SHA1\|hash-SHA1]]) 
#anki/end

#anki/start

```anki-config
id: 
deck: Programación::Clasica::Git
```
### ¿Donde se almacenan mis HASH de git?
#anki/---
Los  hash se almacenan en `.git/objects/<sub-directory>`
#anki/end

```anki-config
id: 
deck: Programación::Clasica::Git
```
### ¿Por que es improbable que dos archivos se confundan?
#anki/---
Git crea un [[hash-SHA1\|hash-SHA1]] usando como valor el contenido del archivo o el arbol, de esta forma es extremadamente improbable que dos conjuntos de datos diferentes produzcan el mismo hash (esto se conoce como una [[hash-SHA1#colision\|colisión]])
#anki/end

---
### Ejemplos

#### Ruta hash{ #ruta-hash}


Si tenemos un hash: `2e65efe2a145dda7ee51d1741299f848e5bf752e`
Los dos primeros caracteres son la subcarpeta en la que se almacenara el hash: `2e/`
Los demás caracteres son el nombre del [[Thesaurus/2008-c-git-objects\|objeto]]: `65efe2a145dda7ee51d1741299f848e5bf752e`
```bash
#Así queda al final:
.git/objects/2e/65efe2a145dda7ee51d1741299f848e5bf752e
```

---
# Bibliothecae
- 