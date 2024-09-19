# módulo-00 	:lemon:

**Bootcamp JS 2 - Laboratorio Git** 	

Este repositorio contiene ejemplos y prácticas del Bootcamp de JavaScript 2, con un enfoque en el uso de Git y GitHub.

## Instrucciones

### :one: Inicializar el Repositorio

Inicializa un nuevo repositorio de npm:

><pre>git init

><pre>npm init -y

### :two: Subir el Repositorio a GitHub

Añade el repositorio remoto en GitHub:

><pre>git remote add origin git@github.com:IvanDeTena/modulo-00.git

### :three: Hacer Commit y Push

Añade todos los cambios al área de preparación:

><pre>git add .

Realiza el commit con un mensaje descriptivo:

><pre>git commit -m "Mensaje descriptivo del commit"

Sube los cambios al repositorio remoto:

><pre>git push

### :four: Crear y Trabajar en una Nueva Rama

Crea una nueva rama y cámbiate a ella:

><pre>git checkout -b nombre-rama-nueva

Realiza los cambios necesarios, luego añádelos y haz commit:

><pre>git add .
><pre>git commit -m "Mensaje descriptivo del commit en la nueva rama"

Sube la nueva rama al repositorio remoto:

><pre>git push --set-upstream origin nombre-rama-nueva

### :five: Fusionar la Rama Nueva con la Rama Principal

Vuelve a la rama principal (main):

><pre>git checkout main

Fusiona la rama nueva con la rama principal:

><pre>git merge nombre-rama-nueva

Sube los cambios fusionados al repositorio remoto:

><pre>git push
