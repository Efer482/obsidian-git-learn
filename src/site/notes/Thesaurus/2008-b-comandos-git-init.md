---
{"dg-publish":true,"permalink":"/thesaurus/2008-b-comandos-git-init/"}
---

# git-init

`git init` no es el comando que más usaremos, pero sin duda, siempre será el primer comando que ejecutaremos en cada proyecto. Este comando establece las bases necesarias para que el proyecto pueda gestionarse a través de [[Thesaurus/2008-Git-GitHub\|Git]]. La mayoría de los otros comandos no están disponibles fuera de un repositorio inicializado, por lo que `git init` es esencial para comenzar a trabajar con Git.
## ¿Como funciona?

Cuando ejecutas `git init`, Git crea un subdirectorio oculto llamado `.git` en el directorio en el que ejecutaste el comando. Este subdirectorio contiene todos los archivos y directorios necesarios para el funcionamiento interno de Git. Es el corazón del repositorio de Git.

---
### Ejemplos y sintaxis

#### Uso basico

```bash
cd /ruta/a/tu/directorio
git init
```
{ #2e6f04}


Este comando creara un subdirectorio de `.git` al directorio actual y se crea la posibilidad de empezar a registrar las revisiones del proyecto.

### Git init en un directorio especifico

```bash
git init /ruta/a/tu/directorio
```
Creara el subdirectorio `.git`, pero no en el directorio actual si no en el directorio especificado.

---
# Bibliothecae
- [[bibliothecae/40014-git-init\|git init a fondo]]