# Git y herramientas para implementar el control de versiones en aplicaciones para desarrolladores/as

# ACTIVIDAD INTEGRADORA

## Integrantes del grupo

Este es un trabajo realizado en grupo por los siguientes integrantes

- [Ezequiel Alvarez](https://github.com/ezefinrod)
- [Cristian Giambruni](https://github.com/kity-linuxero)
- [Carolina Le Mura](https://github.com/Carolemura1989)

## Elección de tecnología:

Describir al menos dos de los servicios a libre elección que aparecen como templates en la creación de proyectos en Gitlab. 

Para este trabajo seleccionamos dos plantillas (templates) disponibles al iniciar proyectos en plataformas de control de versiones como GitLab o similares. Ambas resultan útiles para desarrollar aplicaciones web:

- HTML5 Boilerplate Proporciona una estructura básica en HTML5, ideal para comenzar sitios web simples. Incluye buenas prácticas de desarrollo y compatibilidad entre navegadores.

- Node.js Express App Plantilla pensada para iniciar una aplicación backend con Node.js y Express. Es ideal para desarrollar APIs, servidores y lógicas del lado del servidor.


## Adaptación:

Buscar y clonar un proyecto libre del Estado Argentino (fuera del repositorio) y copiar sus archivos dentro de nuestro repositorio en una carpeta con el nombre del proyecto clonado. Esto hacerlo en una rama distinta a la rama principal llamada proyectos. 

## Pasos realizados

### 1. Se creó el repositorio en Github.
Se agregaron los _contribuitors_ mediante invitaciones.

### 2. Se clonó el repositorio localmente

```bash
git clone https://github.com/kity-linuxero/git-ipap-integradora.git
```

### 3. Se agregaron archivos al repositorio.

Para este TP se desarrolló un `index.html` usando el framework [Poncho](https://github.com/argob/poncho) para cumplir con la consigna de integrarlo con un proyecto de gestión nacional.

### 4. Primer commit local

Se agregaron los archivos necesarios para levantar el sitio para un commit.

```bash
git add . # Se agregan al stage area

git commit -m "Agregado archivos básicos"
```

### 5. Se crea branch para el proyecto

```bash
git branch proyecto
```

### 6. Proyecto usado del estado nacional Poncho

 https://github.com/argob/poncho.git

```bash
 git clone  https://github.com/argob/poncho.git

 mv poncho git-ipap-integradora
```

### 7. Se copian los archivos de poncho

Se clona el repositorio de Poncho y se copian los archivos al repositorio, luego se agregan para el commit en el branch `proyecto`.

```bash
git add poncho

git commit -m "Se agrega Poncho al proyecto"
```

## Anotación:

Escribir un README.md en el directorio raíz de nuestro repositorio explicando de 
qué se trata el curso. Esto debe hacerse en la rama principal. 

- Agregar un apartado al README.md donde explique de qué se trata el repositorio clonado del Estado Argentino. Esto debe hacerse en la rama proyectos. 
- Agregar un apartado al README.md con links y descripciones de al menos 2 herramientas web para aprender ramas en Git. En la rama principal.

### 1. Se edita el archivo README.md para la rama main y el archivo TRABAJO.md

Se edita el archivo README.md para la rama Main, con una explicación de qué se trata el curso, Se agrega un apartado al README.md con links y descripciones de las herramientas "Learn Git Branching" y "Oh My Git!".
Tambien se agrega el archivo TRABAJO.md donde ir cargando el paso a paso de lo que vamos haciendo.
Se realiza el commit correspondiente y el push origin

```bash
git add README.md
git add TRABAJO.md

git commit -m "Renombro el README.md a TRABAJO.md y agrego un nuevo README.md con el contenido que solicita la consigna para la rama main"

git push origin main
```

### 2. Se edita el archivo README.md para la rama proyectos

En la rama proyectos, se edita el archivo README.md solo con un apartado sobre poncho, el repositorio clonado. Se realiza el commit y se carga el archivo en dicha rama

```bash
git checkout proyectos

git add README.md

git commit -m "agrego el README.md con info sobre Poncho, para la rama proyectos"

git push origin proyectos
```