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

# Integradora-Practica03

Continuamos con los comandos básicos de Git y Github para el maquetado de la documentación.

### 5. Cuadros para código o Reseñas (BLOCKQUOTES)

  Estos elementos para resaltar instrucciones específicas para la instalación, configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (\>).
  
  **EJEMPLO:**
  Para listar las carpetas y archivos desde una terminal de sistema operativo Windows debemos ingresar el comando: 

  > C:/dir

Después oprimimos la tecla "enter". 

También podemos ingresar textos multilineales

**EJEMPLO:**

>Aquí se ingresa un conjunto de instrucciones
>para explicar al usuario, como instalar el
>software que hemos diseñado.

 Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter 
 -dentro del texto a documentar.

**EJEMPLO**
 **Pasos para instalar la base de datos**
 > - Descargar MySQL Server delsitio oficial
>  - Instalar el SistemaGestor de Base de Datos, definiendo el puerto y contraseña para el usuario ***root***
>  - Descargamos el archivo de respaldo de la base de datos (.sql)
>  - Restauramla Base de Datos usando el comando *mysql *
>> C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password \< respaldo.sql


### 6.Listas Ordenadas y Listas Desordenadas

Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro podemos hacerlo utilizamos los números con un punto decimal si las deseamos ordenadas o un guión medio - si solo queremos una viñeta.

**EJEMPLO**
Para crear tu primer repositorio en GitHub deberás:
1. Contar con cuenta de GitHub.
1. Dar click en el boton: **Nuevo Repositorio*
2. Asignarle un Nombre a tu repositorio, por ejemplo:  *practicas3-3b*
8. Asignarle un nivel de privacidad entre
   - **Público:** Si quieres que éste disponible para todos los usuarios.
   - **Privado:** Deseas que solo a quien tu decidas puedan ver y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado : *README.md*
50. Definir si habrá exclusiones de archivo a través de archivo: *.gitignore*
3. Guardar los cambios.

#### 7. Ligas (HIPERVINCULOS)
Las ligas son utilizadas para víncular elementos o referencias delproyecto dentro del mismo repositorio o fuera de él. Y se maquetan utilizando los corchetes \[ \]

**EJEMPLO**
Mi buscador favorito es: [Google](https://www.google.com)

Pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizas los símbolos \< \>

**EJEMPLO**

Documentación creada por: ***Esther González Peralta***

<230297@utxicotepec.edu.mx>

<http://www.utxicotepec.edu.mx>
