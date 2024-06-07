# IntegradoraPractica02

En está práctica aprenderemos autilizar las herramientas Git y GitHub para el control de versiones,
documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la Asignatura de Integradora I.

## Comandos Básicos para la documentación, utilizando el estándar de Markdown (md)
Markdown es el estandar utilizado por Git y Github para maquetar la documentación de proyectos, lo que permite 
a usuarios y colaboradores del proyecto entender el contexto y operació del mismo.

### 1. Encabezados o Títulos (HEADERS)
Para poder realizar una buena documentación del proyecto debemos, distribuir correctamente los contenido, 
para poder delimitar o hacer enfásis (enfatizar) es decir resaltar las secciones importantes, podemos utilizar los siguientes:

EJEMPLOS:
# Encabezado de Nivel 1 - similar a H1 en HTML
## Encabezado de Nivel 2 - similar a H2 en HTML
### Encabezado de Nivel 3 - similar a H3 en HTML
#### Encabezado de Nivel 4 - similar a H4 en HTML
##### Encabezado de Nivel 5 - similar a H5 en HTML
###### Encabezado de Nivel 6 - similar a H6 en HTML
####### Encabezado de Nivel 7 - Sólo 6 son los niveles permitidos, a partir de este el maquetado será ignorado.

### 2. Separadores (SEPARATORS)

Si desea marcar una separación más visual de contenidos podemos utilizarlos indicando tres carácteres de "-" continuos, en el maquetado.

EJEMPLO
---

*Esto es similar a un tag de < HR > en HTML.

### 3. Párrafos (PARAGRAPHS)

Son utilizados para presentar grandes secciones de texto que describren detalladamente las secciones de la documentación del proyecto.

EJEMPLO:

Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1.

Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2.

Lo que en una página utilizaríamos la etiqueta < P >.

También podemos aplicar estilos básicos de alineación:

Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto.

<p align="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. 

</p>

<p align="center">
Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. 
</p>

<p align="justify">
Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. 

</p>

### 4. Texto Enfatizado (BOLD, ITALIC, BOLD/ITALIC)

Si el texto que debemos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

##### Texto en Negrita (BOLD)

Para poder poner el texto en negrita, este deberá ser encerrado entre doble **.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto **Texto** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Cursiva (ITALIC)

Para poder poner el texto en cursiva, este deberá ser encerrado entre * o -.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Negrita/Cursiva (BOLD/ITALIC)

Para poder poner el texto en negrita/cursiva, este deberá ser encerrado entre triple ***.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto ***Texto*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto subrayado (UNDERLINE) 

Algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML usando el tag \<ins> y cerrando con \</ins>.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto importante Texto Texto</ins> Texto Texto Texto Texto Texto 
