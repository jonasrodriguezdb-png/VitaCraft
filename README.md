# VitaCraft para PS Vita — versión de prueba 01.02

VitaCraft es una adaptación no oficial en C++ de un juego de bloques clásico para PS Vita. Esta versión para testers incluye controles de Vita, guía de botones, contador de FPS y efectos de sonido. Fue probada en una consola real; puede presentar errores gráficos o cierres.

## Descarga

Descargá `Minecraft.vpk` desde la sección [Releases](https://github.com/jonasrodriguezdb-png/VitaCraft/releases). Comprobá el SHA-256 con `SHA256SUMS.txt` si querés verificar el archivo.

## Instalación

1. Copiá 'Minecraft.vpk` a `ux0:data/` usando VitaShell.
2. Abrí el archivo en VitaShell y pulsá **X** para instalarlo. La aplicación actualiza versiones anteriores con el mismo identificador interno.
3. Antes de iniciar, comprobá que exista un `assets.pak` compatible en `ux0:data/vitacraft/`. Una instalación anterior en `ux0:data/vitacraft/` se migra automáticamente al primer inicio.

**El VPK no contiene `assets.pak`.** Los testers deben aportar su propio paquete de recursos compatible; este repositorio no distribuye archivos de Minecraft. Sin ese paquete, el juego no puede arrancar correctamente.

Los mods Java, incluido OptiFine, no funcionan en esta versión C++. Los paquetes `.ochpack` reconocidos van en `ux0:data/vitacraft/.minecraft/mods/`.

Discord: 
https://discord.gg/Qh72uKPeB
