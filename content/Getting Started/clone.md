---
title: "Clonar un repositorio"
date: 2018-10-15T17:38:50-04:00
weight: 3
pre: "<b>2.3. </b>"
---

#### ¿Clonar un repositorio?
Significa descargarse una copia completa del mismo a nuestra computadora.

#### ¿Qué debo hacer?
Nota: _Los siguientes pasos puedes realizarlos como de costumbre, sin utilizar la consola, el propósito de que lo enseñe así es para que se vayan acostumbrando a moverse por ella._

1. Abrimos nuestra consola de comandos preferida.
![](/images/getting-started/11.png)

2. Creamos una carpeta nueva con el comando `mkdir {NOMBRE DE LA CARPETA}`
![](/images/getting-started/12.png)

3. `ls` o `dir` muestra todas las carpetas de la ruta donde te encuentras.
![](/images/getting-started/13.png)

4. Con `cd {NOMBRE DE LA CARPETA}` entras a la carpeta.
![](/images/getting-started/14.png)
_Recuerden ser ordenados y nombrar todo como se debe_

Ya dentro de una carpeta limpia, procedemos a poner los siguientes comandos:

- `git config --global user.name "tu nombre"`
- `git config --global user.email "tu@email.com"`

modifica los valores que están dentro de las comillas

#### ¿Cómo clono el repositorio?

Luego de hacer el Fork, vas al apartado para ver tus repositorios

![](/images/getting-started/15.png)

Aparecerá un repositorio llamado _Paradise_, entramos.

![](/images/getting-started/16.png)

Clicamos en Clone or Download y copiamos la url que nos dan.

![](/images/getting-started/17.png)

Volvemos a la consola y ponemos `git clone URL`

![](/images/getting-started/18.png)

Y solo toca esperar a que se descarguen los archivos.

![](/images/getting-started/19.png)