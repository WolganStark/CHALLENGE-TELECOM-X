# CHALLENGE-TELECOM-X
<p align="center"><img src="https://github.com/user-attachments/assets/bb3ea1e2-61c8-4399-8800-3e250d9bb4b5"></p>
<p align="center">La empresa de telecomunicaciones `TELECOM X` solicitó nuestros serivicios como Cientificos de Datos, para análizar la evasión de los clientes que ha presentado</p>

## :hammer: ETL

- `EXTRACCIÓN DE DATOS`: Se extrajeron los datos mediante una API request al servidor en donde se encuentran los datos, mediante el uso de las librerias `json` `requests`, y se convierteron y explotaron los datos a través de la biblioteca `pandas`.

- `TRANSFORMACIÓN DE DATOS`: La transformación de datos se realizo mediante la biblioteca `pandas`, haciendo uso de una estrategia de encontrar los valores de las columnas mediante el uso del metodo `.unique()`, luego al tener la estructura de los datos, se inicio con la estandarización de los datos mediante el uso de metodos como `.replace()` o `.map()` para facilitar la siguiente fase del proyecto.

- `CARGA DE DATOS`: Haciendo uso de las bibliotecas `matplotlib` y `seaborn` se realizaron todos los gráficos que relacionaran los datos del DataFrame con la variable `Churn`, para lograr identificar cuales son los datos que influyen más en el aumento de evasión de los clientes.

- `INFORME FINAL`: Al final del notebook se encuentra el informe final en donde se encuentran los gráficos seleccionados para el análisis exploratorio de los datos. A través de los cuales se encuentran las sugerencias realizadas a la empresa `TELECOM X` para aumentar la retención de los clientes.





## :wrench: Como ejecutar el proyecto
1. Debes descargar el archivo del repositorio `TelecomX.ipynb`, tranquilo no tienes que ejecutarlo en tu maquina.

<p align="center"><img src="https://github.com/user-attachments/assets/247bbc21-365e-47bb-8e8d-a04bb542638c"></p>

2. Abre Google Colab con tu cuenta de Google

<p align="center"><img src="https://github.com/user-attachments/assets/a1c596f2-b2b6-4c46-a479-35cc8b6071fd"></p>

3. Sube el archivo que acabas de descargar

<p align="center"><img src="https://github.com/user-attachments/assets/5ea98394-2513-4ea0-b574-b76a387e2f1d"></p>
   
4. Da click en `Entorno de ejecución` y luego click en ejecutar todo, también puedes usar solo el teclado con el atajo `CTRL + F9`

<p align="center"><img src="https://github.com/user-attachments/assets/bae86cb6-19dd-4afc-8e10-6a3c3eb51a6c"></p>

5. Si deseas también puedes ejecutar cada celda individualmente, simplemente tienes que tener precaución de ejecutar primero la celda de `Importación de datos` ya que es la celda que trae los datos para manipularlos y también importa las librerias y dependencias usadas en el proyecto.

<p align="center"><img src="https://github.com/user-attachments/assets/26ae0542-dc2b-4d90-90b7-6f9a634bdbbf"></p>

Puedes hacer click en la esquina superior izquierda en el simbolo de `play` o puedes utilizar el atajo de teclado `CTRL + ENTER`

6. Ahora estás listo para utilizar esta poderosa herramienta que es Google Colab, y también para explorar con el código de este proyecto, siéntete libre de toquetear el código como tu quieras, este repositorio va a mantenerse funcional para que no tengas miedo de probar cosas distintas.
