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

- [https://education.github.com/git-cheat-sheet-education.pdf]

---

**Siguiente paso:** Empezar SAT-01 Atlas

🎯 EJERCICIO 3: Investigación guiada (15 min)

# 🔍 Parte 1: Explora estos comandos

* git log --oneline

# ¿Qué muestra? 

[muestra los cambios que se han realizado en el repositorio y que se han guardado mediante commits en orden inverso, empezando por el último cambio que se ha hecho en el repositorio.]

* git remote -v

# ¿Qué información da? 

[En esta caso muestra la ruta de los repositorios: 

origin  https://github.com/lucypelaez/bootcamp-apuntes.git (fetch)

origin  https://github.com/lucypelaez/bootcamp-apuntes.git (push)]

* git branch

# ¿En qué rama estás? 

[Este comando nos muestra en que rama del proyecto nos encontramos. Main en este caso sería la rama principal]


## 🔍 Parte 2: Preguntas de investigación

# ¿Qué hace el comando git pull?

El comando git pull se utiliza para buscar y descargar contenido de un repositorio remoto y actualizar inmediatamente el repositorio local para que coincida con ese contenido.

# ¿Para qué sirve el archivo .gitignore?

En git es posible ignorar archivos o carpetas que no queremos incluir en el sistema de control de versiones, ya sea porque tienen información sensible o son autogeneradas por alguna herramienta: logs, archivos temporales, etc.

El archivo donde se define la lista de archivos y carpetas a ignorar se llama .gitignore. Como este archivo inicia con punto (.), en la mayoría de sistemas operativos aparecerá como un archivo oculto.

Los archivos y carpetas definidos en .gitignore no van a aparecer como archivos nuevos o modificados al ejecutar git status.

Si aún no existe el archivo .gitignore podemos crearlo con nuestro editor de texto favorito e incluirlo en el siguiente commit.

# ¿Qué diferencia hay entre git add . y git add nombre-archivo?

- git add .: Añade archivos modificados y nuevos (untracked) al stage area, buscando recursivamente desde la carpeta actual. También maneja eliminaciones de archivos.
- git add + [nombre-archivo]: Selecciona selectivamente archivos específicos, lo que permite mayor control sobre lo que se incluirá en el siguiente commit.