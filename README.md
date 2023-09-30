# Prespuesto-para-clientes-foraneos - PRESFOR 

# OBJETIVOS 
Se creará un software para brindar una organización financiera a los estudiantes que vienen de otros lados, puede brindar un presupuesto y un reporte de gastos diario, semanal y mensual. A partir de un chat de inteligencia artificial te podrá comparar distintos sitios y recomendará la mejor opción para reducir gastos en comida, transporte y hospedaje.
USUARIOS/CLIENTES 
# Usuarios primarios: Nuestros clientes principales son estudiantes foráneos de la UMT. 
Perfil de los usuarios primarios 
- Edad: 17 a 27
- Cursando alguna licenciatura en la UMT
- Estudiantes que rentan 
# Usuarios secundarios: Los dueños de los locales de la localidad de Tizimín, compañeros de estudiantes foráneos. 
Perfil de los usuarios secundarios 
- Tener algún negocio 
- Tener algún transporte
# Potenciales: Los maestros de la UMT 
Perfil de los usuarios 
- Maestros foráneos 
- Maestros con dificultad para encontrar transporte 
- Maestros que busquen un lugar economico para comer
# PRopuesta de valor 
Esta es una herramienta innovadora porque añade un chat con inteligencia artificial, que ayudara al usuario a contribuir a su gestión financiera, funcionara con localización GPS, brindara un reporte estadístico basado en un calendario de tus gastos diarios y semanales, al igual que te recomienda el dinero que puedes gastar diariamente y tus ahorros que administraste a la semana, también lo que te recomienda gastar en tus gustos personales.




# Requerimientos

## Requerimientos del sistema
  

### Funcionales: 
| RF001   |      Gestor de videos      |  
|----------|:-------------:|
| Prioridad:| Alta |
| Descripción |La url,nombre, título de cada video se almacena en una base de datos y mediante el gestor de videos, es posible borrarlos, modificarlos o agregar nuevo contenido.|

***
<br>

| RF002   |      Reproducción de video      |  
|----------|:-------------:|
| Prioridad:| Alta |
| Descripción |El sistema es capaz de cargar un video desde el almacenamiento interno y los muestra al usuario en un reproductor embebido con sus respectivos controles (Play, Pausa, Mute, Control de volumen)|

***
<br>

| RF003   |       Interfaz Interactiva    |  
|----------|:-------------:|
| Prioridad:| Media |
| Descripción |El sistema mostrará los videos ocupando el 100% de la pantalla y cuando finalice la reproducción, mostrará una ventana flotante con una pregunta dirigida al usuario acerca del video. <br> El sistema mostrará la pregunta y sus respectivas respuestas en botones interactivos|

***
<br>

| RF004   |      Respuesta correcta      |  
|----------|:-------------:|
| Prioridad:| Media |
| Descripción |Al responder una pregunta de manera correcta, el sistema cambiará de video y comenzará a reproducirse |

***
<br>


| RF005   |      Respuesta incorrecta     |  
|----------|:-------------:|
| Prioridad:| Media |
| Descripción |Al responder una pregunta de manera incorrecta, el sistema mostrará un mensaje "Respuesta incorrecta" y un botón para repetir el video.|

***
<br>

| RF006   |      Usuario temporal      |  
|----------|:-------------:|
| Prioridad:| Baja |
| Descripción |El sistema puede ingresar un nombre de usuario temporal al momento de empezar el video interactivo. <br>El sistema mostrará el nombre de usuario al momento de realizar las preguntas |

***
<br>


| RF006   |      Registro de visitantes      |  
|----------|:-------------:|
| Prioridad:| Baja |
| Descripción |El sistema registra cada acción en el botón "Comenzar" y almacena esos valores en una base de datos. <br>El sistema contará con una pagina principal para mostrar la cantidad de usuarios que han probado el video interactivo |
***
<br>





### No funcionales:
| RNF001   |      Tiempo de respuesta       |  
|----------|:-------------:|
| Descripción | El sistema deberá contabilizar el tiempo que el usuario tarda en responder correctamente la encuesta |

***
<br>

| RNF002   |      Privacidad de datos    |  
|----------|:-------------:|
| Descripción |  El sistema no debe revelar ninguna información personal sobre el usuario, exepto su nombre.|

***
<br>

| RNF003   |      Límite de carácteres   |  
|----------|:-------------:|
| Descripción |  El sistema solo permite un máximo de 15 carácteres en el campo de texto usuario.|
<br>

***
| RNF004   |      Límite de memoria por video   |  
|----------|:-------------:|
| Descripción |  El sistema debe alojar los videos con un maximo de 100 Mb c/u, para que la carga de estos sea más rápida. |
<br>

***
| RNF005  |      Calidad de video  |  
|----------|:-------------:|
| Descripción |  Los videos estarán renderizados en calidad 720p, para reproducirse de manera eficiente en la mayoria de las redes inalambricas.|

***
