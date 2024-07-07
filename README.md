# PracticaGit
Esta practica sirve para para conocer los comandos basicos del maquetado bajo el estandar de MARKDOWN(.md), servira para crear la documentación de nuestros proyectos de softwaredurante nuestra formacion profecional.
## Titulo (HEADERS)
Si se desea ubicar secciones de algun tema podemos resaltarlos como encabezados. Estos son mus similares a las etiquetas \<h1>....\<h6> en HTML.
**EJEMPLO:**
# titulo1
## titulo2
### titulo3
#### titulo4
##### titulo5
###### titulo6
####### titulo7
este estandar solo permite hasta 6 titulos, despues de seis omitira la instruccion del maquetado.

## 2 Separadores (SEPARATORS)
Coloca unal linea vertical entre las secciones del documentoorganizando y distribuyendo mejor el contenido, puede ser maquetado con 3 guiones medios (---) despues del parrafo iniciado.
**EJEMPLO:**
parrafo1 coloca unal linea vertical entre las secciones del documentoorganizando y distribuyendo mejor el contenido, puede ser maquetado con 3 guiones medios (---) despues del parrafo iniciado.
---
Parrafo2 coloca unal linea vertical entre las secciones del documentoorganizando y distribuyendo mejor el contenido, puede ser maquetado con 3 guiones medios (---) despues del parrafo iniciado.
## 3 Parrafos (PARACHAPS)
Representan el texto descriptivo del documento de los proyectos, podemos utilizar la propiedad de "align" de HTML para la alineacion. 
**EJEMPLO:**
Parrafo1 en caso de nodefinir el parrafo se va a la izquierda 
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
Despues demos "enter"
**EJEMPLO:**
> Descargar el archivo desde www.msql.com
> Instalar el servidor de base de datos
> Definir el puerto y contraseña para el usuario **root**
> Inicializar el servidor
> Conectar a la base de datos
## 6 Listas ordenadas y no ordenadas 
Si se necesita incluir informacion en modo de lista, es decir elementos tras elementos podemos hacerlo ya sea usando viñetas o numeros definidos.
para el uso de viñetas es agregar (-) antes del texto:

**EJEMPLO:**

Mi tipo favorito de musica es:
- KPOP
- Bachata
- Musica mexicana

  Para usar los numeros es con un (.):
  
  **EJEMPLO:**
  
  Crea un nuevo repositorio en **GitHub**:
  
  1. Crear una cuenta en GitHub
  2. Logear mi cuenta
  6. Ir a la pagina principal
  7. En el menú lateral buscar **NUEVO REPOSITORIO**
  8. Asignar un nombre
  98. Definir si es:
      
 -**Publico:** cualquiera lo ve y lo consulta
 -**Privado:** solo quien tenga autorizacion
 
Agregar un primer archivo documental *README.MD*
  2. Aprobar su creacion
     
## 7 Ligas e hipervinculos (LINKS)
redirigen archivos, secciones dentro o fuera del repositorio. Se maquetan utilizando corchetes \[\], inmediatamente de parentesis con la url de destino \(\).
**EJEMPLO:**
Mi buscador favorito es: [Google] (https://google.com)
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

Imagenes en JPG o PNG
