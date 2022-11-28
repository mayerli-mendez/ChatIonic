# ESCUELA POLITÉCNICA NACIONAL

* ING. JUAN PABLO ZALDIUMBIDE 👨🏻‍🏫

#  EXAMEN BIMESTRAL 1

INTEGRANTES👩‍💻 
- Amoguimba Jessica

# INSTRUCCIONES DEL EXAMEN

Desarrollar en ionic una aplicación que me permita chatear y que guarde todos los mensajes de cada usuario, los mensajes deben guardarse cifrados. Se debe registrar el texto escrito y el usuario que ingresa dicho texto, es decir se dbe implementar un login.

El chat permitirá subir imágenes, las cuales también deben ser protegidas.

Entregables: Repositorio de github con readme detallado que incluya un video del funcionamiento del aplicativo. Subir el link del video y el apk en el repositorio. El readme y el video deben tener la explicación de las funciones y métodos implementados. 

Agregar como colaborador a jzaldumbide@gmail.com

# INTRODUCCIÓN  📝

Este README contiene un explicativo sobre la aplicación que será realizada para lo cual se hace uso de herramientas tales como:
- Ionic usando Angular 
- Firebase
Todo esto se utilizarácon el fin de crear una aplicación que permita ingresar a la app registrandose, una vez registrado podrá ingresar al chat donde se podrá enviar y recibir mendajes de texto y archivos multimedia (imagenes).

## Acerca del proyecto ##
### Explicación ###
## NOTA: ##
Previo a la realización del proyecto se debe verificar las versiones de las herramientas que usaremos.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/versiones.png)

### Comandos usados
Ejecutaremos los siguientes comandos :
```
- Instalar ionic 
npm install -g @ionic/cli

- Ejecutar Ionnic
ionic serve
ionic serve -l

- Crear nuevas páginas
ionic generate [carpera-x]/[nombre-x]

- Instalar Firebase
npm install firebase @angular/fire --save
npm install -g @ionic/cli native-run cordova-res

- Encriptación
npm install crypto-js

- Generar APK 
ionic cordova build android


```
## Credenciales 

- Firebase
![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/credenciales-firebase.png)


## Funcionalidad del Proyecto :pencil2:

- Se crea un proyecto acto seguido codificar el Loginy todos los demás pages y por último transformar a APK

| **Firebase Auth** :speech_balloon:| **Login** :speech_balloon: | **APK** :bust_in_silhouette: |
| ------------- | ------------- | ------------- | 
|![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/credenciales-firebase.png) |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/login-codigo.png) |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/apk-transform.png)  |![myimage-alt-tag]|

## Interfaces

La aplicación permite iniciar sesión, en el caso de contar con una cuenta previamente creada. 
Caso contrario el usuario puede crear una.
Una vez registrado puede ingresar al dashboard de chat donde puede conversar y compartir imagenes con amigos.


| **login** :speech_balloon: | **register** :bust_in_silhouette: | **chat** :scroll:|**imagenes compartidas** 📤|
| ------------- | ------------- | ------------- | ------------- |
|![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/login-usuario.png) |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/registro-usuario.png)  |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/chat-amigos.png)  |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/subir-archivos.png) |

## Código:
- Como primer paso creamos el proyecto y realizamos la conexión a FIREBASE.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/credenciales-firebase.png) 

- Siguiente generamos pages por ejemplo login, register, services, dashboard.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/componestes-generados.png)

- En el siguiente código se presenta el código usado en el pages login el cual fue modificado para que pida los campos de Email y Contraseña junto con dos botones que son para registrarse y el otro para entrar directamente si se tiene ya una cuenta previamente.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/login-codigo.png)

- En el siguiente pages de registro creamos las variables para almacenar la información el firebase y de esta manera se guarde para que el  usuario pueda logearse en la aplicación.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/registro-codigo.png)


- Esta pages lo que hace es presentar el panel de chat para los usuarios que ya estan registrados.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/chat-codigo.png)


- También se añadió imagenes las cuales son de ayuda para la interfaz del usuario.

![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/imagenes-chat.png)

-----------------------------
## Resultados ✔️
Los resultados son los siguientes:
- Ingresa a la APP
- Se registra
- Ingresa al login
- Ingresar al chat
- Compartir imágenes

| **Paso 1️⃣** :speech_balloon: | **Paso 2️⃣** :bust_in_silhouette: | **Paso 3️⃣** :clapper:|**Paso 4️⃣** :scroll:|
| ------------- | ------------- | ------------- | ------------- |
|![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/registro-usuario2.png) |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/login-usuario2.png)  |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/chat-amigos.png)  |![myimage-alt-tag](https://github.com/JESSICAAMOGUIMBA/Prueba1/blob/main/imagenes-readme/fin-chats2.png) |

## Video en Yotube :movie_camera:
 
- https://www.youtube.com/watch?v=U5f9ex2mDms&feature=youtu.be


### Referencias de ayuda ###
    1. https://www.youtube.com/watch?v=xgkwOBpU3ek
    2. https://ionicframework.com/docs/api/toolbar
    3. https://ionicons.com/
