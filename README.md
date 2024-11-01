# Proyecto de Reserva de Canchas de Fútbol

Este proyecto es una aplicación Flutter para la gestión de reservas de canchas de fútbol, que permite a los usuarios registrarse, iniciar sesión y realizar reservas de canchas de manera eficiente. La aplicación está conectada a un backend en PHP y utiliza una base de datos MySQL.

## Tabla de Contenidos

- [Características](#características)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [Ejecución del Proyecto](#ejecución-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Características

- Registro y autenticación de usuarios.
- Reserva de canchas de fútbol.
- Verificación de disponibilidad de canchas.
- Edición y eliminación de reservas existentes.
- Interfaz de usuario intuitiva.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalados los siguientes programas:

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Visual Studio Code](https://code.visualstudio.com/)
- [XAMPP](https://www.apachefriends.org/index.html) o un servidor PHP compatible.
- [Android Studios](https://developer.android.com/studio?hl=es-419)

## Instalación

1. **Clona el repositorio:**

   Abre la terminal y ejecuta el siguiente comando:

   ```bash
   git clone https://tu-repositorio.git

2. **Navega a la carpeta del proyecto:**
    ```bash
    cd nombre-del-proyecto

3. **Instala las dependencias:**
   Ejecuta el siguiente comando para instalar todas las dependencias necesarias:
    ```bash
    flutter pub get

4. **Configura el backend:**
- Asegúrate de tener XAMPP instalado y ejecutándose.
- Crea una base de datos llamada reserva_cancha en phpMyAdmin.
- Importa el archivo SQL proporcionado (si está disponible) para crear las tablas necesarias.

## Ejecución del Proyecto
1. **Inicia el servidor PHP:**
- Asegúrate de que el servidor XAMPP esté ejecutándose y que el módulo Apache esté activado.
2. **Configura las URL del backend:**
- Abre el archivo de configuración de tu aplicación (generalmente en lib/config.dart o similar) y verifica que las URLs del backend apunten correctamente a tu servidor.
3. **Ejecuta la aplicación:**
- Conéctate a tu emulador o dispositivo físico.
- En la terminal, ejecuta el siguiente comando:
  ```bash
  flutter run
Esto iniciará la aplicación en el emulador o dispositivo conectado.

## Tecnologías Utilizadas
- Frontend: Flutter
- Backend: PHP
- Base de datos: MySQL
- IDE: Visual Studio Code
