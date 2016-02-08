============
Introducción
============

La robótica pedagógica, dado su carácter multidisciplinario, permite el 
abordaje de conocimientos variados como la electrónica, informática, 
física y matemática mediante la construcción de un juguete-objeto 
como puede ser un robot. El desarrollo de estos juguetes-objetos 
implica una experiencia que contribuye a expandir la creatividad y el 
pensamiento reflexivo y científico de los alumnos, 
en relación a la formulación de hipótesis, la
experimentación y la elaboración de conclusiones, los cuales al 
enfrentarse a un “problema” dado, aprenden a experimentar, diseñar y 
resolver situaciones de carácter constructivista. En el proceso de 
“pensar el robot” , se generan las condiciones de apropiación 
del conocimiento por parte del alumno. 
Se trata de otorgar a los alumnos un rol activo en sus aprendizajes, 
colocándolos como diseñadores de sus propios proyectos y constructores 
de conocimientos. El uso de software libre en el ámbito escolar, 
permite tener control sobre las características del mismo, 
permitiendo adaptarlo a las necesidades concretas del ámbito escolar 
y las realidades socio-económicas de la institución, es neutro frente 
a fabricantes (el alumno no es un “potencial cliente”) y todo el 
material usado puede ponerse a disposición de otros docentes.

software libre en la educación
------------------------------

Antes de explicar que es el software libre, 
necesitamos conocer algunos aspectos claves del diseño y 
creación de cualquier programa, como el concepto de código fuente y 
como afecta a nuestra libertad el echo de no poder tener acceso al mismo.

Una computadora es básicamente una máquina electrónica que recibe y 
procesa datos para convertirlos en información útil, y esos datos 
apenas son cadenas de ceros y/o unos. Por lo tanto una computadora 
solo entiende código binario, Para hacer 
un programa mas o menos complejo, necesitamos muchísimos “ceros y unos”,  
lo que hace extremadamente complejo entender y programar en 
“lenguaje de maquina”. Para ello se diseñaron “lenguajes” mas parecidos 
a lo que un humano podría entender y mediante un software 
compilador podíamos convertirlo en archivo binario que nuestra 
computadora usa.

Podemos considerar al software como el Conjunto de programas, 
instrucciones y reglas informáticas para ejecutar ciertas tareas en una 
computadora por lo tanto es una parte central de una computadora 
porque es el que controla todos los procesos electrónicos de la 
misma. Para que una computadora haga algo, necesita un programa, y 
este tuvo que ser creado escribiendo en un lenguaje especial las 
instrucciones que dicho programa ejecutara, esto se conoce como 
Código fuente.

El código fuente es un texto escrito en un lenguaje de programación 
específico que puede ser leído por un programador, se puede considerar 
como un conjunto de líneas de texto que son las instrucciones que 
debe seguir la computadora. El código fuente esta escrito en primera 
instancia por un programador en un formato de texto plano y para que 
este archivo de texto pueda ser interpretado por una computadora, 
tiene que ser procesado por un software llamado «compilador», el cual 
en su definición más genérica, es un programa que toma como entrada un 
texto escrito usando la semántica de cierto lenguaje y produce como 
salida el texto de un programa en otro lenguaje. De esta manera podemos 
obtener de un lenguaje natural similar al lenguaje humano, un archivo 
en lenguaje de código maquina (código binario).

Para los programadores, leer el código maquina o código binario es una 
actividad muy difícil, por eso para poder modificar o estudiar un 
programa, se vuelve fundamental tener el código fuente original. A 
causa de que muchas empresas desarrolladoras de software no permiten 
conocer ni estudiar el código fuente de sus programas 
(software privativo), en el año 1985 Richard Stallman y otros 
entusiastas fundaron la Free Software Foundation con el objetivo de 
promover el uso del software libre.

Cuando Hablamos de software libre, nos referimos a todo software que 
por elección manifiesta de su autor, puede ser copiado, 
estudiado, modificado, utilizado libremente con cualquier fin y 
redistribuido con o sin cambios o mejoras. Para eso se definió 4 
«libertades» básicas que tiene que tener todo software para poder ser 
considerado de software libre:

#. La libertad de ejecutar el programa como se desea, con cualquier propósito (libertad 0). 
#. La libertad de estudiar cómo funciona el programa, y cambiarlo para que haga lo que usted quiera (libertad 1). El acceso al código fuente es una condición necesaria para ello. 
#. La libertad de redistribuir copias para ayudar a su prójimo (libertad 2). 
#. La libertad de distribuir copias de sus versiones modificadas a terceros (libertad 3). Esto le permite ofrecer a toda la comunidad la oportunidad de beneficiarse de las modificaciones. El acceso al código fuente es una condición necesaria para ello.

