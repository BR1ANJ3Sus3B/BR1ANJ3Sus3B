# Integradora-Practica02

En está práctica aprenderemos autilizar las herramientas Git y GitHub para el control de versiones,documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la Asignatura de Integradora I

## Comandos Básicos para la documentación, utilizando el estandar de Markdown (md)
Markdown es el estandar utilizado por Git y Github para maquetar la documentación de proyectos, lo que permite 
a usuarios y colaboradores del proyecto entender el contexto y operació del mismo.
### 1. Encabezados o Títulos (HEADERS)
Para poder realizar una buena documentación del proyecto debemos, distribuir correctamente los contenido, para poder delimitar o hacer enfásis (enfatizar) es decir resaltar las secciones importantes, podemos utilizar los siguientes:

EJEMPLOS:
# Encabezado de Nivel 1 - similar a H1 en HTML
## Encabezado de Nivel 2 - similar a H2 en HTML
### Encabezado de Nivel 3 - similar a H3 en HTML
#### Encabezado de Nivel 4 - similar a H4 en HTML
##### Encabezado de Nivel 5 - similar a H5 en HTML
###### Encabezado de Nivel 6 - similar a H6 en HTML
####### Encabezado de Nivel 7 - solo son los niveles permitidos, a partir de este el maquetado será ignorado.


### 2.Separadores (SEPARATORS)
Si desea marcar una separación más visual de contenidos podemos utilizarlos indicando tres carácteres de guión medio "-"continúos, en el maquetado


EJEMPLO
---
*Esto es similar a un tag de < HR > en HTML.

### 3.Párrafos (PARAGRAPHS)
Son utilizados para presentar grandes secciones de texto que describen detalladamente las secciones de ladocumentación del proyecto. 

EJEMPLO:
<p>Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1
Este texto pertenece al párrafo 1

Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2

Lo que en una página utilizariamos usando la etiqueta < /P >.

También podemos aplicar estilos básicos de alineación:

Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto
Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto
Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto
Este párrafo esta alineado a la izq por defecto
<p align="right">
Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion.
Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion.
</p>

<p align="center">
Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion. Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion. Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion. 
</p>

<p align="justify">
Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación.Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación.
</p>
### 4. Texto enfatizado (BOLD,ITALIC, BOLD/ITALIC)

Si el texto que deseamos enfatizar se encuentra en un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

##### Texto en Negrita (BOLD)
Para poder poner el texto en negrita, este debera ser encerrado en dos **

EJEMPLO:
**Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante****Texto importante**
Enfatizar texto en negrita es útil cuando quieres resaltar ciertas palabras o frases para que sean más visibles y fácilmente identificables para los lectores. Puedes utilizar este formato para destacar términos clave, notas importantes o cualquier otro contenido que desees resaltar en tu documentación.



Algunas veces necesitamos subrayar Texto dentro de la documentacion ,para ellos,si bien markdown no tiene un atajo o codificacion rápida podemos utilizar el estilo que se usa al estandar de HTMLestilo que se usa al estandar de html  usando el tag<ins> y cerrado con </ins>.

***texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto******texto***
 
Texto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,textoTexto,Texto,texto<ins>Subrayado</ins>.Texto

# Integradora_Practica 03
continuando con las comandos basicosde git y githubpara el maquetado de la documentacion.

###5. Cuadros para el codigo o Reseñas (BLOCKQUOTES)
Estos elementos son utilizados para resaltar instrucciones especificas para la instalacion ,configuracion y/o inicializacion o mostrarsecciones de codigo fuete. Se maqueta iniciando el texto con un simbolo de nmenor que .

** Ejemplo **
Para utilizar las carpetas y archivos en desde un material de sistema operativo windows debemos ingresar el comando:
>c:/dir
Despues oprimir la letrar enter
Tambien podemos ingresar  textos multiples

**Ejemplo **
>c:/dir
>- Descargar MySQL server de sitio ofical
>- Instalar el sistema gestor de base de datos ,  definiendo el puerto y contraseña para el usuario ***rot***
>- Descargamos nel archivo de respaldo de la base de datos (.sql)
>- Restauramos la base de datos usando el comando *myql*
>- c:/program files/MySQL/Mysql server 8.0/bin /mysql -u root  -p password \< respaldo .sql
### 6. Listas ordenadas y listas Desordenadas 
si nuestra documentacion necesitamos incluir innformacion en modo de lista, un elemento tras otro podemos hecarlo un punto decimal si las deseamois ordenadas o un guion medio - si solo queremos una viñeta .
**EJEMPLO **
Para crear tu primer  repositario de Github deberas:
1-. Contar un cyenta de Github.
2-. Dar click en el boton :**nuevo Repositorio 
3-.Asignar un Nombre a tu reporitario, por ejemplo : *practica03-3b*
4-. Asignar un nivel de privacidad entre 
- **Publico :** Si quiere que este disponible para todos los usuarios .
- **Privado :** si desa que solo a quien tu decidas puedan y colaborar con tu proyecto .
- 5.Definir si incluye un archivo de descripcion llamado : *README.md*
- 50. Definir si habra exclusiones de archivo a traves del archivo : *gitignore*
      3. Guardar los cambios 
