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
[ ]

## 🔗 Recursos útiles

- [https://education.github.com/git-cheat-sheet-education.pdf]

---

**Siguiente paso:** Empezar SAT-01 Atlas

🎯 EJERCICIO 3: Investigación guiada (15 min)
Ahora que ya sabes clonar, crear repos y hacer commits, vamos a investigar algunos comandos nuevos.

🔍 Parte 1: Explora estos comandos
Ejecuta cada comando en tu repositorio bootcamp-apuntes y anota qué hace en tu archivo dia-01.md:

git log --oneline
¿Qué muestra? [muestra los cambios que se han realizado en el repositorio:

jmpin@DESKTOP-V54NCRM MINGW64 ~/Desktop/bootcamp-apuntes (main)
$ git log --oneline
3958768 (HEAD -> main, origin/main, origin/HEAD) feat: modificacion texto dia-01
666fd33 feat: añadir apuntes del dia 1
76ba329 Initial commit]

git remote -v
¿Qué información da? [En esta caso muestra la ruta de origen de donde hace la búsqueda de archivos y la ruta de origen desde la que hace la subida de esos archivos:
jmpin@DESKTOP-V54NCRM MINGW64 ~/Desktop/bootcamp-apuntes (main)
$ git remote -v
origin  https://github.com/lucypelaez/bootcamp-apuntes.git (fetch)
origin  https://github.com/lucypelaez/bootcamp-apuntes.git (push)
]

git branch
¿En qué rama estás? [en la rama principal:
jmpin@DESKTOP-V54NCRM MINGW64 ~/Desktop/bootcamp-apuntes (main)
$ git branch
* main
]