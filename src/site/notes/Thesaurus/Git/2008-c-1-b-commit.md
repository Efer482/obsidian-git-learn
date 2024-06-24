---
{"dg-publish":true,"permalink":"/thesaurus/git/c-1-b-commit/"}
---

# git object commit
apunta a un único árbol, marcándolo como el aspecto que tenía el proyecto en un momento determinado. Contiene metainformación sobre ese momento, como una marca de tiempo, el autor de los cambios desde la última confirmación, un puntero a las confirmaciones anteriores, etc.
{ #51a2dd}


![[c-1-b-commit.excalidraw\|300]]

## ¿Que contiene un commit?
1. un árbol: El nombre SHA1 de un objeto árbol (como se define a continuación), que representa el contenido de un directorio en un momento determinado.
{ #tree}

2. padre(s): El nombre SHA1 de un cierto número de confirmaciones que representan el paso o pasos inmediatamente anteriores en la historia del proyecto. El ejemplo anterior tiene un padre; las confirmaciones de fusión pueden tener más de uno. Un commit sin padres se denomina commit "raíz", y representa la revisión inicial de un proyecto. Cada proyecto debe tener al menos una raíz. Un proyecto también puede tener múltiples raíces, aunque esto no es común (o necesariamente una buena idea).
{ #parents}

3. un autor: El nombre de la persona responsable de este cambio, junto con su fecha.
{ #author}

4. un committer: El nombre de la persona que realmente creó el commit, con la fecha en que se hizo. Puede ser diferente del autor; por ejemplo, si el autor escribió un parche y lo envió por correo electrónico a otra persona que utilizó el parche para crear la confirmación.
{ #committer}

5. un commit que describa esta confirmación.
{ #commit}


Ten en cuenta que una confirmación no contiene en sí misma ninguna información sobre lo que ha cambiado realmente; todos los cambios se calculan comparando el contenido del árbol al que hace referencia esta confirmación con los árboles asociados a sus padres. En particular, git no intenta registrar explícitamente los renombramientos de archivos, aunque puede identificar casos en los que la existencia de los mismos datos de archivo en rutas cambiantes sugiere un renombramiento. 

---
# Bibliothecae
- 