## Manual de referencia para el proyecto de robótica educativa ICARO

#Instalación
Antes que nada vamos a instalar el software necesario para que puedas compilar y generar la documentación!

### UBUNTU

### Instalamos librerías

    sudo apt-get install texlive-fonts-recommended texlive-latex-extra

### Instalamos Sphinx

    sudo apt-get install python-sphinx

### FEDORA
Para instalarlo en Fedora GNU/Linux

### Instalamos Sphinx y los modulos de Texlive para poder compilar en PDF 

    sudo dnf -y install python-sphinx git texlive

### Instalamos las fuentes de texlive

    sudo dnf -y install texlive-titlesec texlive-framed texlive-threeparttable texlive-wrapfig texlive-upquote texlive-multirow 

# Edición de la documentación
Ahora sí! manos a la obra! 

La documentación está escrita en reStructuredText, es un sistema MarkDown muy fácil de usar!

Simplemente tenés que modificar los archivos que tienen la extensión.rst, por ejemplo el archivo index.rst es el que organiza los archivos y luego cada capítulo está en un .rst diferente.

# Generar documentos
Ahora ya podés generar tus archivos PDF y HTML !

Para generar los documentos en distintos formatos, debemos ingresar a la carpeta  manual_referencia_icaro/sphinx  y ahí ejecutamos la instrucción para generarlo, lo cual va a compilar y generar el archivo en la carpta _build .

#### PDF

    make latexpdf

Esto lo exporta a la carpeta _build/latex

#### HTML

    make html

Esto lo exporta a la carpeta _build/html

Espero que te haya resultado fácil! esperamos tus aportes!

# Licencia
Este proyecto es software libre y se distribuye bajo la licencia GPL V3. 
