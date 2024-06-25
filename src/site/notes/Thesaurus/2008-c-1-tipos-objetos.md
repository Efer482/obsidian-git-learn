---
{"dg-publish":true,"permalink":"/thesaurus/2008-c-1-tipos-objetos/"}
---

# Tipos de objetos
Git maneja distintos tipos de objetos:

1.  
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/thesaurus/2008-c-1-a-tree/#576af4" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



Un árbol es un objeto simple que tiene un montón de punteros a blobs y otros árboles - generalmente representa el contenido de un directorio o subdirectorio. 

</div></div>
 
2.  
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/thesaurus/2008-c-1-b-commit/#51a2dd" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



apunta a un único árbol, marcándolo como el aspecto que tenía el proyecto en un momento determinado. Contiene metainformación sobre ese momento, como una marca de tiempo, el autor de los cambios desde la última confirmación, un puntero a las confirmaciones anteriores, etc. 

</div></div>

3. 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/thesaurus/2008-c-1-c-blob/#99d1e0" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



Un objeto "blob" no es más que un trozo de datos binarios. No hace referencia a nada más ni tiene atributos de ningún tipo, ni siquiera un nombre de archivo. 

</div></div>

4. Una "etiqueta" es una forma de marcar una confirmación específica como especial de alguna manera. Normalmente se utiliza para etiquetar determinados commits como versiones específicas o algo por el estilo.
 