---
{"dg-publish":true,"permalink":"/thesaurus/2008-c-2-git-objects-seguridad/"}
---

# Deteccion de Errores al Leer un Objeto
Git emplea un mecanismo de integridad que le permite detectar errores o alteraciones en los datos:

- **Almacenar el Objeto:**
    
    - Cuando se crea un nuevo objeto en Git (como un nuevo [[Thesaurus/2008-b-comandos-git-commit\|commit]] o un archivo), Git calcula el [[Thesaurus/2008-d-git-hash\|hash]] del contenido del objeto.
- **Leer el Objeto:**
    
    - Cuando Git necesita leer un objeto del repositorio (por ejemplo, para mostrar el contenido de un archivo o para reconstruir el historial de commits), busca el objeto usando su hash SHA1.
    - Una vez encontrado el objeto, Git puede volver a calcular el hash SHA1 de su contenido actual.
- **Verificación de Integridad:**
    
    - Git compara el hash SHA1 recalculado con el nombre original del objeto (el hash con el que se almacenó).
    - Si los dos hashes coinciden, significa que el contenido del objeto no ha cambiado y no se ha producido ningún error.
    - Si los hashes no coinciden, esto indica que el contenido del objeto ha sido alterado de alguna manera (por ejemplo, por corrupción de datos o un ataque malicioso), y Git puede entonces reportar un error.