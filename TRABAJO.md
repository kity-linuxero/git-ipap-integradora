# Trabajo integrador | IPAP Git
Repositorio para actividad final capacitación IPAP en el curso **Git y herramientas para implementar el control de
versiones en aplicaciones para desarrolladores/as**

## Integrantes del grupo

Este es un trabajo realizado en grupo por los siguientes integrantes

- [Ezequiel Alvarez](https://github.com/ezefinrod)
- [Cristian Giambruni](https://github.com/kity-linuxero)
- [Carolina Le Mura](https://github.com/Carolemura1989)


## Pasos realizados

### 1. Se creó el repositorio en Github.

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

### 6. Se copian los archivos de poncho

Se clona el repositorio de Poncho y se copian los archivos al repositorio, luego se agregan para el commit en el branch `proyecto`.

```bash
git add poncho

git commit -m "Se agrega Poncho al proyecto"
```




# Proyecto usado del estado nacional Poncho

 https://github.com/argob/poncho.git

 git clone  https://github.com/argob/poncho.git

 mv poncho git-ipap-integradora