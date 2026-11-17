# Golpe Franco — proyecto Android listo para compilar

Este proyecto ya trae el juego dentro (app/src/main/assets/www/index.html). Solo hay que compilarlo.

## Opción A — Android Studio (computador)
1. Abre Android Studio -> File -> Open -> elige esta carpeta.
2. Espera a que termine la sincronización de Gradle.
3. Build -> Build Bundle(s) / APK(s) -> Build APK(s).
4. El APK queda en app/build/outputs/apk/debug/app-debug.apk. Pásalo al celular e instálalo
   (permite "instalar apps desconocidas" cuando el celular lo pida).

## Opción B — GitHub (sin instalar nada)
1. Crea un repositorio nuevo en github.com y sube TODO el contenido de esta carpeta
   (incluida la carpeta oculta .github).
2. Entra en la pestaña Actions, abre la ejecución "Build APK" y espera a que termine (unos minutos).
3. Abajo, en "Artifacts", descarga "golpe-franco-android-apk": dentro está app-debug.apk.

Nota: este proyecto se preparó sin poder compilarlo en el equipo donde se creó. Si Gradle muestra
un error, envíame el texto del error y lo corrijo.
