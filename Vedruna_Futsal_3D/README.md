# Vedruna Futsal 3D - Android Studio Project
Temporada 2026-2027 | CFS Cal Xirricló Balaguer Vedruna A

## Estructura del Proyecto
- `app/src/main/java/com/vedruna/futsal/MainActivity.java`: Actividad principal Android con orientación horizontal y pantalla completa inmersiva.
- `app/src/main/assets/index.html`: Motor 3D completo con Three.js, físicas de balón, estadios de fútbol sala, plantilla de jugadores, controles táctiles con joystick virtual, botones de Chutar/Robar, Pasar, y Centrar/Entrada, además de modos de juego (Partido Rápido, Liga Benjamín, Entrenamiento, Torneo).
- `roster.json`: Plantilla oficial de jugadores y rivales sin dorsales inventados.

## Instrucciones para compilar y generar el APK:
1. Abrir Android Studio (Arctic Fox o superior).
2. Seleccionar **Open an Existing Project** y elegir esta carpeta raíz `Vedruna_Futsal_3D`.
3. Esperar a que Gradle sincronice las dependencias.
4. Conectar un dispositivo Android con la *Depuración USB* activada o iniciar un emulador con API 24+.
5. Hacer clic en **Build > Build Bundle(s) / APK(s) > Build APK(s)** o presionar el botón de **Run (▶)**.
6. El APK de depuración se generará en `app/build/outputs/apk/debug/app-debug.apk`.
