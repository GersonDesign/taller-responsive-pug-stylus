
# Base maquetación para usar Pug y Stylus
--------------------------------------------------------
# Descripción
Este repositorio es creado para que tengas una base cuando vayas iniciar un proyecto usando los pre-procesadores para HTML, CSS llamados PUG y Stylus, a parte podrás crear varios archivos .js, el proyecto se va encargar unirlo en un solo, así solo tendrás un archivo .js en todo el proyecto, también de optimizar las imágenes que vayas colocando en la carpeta img y por el último tienes la opción de generar tu favicon.

Dentro de la carpeta assets en donde debes trabajar, ya que una vez levantando
el servidor se van a generar los archivos en la carpeta public.


# Programas a Instalar

* Atom(Opcional)
* Hyper.is(Opcional)
* Nodejs(Obligatorio)

# Primer paso de configuración
- Clonar el proyecto en el lugar que desees de tu computador
- Abrir un terminal para instalar GulpJS:
* npm install -g gulp(En Windows)
* npm install gulp(En Linux)

# Segundo paso de configuración
Ubícate en la carpeta que haz clonado el proyecto, abres un terminal y lo haz lo siguiente:

## Instalar dependencias
npm install

## Abrir atom (Opcional)
atom .

## Desplegar entorno de Desarrollo
gulp serverAptitud

--------------------------------------------------------

## Las herramientas a usar son las siguientes:

Servidor local:
+ browser-sync

Sistema de control versiones
+ Git

Preprocesadores:
+ PUG(HTML)
+ Stylus(CSS)

Paquetes:
+ browser-sync
+ gulp-concat
+ gulp-imagemin
+ gulp-pug
+ gulp-to-ico
+ gulp-stylus
+ gulp-uglify
+ nib
