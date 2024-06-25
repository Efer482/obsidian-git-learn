---
{"dg-publish":true,"permalink":"/thesaurus/2008-git-git-hub/","tags":["programacion","gardenEntry","gardenEntry","gardenEntry","gardenEntry"]}
---

# Git-GitHub

## ¿Por que usar un CVS?
Cuando usamos un sistema de control de versiones podemos tener control sobre los cambios en nuestros archivos, lo que nos permite:

- **Registro de cambios:** Todos los cambios realizados en los archivos se registran con un historial detallado. Esto incluye información sobre quién realizó el cambio, cuándo se hizo y una descripción del cambio. Esto facilita el seguimiento y auditoría del desarrollo del proyecto.
    
- **Revertir cambios:** Si se introduce un error o problema en el código, podemos revertir fácilmente los cambios a una versión anterior que funcionaba correctamente. Esto es crucial para mantener la estabilidad del proyecto y corregir errores rápidamente.
    
- **Trabajo en equipo:** Permite que varios desarrolladores trabajen en el mismo proyecto simultáneamente sin interferir entre sí. Cada desarrollador puede trabajar en su propia rama y luego fusionar los cambios con la rama principal cuando estén listos. Esto mejora la colaboración y productividad del equipo.
    
- **Experimentos seguros:** Podemos crear ramas para probar nuevas características o cambios sin afectar el código principal. Si el experimento no funciona como se esperaba, simplemente se puede descartar la rama sin impactar el resto del proyecto.
    
- **Copias de seguridad automáticas:** Cada cambio se guarda en el repositorio, lo que actúa como una copia de seguridad. Si se pierde algún archivo localmente, siempre se puede recuperar la versión más reciente desde el repositorio.
    
- **Documentación y trazabilidad:** Los mensajes de commit y las etiquetas proporcionan documentación útil sobre el desarrollo del proyecto. Esto ayuda a entender el propósito de los cambios y facilita la trazabilidad de las decisiones técnicas.
    
- **Integración continua y despliegue:** Muchos sistemas de control de versiones se integran con herramientas de integración continua y despliegue, lo que permite automatizar pruebas y despliegues cada vez que se realiza un cambio en el código, mejorando la eficiencia y calidad del desarrollo.
    
- **Resolución de conflictos:** Los sistemas de control de versiones ayudan a detectar y resolver conflictos cuando varios desarrolladores modifican las mismas partes del código. Esto garantiza que los cambios se integren de manera coherente.

## ¿Cual es la diferencia entre Git y GitHub?
**Git** es la herramienta que usas en tu computadora para manejar el código, y **GitHub** es el sitio web donde puedes guardar y compartir ese código y versiones con otros.

Sin embargo, el uso general de Git es asociado a GitHub, por lo tanto asumiremos que son lo mismo en la mayoría de casos.

## ¿Como empezar a usar Git?
Git permite tener distintas formas de trabajar, sin embargo, lo esencial es el manejo simple de versiones

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/thesaurus/2008-a-flujo-trabajo-basico/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

<div class="markdown-embed-title">

# flujo-trabajo-basico

</div>



# flujo-trabajo-basico

Git tiene herramientas muy potentes y avanzadas, sin embargo en esta sección solo hablaremos del flujo de trabajo simple de git, que no permitirá empezar a usar un CVS.

## Comandos basicos de Git
Antes de iniciar tenemos que entender que son los comandos básicos de [[Thesaurus/2008-Git-GitHub\|GitHub]], ya que estos son el pilar de todos los demás procesos, además, los enumeraremos en el orden en el que los ejecutaremos las primeras veces que creemos un proyecto.

1.  
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/thesaurus/2008-b-comandos-git-init/#2e6f04" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



```bash
cd /ruta/a/tu/directorio
git init
```

</div></div>

2. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/thesaurus/2008-b-comandos-git-status/#cambios-pendientes" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>

3. [[Thesaurus/2008-b-comandos-git-add\|2008-b-comandos-git-add]]


---
### Ejemplos


---
# Bibliothecae
- 

</div></div>


---
# Bibliothecae
- [[bibliothecae/40013-Git-vs-GitHub\|Git-vs-GitHub]]