
Este proyecto consiste en una aplicación móvil con integración de geolocalización en tiempo real que permite visualizar la ubicación de un dispositivo o usuario en un **mapa interactivo**
# Ubicador GPS con Alertas y Noticias en Mapa Interactivo

## Descripción del Proyecto.

Este proyecto consiste en una aplicación móvil con integración de geolocalización en tiempo real que permite visualizar la ubicación de un dispositivo o usuario en un **mapa interactivo**, emitir **alertas de seguimiento** (por ejemplo, si un usuario sale de una zona segura o se detecta movimiento inusual), y mostrar **últimas novedades** relevantes del entorno (como noticias locales, accidentes, o reportes de seguridad).

## Exposición del Problema.

En la actualidad, muchas personas desean conocer la ubicación de sus seres queridos en tiempo real o rastrear alguna mascota o mercancia que tenga mucho valor sentimental, pero también necesitan estar informadas del contexto geográfico en el que se mueven (novedades del entorno). Las apps actuales ofrecen geolocalización o noticias, pero no suelen integrarlas de manera funcional y visualmente accesible en un mismo mapa.

## Plataforma

- **Lenguaje:** Java
- **Entorno de desarrollo:** Android Studio
- **Geolocalización:** Google Maps SDK + Fused Location Provider
- **Backend:** Firebase (Realtime Database + Authentication)
- **Notificaciones:** Firebase Cloud Messaging (FCM)
- **Repositorio:** GitHub
- **Versionador:** Git

## Interfaz de Usuario (UI) e Interfaz de Administrador

### Usuario final:
- Ver su ubicación en tiempo real.
- Activar alertas personalizadas (zona segura, velocidad, etc.).
- Ver un feed de noticias geolocalizadas.
- Compartir ubicación con contactos.

## Funcionalidades

-  Mapa interactivo con Google Maps.
-  Seguimiento en tiempo real.
-  Alertas automáticas por salida de zona o actividad sospechosa.
-  Feed de novedades geográficas visibles en el mapa.
-  Compartir ubicación con familiares o grupos.
-  Notificaciones push.
-  Autenticación por correo o Google.

## Diseño 

Se planea incluir las siguientes pantallas (wireframes en `/diseño`):

1. **Pantalla de Inicio** – Botón para iniciar sesión o registrarse.
2. **Mapa Principal** – Vista de mapa con ubicación y noticias.
3. **Configuración de Alertas** – Definir zonas seguras, alertas.
4. **Panel de Noticias** – Feed con las novedades relevantes del entorno.
5. **Panel de Administración** – Solo para roles administradores.

> Wireframes diseñados en Figma. Se adjuntarán en formato PNG y PDF en la carpeta `/diseño`.

## Objetivo del Proyecto

Desarrollar una herramienta útil para padres, empresas, o individuos que desean combinar la **seguridad por rastreo GPS** con la **información del contexto** geográfico. Será una app enfocada en usabilidad, precisión de ubicación y notificaciones oportunas.

## Repositorio del Proyecto

https://github.com/Santiamejia/GPS_SLU

### Wiki del Proyecto