### 7. ligas (Hipervinculo)
las ligas son utilizados para vincular elementos o referencia del proyecto  dentro del mismo repositorio o fuera de de el. y se maquetan utilizando los corchetes 
\[\]
**Ejemplo : **
Mi buscardor favorito es: [google](https://chatgpt.com/).

Pero si deseamos poner solo las ligas directas o un correo electronico podemos  utilizar los simboloss \<\>

**Ejemplo**
Documentacion creada por : **T.S.U.Brian Jesus Mendoza Marquez** 
<230308@utxicotepec.edu.mx> 

<http://virtual.utxicotepec.edu.mx/>

### 8. Ingreso de imágenes (Hipervínculos)
¡Como insertar una imagen hipervínculos necesitamos poder meternos code y donde dice Add file flecha abajo y ponemos Upload files arrastramos una imagen copeamos el link de nuestra imagen y ocupamos los siguientes símbolos! [] (link de la imagen)


![](https://github.com/BR1ANJ3Sus3B/BR1ANJ3Sus3B/blob/main/WhatsApp%20Image%202024-06-12%20at%206.37.38%20PM.jpeg)

![](https://github.com/BR1ANJ3Sus3B/BR1ANJ3Sus3B/blob/main/WhatsApp%20Image%202024-06-12%20at%206.37.39%20PM.jpeg).


*** 9. Tablas (TABLES)
Sila documentación lo requiere podemos presentar información en formato de tablas con filas y 
columnas, para maquetarlas podemos utilizar el carácter \| para delimitar las columnas y \- para
delimitar las filas.


**EJEMPLO:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|-------------|---------------|--------------|---------------|
| Fila 1 celda 1| Fila 1 celda 2| Fila 1 celda 3| Fila 1 celda 4|
| Fila 2 celda 1| Fila 2 celda 2| Fila 2 celda 3| Fila 2 celda 4|
| Fila 3 celda 1| Fila 3 celda 2| Fila 3 celda 3| Fila 3 celda 4|

En caso de necesitar  la fusión de celdas en columnas usaremos la propiedad *colspan* del tag \<td> y 
en el caso de necesitar la fusión de filas utilizaremos la propiedad *rowspan*.

**EJEMPLO:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|-------------|---------------|--------------|---------------|
| Fila 1 celda 1| Fila 1 celda 2| Fila 1 celda 3| Fila 1 celda 4|
| Fila 2 celda 1 <td colspan=2>  Fila 2 celda 2| Fila 2 celda 3|
| Fila 3 celda 1| Fila 3 celda 2| Fila 3 celda 3| Fila 3 celda 4|
|               | Fila 4 celda 2| Fila 4 celda 3| Fila 4 celda 4|
|               | Fila 5 celda 2| Fila 5 celda 3| Fila 5 celda 4|
| Fila 6 celda 1| Fila 6 celda 2| Fila 6 celda 3| Fila 6 celda 4|


Dado que el ejemplo pasando usando solo markdown no se puede realizar la fusion de filas debemos
utilizar el estandar de HTML usando los tags: \<tr> para las filas y <td> 
para las celdas, y en ellos utilizar la propiedad de *colspan* y *rowspan*


**EJEMPLO:**

<table>
<tr>
<th>Encabezado 1</th>
<th>Encabezado 2</th>
<th>Encabezado 3</th>
<th>Encabezado 4</th>
<tr/>

<tr>
<td>Fila 1 celda 1</td>
<td>Fila 1 celda 2</td>
<td>Fila 1 celda 3</td>
<td>Fila 1 celda 4</td>
<tr/>

<tr>
<td>Fila 2 celda 1</td>
<td colspan=3 align="center">Fila 2 celda 2</td>
<tr/>

<tr>
<td rowspan=3>Fila 3 celda 1</td>
<td>Fila 3 celda 2</td>
<td>Fila 3 celda 3</td>
<td>Fila 3 celda 4</td>
<tr/>


<tr>
<td>Fila 4 celda 2</td>
<td>Fila 4 celda 3</td>
<td>Fila 4 celda 4</td>
<tr/>

<tr>
<td>Fila 5 celda 2</td>
<td>Fila 5 celda 3</td>
<td>Fila 5 celda 4</td>
<tr/>


<tr>
<td>Fila 6 celda 1</td>
<td>Fila 6 celda 2</td>
<td>Fila 6 celda 3</td>
<td>Fila 6 celda 4</td>
<tr/>

</table>
