# Integradora-Practiaca-2
Practica de Clase para comenzar a utilizar GitHub cómo herramienta para el desarrollo colaborativo, control de versiones y documentación del Proyecto integrador de la asignatura 
##Comando basico para el paquetado
###Encabezado (Headings)
Para poder dar enfasis  a lo componetes de la documentacion podemos utilizar lo encabezados (headings), para marcar alguna seccion o subseccion estos se marcan utilizando el simbolo # , entre menos repeticiones tenga mayor tamaño e importancvia tendar el texto 
  Ejemplo:
  # Encabezado de nivel 1
  ## Encabezado de nivel 2
  ### Encabezado de nivel 3
  #### Encabezado de nivel 4
  ##### Encabezado de nivel 5
  ###### Encabezado de nivel 6
  ####### Encabezado de nivel 7

  ### 5. Cuadros para código o reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración y/o mostrar secciones de código fuente 

Para listar las carpetas y archivos en desde una terminal de sistema operativo Windows debemos ingresar el comando:

>C:/dir 

Después oprimimos la tecla "Enter".

También podemos ingresar textos multilínea

**EJEMPLO:**  
>Aquí se ingresa un conjunto de instrucciones
>Para explicar al usuario, como instalar el 
>software que hemos diseñado

Y si deseamos utilizar viñetas para enlistar pasos podemos utilizar el carácter - dentro del texto a documento.

**EJEMPLO:**

*PASOS PARA ENLISTAR LA BASE DE DATOS*

>- Descargar MySQL Server del Sitio Oficial 
>- Instalar el Sistema Gestor de Base de Datos definiendo el puesto y la contraseña para el usuario **root**
>- Descarguemos el archivo de respaldo de la base de datos (.sql)
>- Restauremos la Base de Datos usando el comando Mysql 
>- C:ProgramFiles/MySQL/MYSQLServer8.0/bin/mysql-u root -p password < respaldo sql

*6. Listas ordenadas y Desordenadas*

Si en nuestra documentación necesitamos incluir información de texto en modo de lista, un elemento tras otro podemos hacerlo utilizando los números con un punto decimal
si las deseamos ordenadas o en un guion en medio  - si solo queremos una viñeta

*EJEMPLO*

Para poder crear tu primero repositorio en GitHub deveras;

1. Contar con una cuenta de GitHub

2.Dar clic en *nuevo repositorio

3- Asignarle un nombre a tu repositorio, por ejemplo: 'practica03-3b'

4.Asignarle un nivel de privacidad

-**PUBLICO:** SI quieres que este disponible para todos lo usuarios

-**PRIVADO:** Si deseas que a solo decidas pueden colaborar en tu proyecto

10. Definir si incluye un archivo de descripción llamado: RAEDME.md

11. Definir si habrá exculciones de archivo atravez del archivo : gitignore

12. Guardar cambios 

### 7. Ligas (Hipervinculos)

Las ligas utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando los corchetes \[\] después pondremos la liga de referencia entre paréntesis /()

**EJEMPLO**

