# PracticaGit
esta practica sirve para para conocer los comandos basicos del maquetado bajo el estandar de MARKDOWN(.md), servira para crear la documentación de nuestros proyectos de softwaredurante nuestra formacion profecional.
## Titulo (HEADERS)
si se desea ubicar secciones de algun tema podemos resaltarlos como encabezados. Estos son mus similares a las etiquetas \<h1>....\<h6> en HTML.
**EJEMPLO:**
# titulo1
## titulo2
### titulo3
#### titulo4
##### titulo5
###### titulo6
####### titulo7
este estandar solo permite hasta 6 titulos, despues de seis omitira la instruccion del maquetado.

## 2 separadores (SEPARATORS)
coloca unal linea vertical entre las secciones del documentoorganizando y distribuyendo mejor el contenido, puede ser maquetado con 3 guiones medios (---) despues del parrafo iniciado.
**EJEMPLO:**
parrafo1 coloca unal linea vertical entre las secciones del documentoorganizando y distribuyendo mejor el contenido, puede ser maquetado con 3 guiones medios (---) despues del parrafo iniciado.
---
parrafo2 coloca unal linea vertical entre las secciones del documentoorganizando y distribuyendo mejor el contenido, puede ser maquetado con 3 guiones medios (---) despues del parrafo iniciado.
## 3 parrafos (PARACHAPS)
representan el texto descriptivo del documento de los proyectos, podemos utilizar la propiedad de "align" de HTML para la alineacion. 
**EJEMPLO:**
parrafo1 en caso de nodefinir el parrafo se va a la izquierda 
<p align="center"> parrafo2 con la etiqueta p y la propiedad align="center" el parrafo se centrara.
  <p align="right"> parrafo2 con la etiqueta p y la propiedad align="right" el parrafo se ira a la derecha
    <p align="justify"> parrafo2 con la etiqueta p y la propiedad align="justify" el parrafo se justificara, para darle una presentacion adecuada y formal
      
## 4 texto enfatizado (BOLD, ITALIC, ITALIC BOLD Y UNDERLINE)
es posible resaltar algunas palabras importantes en la informacion utilizando la estilizacion de "LETRAS NEGRITAS" para la cual colocaremos dos * antes y despues de la palabra a resaltar "LETRAS CURSIVAS" solo con un * antes y despues *** CURSIVA Y NEGRITA *** y por ultimo  <ins>  subrayado  </ins>  dentro de la etiqueta \<ins> y cierre \</ins>
## 5 cuadro de codigo o reseñas (BLOCKQUOTES)
utilizado para resaltar instrucciones especificas para la instalacion, configuracion y/o inicializacion del proyecto para mostrar las selecciones del codigo fuente y maquetado utilizando el simbolo mayor que (>) antes del texto.
**EJEMPLO:**
para listar las carpetas o archivos desde una terminal de comandos en el sistema operal debemos usar el comando:
> c:dir
despues demos "enter"
**EJEMPLO:**
> descargar el archivo desde www.msql.com
> instalar el servidor de base de datos
> definir el puerto y contraseña para el usuario **root**
> inicializar el servidor
> conectar a la base de datos
## 6 listas ordenadas y no ordenadas 
si se necesita incluir informacion en modo de lista, es decir elementos tras elementos podemos hacerlo ya sea usando viñetas o numeros definidos.
para el uso de viñetas es agregar (-) antes del texto:

**EJEMPLO:**

mi tipo favorito de musica es:
- KPOP
- bachata
- musica mexicana

  para usar los numeros es con un (.):
  
  **EJEMPLO:**
  
  crea un nuevo repositorio en **GitHub**:
  
  1. crear una cuenta en GitHub
  2. logear mi cuenta
  6. ir a la pagina principal
  7. en el menú lateral buscar **NUEVO REPOSITORIO**
  8. asignar un nombre
  98. definir si es:
      
 -**publico:** cualquiera lo ve y lo consulta
 -**privado:** solo quien tenga autorizacion
 
  1. agregar un primer archivo documental *README.MD*
  2. Aprobar su creacion
     
## 7 ligas e hipervinculos (LINKS)
redirigen archivos, secciones dentro o fuera del repositorio. Se maquetan utilizando corchetes \[\], inmediatamente de parentesis con la url de destino \(\).
**EJEMPLO:**
mi buscador favorito es: [Google] (https://google.com)
Esta documentacion fue creada por **Karla Yulenni Domínguez Amador** 230284@utxicotepec.edu.mx
## 8 Tablas (TABLES)
se puede representar la informacion de manera de tablas con columnas y filas, para las columnas es el caracter |, y para las filas es el caracter -
**EJEMPLO:**

|encabezado1 | encabezado2 |encabezado3 |
|------------|--------------|--------------------|
| fila1 celda1 |  fila1 celda2 |  fila1 celda3 |
| fila2 celda1 |  fila2 celda2 |  fila2 celda3 |

## Imagenes 
Para ver debemos cargar los archivos en nuestro repositorio y vincularlo.
![Liga] C:\Users\Karla\Downloads = (https://www.youtube.com/watch?v=mHNCM-YALSA)
