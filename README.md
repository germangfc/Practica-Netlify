# Practica-Netlify
## Objetivo
El objetivo es comprobar el despliegue continuo automático en Netlify de una web personal que enlaza a un curriculum usando HTML y CSS y Bootstrap. 
Se mostrarán capturas de dicho despliegue continuo en Netlify cada vez que se haga un cambio en la rama main del proyecto.

## Proceso y capturas
La idea es crear un repositorio con nuestro proyecto en GitHub, donde se alojará nuestro proyecto base y que importaremos posteriormente desde Netlify.
Iremos haciendo cambios en el repositorio para comprobar que Netlify hace el despliegue continuo.

Previamente, nos habremos registrado y logueado en Netlify, en mi caso, con mi usuario de GitHub.
### 1. Repositorio GitHub
Creamos el repositorio vacío en GitHub.  

<img src="./capturas/01.png" max-width="80%">

### 2. Importar desde Netlify
Importamos el repositorio:  

<img src="./capturas/02.png" max-width="80%">  

\
Elegimos el origen (GitHub):

<img src="./capturas/03.png" max-width="80%">

\
Autorizamos a Netlify verificando nuestra identidad de GitHub:

<img src="./capturas/04.png" max-width="80%">

\
Instalamos, modificando la opción por defecto (All repositories) para
que se apliquen varios permisos solo para este repositorio:

<img src="./capturas/05.png" max-width="80%">  
<img src="./capturas/06.png" max-width="80%">  

\
Confirmamos el acceso a GitHub:

<img src="./capturas/07.png" max-width="80%">

\
Una vez confirmada nuestra identeidad, nos devuelve a la pantalla anterior en Netlify y procede con el despliegue:

<img src="./capturas/08.png" max-width="80%">

\
Debemos configurar varios apartados del despliegue. En este caso únicamente
el nombre del sitio (por el que luego podremos acceder a nuestra página en Netlify) y la rama que se desplegará.

En mi caso la página de Netlify es: https://germangfc.netlify.app y la rama elegida la ***main***.


<img src="./capturas/09ok.png" max-width="80%">

<img src="./capturas/10.png" max-width="80%">

### 3. despliegue inicial

Hacemos clic en **Deploy** para proceder con el despliegue:

<img src="./capturas/11.png" max-width="80%">
<img src="./capturas/12.png" max-width="80%">

\
Hacemos clic en **View site deploy** para acceder al resultado del despliegue.
En nuestro caso, observamos que solo se ha subido un archivo, que es el README.md
de nuestro repositorio, inicialmente no tiene mas:

<img src="./capturas/13.png" max-width="80%">
<img src="./capturas/14.png" max-width="80%">


### 4. Modificación del repositorio

Realizamos cambios en nuestro repositorio. En este caso, subimos la página inicial.

Con esto provocaremos un cambio en la rama main, que activará el despliegue automático en Netlify

\
Justo tras subir los cambios al repositorio: 

<img src="./capturas/15.png" max-width="80%">

\
En Netlify aparece el inicio del despliegue: 
<img src="./capturas/16.png" max-width="80%">

\
Y entrando en el despliegue podemos ver el log:

<img src="./capturas/17.png" max-width="80%">

\
Y una vez finalizado, el resultado (un archivo añadido):

<img src="./capturas/18.png" max-width="80%">
<img src="./capturas/19.png" max-width="80%">

### 5. Modificaciones posteriores

Añadimos nuevos archivos y modificaciones a nuestro repositorio: modificamos la página inicial 
y subimos sus imágenes, estilos, la página con el CV y un *.gitignore*:

<img src="./capturas/21.png" max-width="80%">
<img src="./capturas/22.png" max-width="80%">


<img src="./capturas/23.png" max-width="80%">
<img src="./capturas/24.png" max-width="80%">
<img src="./capturas/25.png" max-width="80%">
<img src="./capturas/26.png" max-width="80%">


