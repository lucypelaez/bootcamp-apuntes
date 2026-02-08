# 📅 Día 1 - [06/02/2026]

## 🎯 Lo que hemos visto hoy

### Mañana
- Dinámica: Gartic Phone (sobre distorsión de información)
- Conceptos: ¿Qué es análisis de datos?
- Ejercicio: Palabras en griego (buscar patrones sin contexto)

### Tarde
- Git y GitHub: instalación y configuración
- Primeros comandos: clone, status, add, commit, push

## 💡 Lo que he aprendido

[Durante esta clase he aprendido con el ejercicio de las palabras en griego que con podemos encontrar patrones comunes en un conjunto de datos y agruparlos según un razonamiento lógico.
De la Git y GitHub he aprendido, que Git es una teconología/lenguaje con comandos propios, que nos permite comunicarnos con el repositorio,  GitHub es la plataforma que está en remoto  en la cual podemos compartir nuestros repositorios y trabajar conjuntamente con otras personas.
Además también he empezado a familiarizarme con los comandos básicos de Git, a crear y clonar un repositorio, a crear una carpeta dentro del mismo y a crear archivos dentro de las carpetas.]

## ❓ Dudas que tengo
[No entiendo muy bien las diferencias entre algunos de los comandos, y tampoco entiendo como se puede trabajar sobre el código en GitHub ]

## 🔗 Recursos útiles

- [https://education.github.com/git-cheat-sheet-education.pdf

https://makeitrealcamp.gitbook.io/guias-de-make-it-real/git/conceptos-comandos-esenciales]


## 🔍 Comandos investigados

### git log --oneline

[Este comando muestra el historial de commits en orden descendente, es decir, primero aparecen los más recientes. se añade la opción --oneline para ver una versión resumida que muestra los primeros 7 caracteres del identificador y el mensaje de cada commit ]

### git remote -v

[Para ver los repositorio remotos que tienes configurados, debes ejecutar el comando git remote. Mostrará los nombres de cada uno de los remotos que tienes especificados. Si has clonado tu repositorio, deberías ver al menos origin (origen, en inglés) - este es el nombre que por defecto Git le da al servidor del que has clonado. La opción -v, muestra las URLs que Git ha asociado al nombre y que serán usadas al leer y escribir en ese remoto]

Ej. [En esta caso muestra la ruta de los repositorios: 

origin  https://github.com/lucypelaez/bootcamp-apuntes.git (fetch)

origin  https://github.com/lucypelaez/bootcamp-apuntes.git (push)]]

### git branch

[Nos muestra un listado de las ramas de nuestro proyecto. La rama con el asterisco a la izquierda es en la que nos encontramos actualmente.]

### git pull

[El comando git pull se utiliza para buscar y descargar contenido de un repositorio remoto y actualizar inmediatamente el repositorio local para que coincida con ese contenido.]

### .gitignore

[En git es posible ignorar archivos o carpetas que no queremos incluir en el sistema de control de versiones, ya sea porque tienen información sensible o son autogeneradas por alguna herramienta: logs, archivos temporales, etc.

El archivo donde se define la lista de archivos y carpetas a ignorar se llama .gitignore. Como este archivo inicia con punto (.), en la mayoría de sistemas operativos aparecerá como un archivo oculto.

Los archivos y carpetas definidos en .gitignore no van a aparecer como archivos nuevos o modificados al ejecutar git status.

Si aún no existe el archivo .gitignore podemos crearlo con nuestro editor de texto favorito e incluirlo en el siguiente commit.]

### git add . vs git add archivo


[
- git add .: Añade archivos modificados y nuevos (untracked) al stage area, buscando recursivamente desde la carpeta actual. También maneja eliminaciones de archivos.
- git add + [nombre-archivo]: Selecciona selectivamente archivos específicos, lo que permite mayor control sobre lo que se incluirá en el siguiente commit.]