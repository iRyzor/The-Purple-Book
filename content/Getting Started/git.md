---
title: "Git"
date: 2018-10-15T18:10:49-04:00
weight: 4
pre: "<b>2.4. </b>"
---

#### El poder del Git

Al terminar de clonar el repositorio usa el comando `cd Paradise`, luego `git status` para ver que todo está en orden.

![](/images/getting-started/20.png)
_Ignora esos tres archivos_

#### Branches

El tema de las branches o ramas es un poco complejo, si estás interesado en saber bien como funciona, clica en [Saber Más](https://git-scm.com/book/es/v1/Ramificaciones-en-Git-%C2%BFQu%C3%A9-es-una-rama%3F).

Debemos crear un branch para nuestro proyecto con el siguiente comando: `git checkout -b NOMBRE-DE-TU-BRANCH` ojo, el nombre de la branch no debe llevar espacios.

![](/images/getting-started/21.png)

Acabas de crear un branch y ahora mismo te encuentras en él. [master -> tu-branch]

Ahora trabaja en tu proyecto, crea lo que quieras, edita y guarda.

#### Add & Commit

Luego de hacer todos los cambios y comprobar que todo funciona en orden, toca hacer un push, para ello primero ejecuta el comando `git status` para comprobar el estado de tus archivos.

![](/images/getting-started/22.png)

Con el comando `git add DIR-DEL-ARCHIVO-MODIFICADO` añadimos archivos para crear un commit.
Ejemplo: `git add code/defines/procs/admin.dm` y `git add code/defines/procs/statistics.dm`

Luego de añadir los archivos modificados, haremos un commit con el siguiente comando:
`git commit -m "Aqui dale un nombre al commit, en pocas palabras los cambios que hiciste ej: Pequeños cambios en los procesos"`

![](/images/getting-started/23.png)

Ahora toca hacer un Push.

#### Push

##### ¿Qué es un Push?
Es un comando que sube los cambios hechos en tu ambiente de trabajo a una rama de trabajo tuya y/o de tu equipo remota.

Usa el siguiente comando: `git push origin [NOMBRE DE TU BRANCH]`

Y eso es todo.
Si has llegado hasta aquí, te felicito. de premio harás tu primer PULL REQUEST [PR].