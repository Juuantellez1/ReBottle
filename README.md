# ReBottle

ReBottle es una aplicación móvil Android desarrollada en Kotlin con Jetpack Compose.

La aplicación busca apoyar procesos de recolección y gestión de residuos, permitiendo que los usuarios programen recolecciones, que los recolectores gestionen solicitudes y rutas, y que las empresas REP consulten información relacionada con cumplimiento y reportes.

## Objetivo

El objetivo del proyecto es crear una plataforma móvil que conecte usuarios, recolectores y empresas responsables de procesos de recolección, facilitando la programación, seguimiento y registro de entregas.

## Roles del sistema

La aplicación maneja diferentes tipos de usuario.

### Usuario

El usuario puede:

- Registrarse e iniciar sesión.
- Programar una recolección.
- Consultar solicitudes activas.
- Revisar su historial.
- Consultar recompensas y puntos.
- Gestionar su perfil.

### Recolector

El recolector puede:

- Consultar solicitudes pendientes.
- Visualizar puntos y rutas en el mapa.
- Iniciar una ruta hacia una solicitud.
- Registrar una entrega.
- Registrar información como lugar y peso.
- Tomar una fotografía.
- Simular el escaneo de un código QR.
- Gestionar su perfil.

### Empresa REP

La empresa puede consultar funcionalidades relacionadas con:

- Reportes certificados.
- Cumplimiento REP.
- Porcentajes de materiales recolectados.
- Avance frente a metas.
- Generación y descarga de certificados.

## Tecnologías utilizadas

- Kotlin
- Android Studio
- Jetpack Compose
- Material Design 3
- Firebase Authentication
- Firebase Realtime Database
- Google Maps
- Google Maps Compose
- Google Directions API
- Retrofit
- Gson
- Moshi
- Kotlin Coroutines
- StateFlow
- ViewModel
- Coil
- Lottie

## Arquitectura general

La aplicación está organizada en diferentes capas:

```text
Usuario
   ↓
Jetpack Compose UI
   ↓
ViewModels
   ↓
Repositorios / servicios
   ↓
Firebase / Google Maps APIs
