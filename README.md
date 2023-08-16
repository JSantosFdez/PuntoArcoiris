# Instrucciones de Gestión - Proyecto PuntoArcoiris

Este documento proporciona las instrucciones necesarias para gestionar y desarrollar el proyecto **PuntoArcoiris**. Este proyecto es el resultado de aplicar el Aprendizaje Servicio a un Trabajo de Fin de Grado (TFG) en el campo de la informática. El objetivo es crear un portal web de información destinado a personas LGBT+.

## Instalación y Configuración

Antes de empezar a trabajar con el proyecto, sigue estos pasos para descargar y configurar los archivos necesarios:

1. Clona el repositorio desde GitHub: `git clone https://github.com/tuusuario/PuntoArcoiris.git`
2. Accede al directorio del proyecto: `cd PuntoArcoiris`
4. Coloca todos los archivos `.z01` a `.z23` y el archivo `.zip` en el mismo directorio donde clonaste el repositorio.
5. Descomprime el archivo `.zip`. Esto debería generar la estructura del proyecto y permitirte acceder a los archivos necesarios.
6. Ejecuta el comando `npm install` para instalar las dependencias del proyecto.

## Compilación y Despliegue

Para compilar y desplegar el proyecto, sigue los siguientes pasos:

1. Ejecuta `ng build` para compilar los componentes y generar los archivos de distribución.
2. Los archivos compilados se encontrarán en la carpeta `dist/`. Puedes subir estos archivos a un servidor web para desplegar el proyecto. En este caso se hace uso del portal Netlify.

## Ejecución de Pruebas

El proyecto incluye pruebas unitarias que se pueden ejecutar utilizando Jasmine y Karma. Sigue estos pasos para ejecutar las pruebas:

1. Ejecuta `ng test` para lanzar las pruebas unitarias.
2. Los resultados de las pruebas se mostrarán en la terminal y te indicarán si las pruebas pasaron o fallaron.

## Ejecución en el Entorno de Desarrollo

Para realizar modificaciones de forma segura en la aplicación, puedes ejecutarla en tu entorno local utilizando el servidor de desarrollo. Sigue estos pasos:

1. Ejecuta `npm run start` para iniciar el servidor de desarrollo.
2. Abre tu navegador web y navega a `http://localhost:4200` para acceder a la aplicación en tiempo real.
3. Realiza tus modificaciones y la aplicación se actualizará automáticamente en el navegador.

## Acceso al Portal Web

Una vez que el proyecto esté compilado y desplegado, puedes acceder al portal web en la siguiente dirección: [https://puntoarcoiris.netlify.app/](https://puntoarcoiris.netlify.app/)

Este portal web proporciona información valiosa para personas LGBT+ y es el resultado de un esfuerzo colaborativo y de aprendizaje.

¡Gracias por contribuir al proyecto PuntoArcoiris! 