hardware libre
--------------

Menos difundido que el concepto de software libre, la idea del «hardware libre» 
(o mas precisamente, Hardware de fuentes abierta) trata de hacer un paralelismo 
entre las «cuatro libertades» del software libre, aplicadas a el diseño y protocolos de 
un dispositivo fisico.

Decimos que el hardware es libre en tanto el diseño de fabricación y 
el software con el que fueron echos esos diagramas, sean distribuidos con licencias libres.
Si bien, por su naturaleza física, un dispositivo (electrónico o mecánico) no puede ser 
equiparado a un programa de software, y por lo tanto, no es correcto equiparar 
las 4 libertades que se aplican al software libre a un objeto físico único, 
si se puede especificar que su diseño, esquemas, planos y demás componentes no-fisicos, 
tengan un tipo de licencia libre. De esta forma un diseño electrónico, puede ser estudiado, 
modificado y distribuido bajo los principios de las licencias GNU GPL 
(GNU General Public License) o similares.

Un PCB (Printed Circuit Board por sus siglas en ingles) 
es es la superficie constituida por pistas de material conductor 
sobre una base no conductora, se utiliza para interconectar los 
distintos componentes electronicos 
(resistensias electricas, capacitores, microcontroladores etc.) y 
generar un circuito por donde circule la corriente electrica, esta 
«tarjeta de circuito impreso» funciona como soporte fisico y esquema de 
conexión electronico.

Cuando se diseña un PCB, generalmente se necesitan 3 diagramas , 
el plano esquematico, el diseño del PCB y los ficheros de fabricación 
archivos (GERBER). Con esa información podemos fabricar nuestra propia 
versón de la plaqueta donde van soldados los componentes electronicos.

La ventaja del hardware libre es que permite adaptar nuestro diseño a 
las distintas realidades locales donde se implementara la fabricación 
de dicho dispositivo. De esta forma permite tener cierta independencia 
de un fabricante en particular, y hasta permitir la fabricación a 
pequeña escala (si el diseño asi lo permite), ademas de fomantar la 
industria nacional y pequeñas PYMES o cooperativas que fabriquen el 
hardware, aprovechando una comunidad de usuarios que 
documentan y dan soporte al mismo.

Un caso muy significativo de la movida del hardware libre, son las 
«impresoras 3d», dispositivo mecanico que permite fabricar componentes 
de 3 dimensiones mediante superponer capas de plastico derretido en una 
plataforma (usando distintos tipos de plasticos y hasta materiales 
como cemento o metales fundidos en maquinas mas experimentales) 
para lograr mediante la adicion sucesiva de capas de material, un 
objecto tri dimensional con cierta consistencia y duresa. 

Si bien la tecnologia de fabricación automatizada de piezas mecanicas 
existe desde hace mucho (los sistemas CNC o control numérico por 
computadora por ejemplo), el proyecto REPRAP se propuso fabricar una 
maquina-herramienta de bajo costo capas de «auto replicarse» fabricando 
las piezas para otras maquinas iguales. los creadores del proyecto 
visionan la posibilidad de distribuir a bajo costo máquinas RepRap a 
personas y comunidades, permitiéndoles crear (o descargar de Internet) 
productos y objetos complejos sin la necesidad de maquinaria 
industrial costosa. En ese sentido la idea del proyecto es poder 
diseñar una impresora que pueda ser facilmente fabricada 
por otras personas, sin necesidad de componentes industriales o 
maquinaria especial para su fabricación. Obviamente, implica 
una desición de compromiso entre cierta calidad de componentes y la 
facilidad de obtenerlos a pequeña escala, ademas de los 
conocimientos minimos necesarios para poder fabricar una impresora 
(desde conocimientos sobre electronica a cuestines mecanicas 
y cierta habilidad manual), por eso, comenzo a proliferar pequeñas 
compañias o micro emprendimientos de personas que fabrican y 
venden impresoras 3d basadas en los modelos de reprap (prusa I2 o 
tambien prusa I3). De esta forma un proyecto global que nace 
gracias a internet, genera trabajo para comunidades en distintas 
partes del mundo. 

En cierta forma, se podria decir que el hardware libre rescata la 
cultura del «hagalo usted mismo» 
(o DIY por sus siglas en ingles), aunque hay proyectos comerciales muy 
exitosos (como el caso de ARDUINO® y RASPBERRY PI®) 
que son de carácter mas industrial y que sin embargo aprovechan 
la ventaja de liberar sus diseños para contar con ua gran 
scomunidad de usuarios que utilizan su hardware y crean documentación o 
tutoriales a traves de internet. 