Mi buscador favorito es: [www.google.com]/(https://google.com)
Pero si deseas poner solo la ligas directas a un correo electrónico podemos utilizar los símbolos \<\>

**EJEMPLO**
Documentación creada por **Jonathan Emmanuel López Morales**
(<jonathanesponja33@gmail.com>)(<https://utxicotepec.edu.mx
>)
>### 8. Tablas (TABLES)
Si la si la documentación lo requiere podemos presentar información en formato de tablas con columnas para mantenerlas podemos utilizar el carácter | para delimitar las columnas y -P de limitar las filas 

**EJEMPLO:**

|**Encabezado 1** | **Encabezado 2** | **Encabezado 3** | **Encabezado 4**|
|-----------------|------------------|------------------|-----------------|
|Fila 1 Celda 1   |  Fila 1 Celda 2  |  Fila 1 Celda 3  | Fila 1 Celda 4  |
|Fila 2 Celda 1   |  Fila 2 Celda 2  |  Fila 2 Celda 3  | Fila 2 Celda 4  |
|Fila 3 Celda 1   |  Fila 3 Celda 2  |  Fila 3 Celda 3  | Fila 3 Celda 4  |

En caso de necesitar la funcion de celdas en cloumnas usaremos la propiedad colspan para unir las celdas y en el caso de la fusion de las filas utilizaremos la propiedad rowspan
**EJEMPLO:**
<table>
  <tr>
  <th>Encabezado1</th>
  <th>Encabezado2</th>
  <th>Encaberado3</th>
  <th>Encabezado4</th>
</tr>
  <tr>
    <td>file 1 celda 1</td>
    <td>file 1 celda 2</td>
    <td>file 1 celda 3</td>
    <td>file 1 celda 4</td>
  </tr>
    <tr>
    <td>file 2 celda 1</td>
    <td colspan="2" >file 2 celda 2</td>
    <td>file 2 celda 4</td>
  </tr>
    <tr>
    <td></td>
    <td>file 3 celda 2</td>
    <td>file 3 celda 3</td>
    <td>file 3 celda 4</td>
  </tr>
    <tr>
    <td>file 4 celda 1</td>
    <td>file 4 celda 2</td>
    <td>file 4 celda 3</td>
    <td>file 4 celda 4</td>
  </tr>
  <tr>
    <td></td>
    <td>file 5 celda 2</td>
    <td>file 5 celda 3</td>
    <td>file 5 celda 4</td>
  </tr>
  <tr>
    <td>file 6 celda 1</td>
    <td>file 6 celda 2</td>
    <td>file 6 celda 3</td>
    <td>file 6 celda 4</td>
  </tr>
</table>
Dado que el ejemplo pasado solo utiliza Mark down no se puede realizar la función debemos utilizar el estándar html usando los tags PH para los encabezados filas y celdas y en ellos utilizar propiedades como colspan y Rowspan

**EJEMPLO:**
<table>
  <tr>
  <th>Encabezado1</th>
  <th>Encabezado2</th>
  <th>Encaberado3</th>
  <th>Encabezado4</th>
</tr>
  <tr>
    <td>file 1 celda 1</td>
    <td>file 1 celda 2</td>
    <td>file 1 celda 3</td>
    <td>file 1 celda 4</td>
  </tr>
    <tr>
    <td>file 2 celda 1</td>
    <td colspan="3" align="center">file 2 celda 2</td>
  </tr>
    <tr>
    <td></td>
    <td>file 3 celda 2</td>
    <td>file 3 celda 3</td>
    <td>file 3 celda 4</td>
  </tr>
    <tr>
    <td>file 4 celda 1</td>
    <td>file 4 celda 2</td>
    <td>file 4 celda 3</td>
    <td>file 4 celda 4</td>
  </tr>
  <tr>
    <td></td>
    <td>file 5 celda 2</td>
    <td>file 5 celda 3</td>
    <td>file 5 celda 4</td>
  </tr>
  <tr>
    <td>file 6 celda 1</td>
    <td>file 6 celda 2</td>
    <td>file 6 celda 3</td>
    <td>file 6 celda 4</td>
  </tr>
</table>
### 9. logos de la empresa
son las imagenes de los logos para la empresa para el proyecto de integracion 

Logo de las playeras de los inspectores:
![](https://github.com/EMATIAS230045/Integradora-Practica-2/blob/main/logo1.jpg) <br></br><br></br>
Logo del icono de perfil:
![](https://github.com/EMATIAS230045/Integradora-Practica-2/blob/main/logo2.jpg)<br></br><br></br>
Logo del icono de bitacora:
![](https://github.com/EMATIAS230045/Integradora-Practica-2/blob/main/logo3.jpg)<br></br><br></br>

