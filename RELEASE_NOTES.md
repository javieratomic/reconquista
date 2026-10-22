# Reconquista TD 0.1.0-beta.2

> **El código fuente del juego NO está publicado.** Los enlaces «Source code
> (zip)» y «Source code (tar.gz)» los genera GitHub automáticamente y contienen
> únicamente documentación e imágenes del repositorio público. No contienen
> scripts ni el proyecto de Godot. Para jugar, utiliza el APK de Android o el ZIP
> de Windows de esta publicación.

Nueva beta para **Android ARM64** y **Windows x64**, centrada en legibilidad móvil
y un terreno visualmente más natural.

## Cambios

- Texto mayor en Android, adaptado a la densidad de pantalla.
- Menú más ancho y tarjetas de torres en dos filas, con nombres y costes legibles.
- Mejoras, pausa, tutorial, presentación de enemigos y resultados adaptados.
- Información enemiga amplia y con descripciones desplazables.
- Botones de victoria y derrota fijos y accesibles mientras se consulta el detalle.
- Suelo con variaciones suaves e irregulares, sin los discos claros de borde duro.
  Los indicadores de alcance y área de impacto se conservan.
- Contacto para permisos mediante Twitter/X
  [@jatomic007](https://twitter.com/jatomic007) o
  [abriendo una issue](https://github.com/javieratomic/reconquista/issues/new?title=Solicitud%20de%20permiso).

Sin cambios en estadísticas, recompensas, oleadas o geometría de rutas.
Consulta el [changelog completo](https://github.com/javieratomic/reconquista/blob/main/CHANGELOG.md).

## Archivos

- `reconquista-0.1.0-beta.2-android-arm64.apk`: Android 7.0+, dispositivos ARM64.
- `reconquista-0.1.0-beta.2-windows-x64.zip`: Windows 10/11 x64, versión portable.
- `SHA256SUMS.txt`: hashes de comprobación.
- `LICENSE.txt` y `THIRD_PARTY_NOTICES.md`: condiciones y avisos de terceros.

## Instalación

Android: actualiza la beta pública anterior instalando el APK **sin desinstalar**
el juego. Se conserva el mismo paquete y la misma firma de publicación.
Los APK antiguos de
pruebas usan otra firma; **no desinstales una build con partida para instalar esta
versión sin consultar antes cómo conservar tus datos**.

Windows: extrae la carpeta completa y ejecuta `Reconquista.exe`. No requiere Steam
ni una instalación de Godot. El ejecutable no lleva firma Authenticode.

## Estado de la beta

Pruebas de legibilidad a 420 y 480 DPI simulados, HUD, tarjetas, terreno,
compatibilidad de guardados y 9.360 posiciones de cámara. El Pixel 9a físico
todavía necesita validación de los usuarios. No se ha repetido una campaña
completa ni realizado un benchmark de rendimiento para esta beta.
Google Play, publicidad y compras reales no están conectados en esta versión.

El juego es gratuito para jugar; modificarlo o monetizarlo requiere permiso previo
por escrito a través de los canales indicados arriba. Consulta `LICENSE.txt`.
