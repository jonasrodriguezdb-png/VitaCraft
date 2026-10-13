# VitaCraft para PS Vita — versión de prueba 01.02

VitaCraft es una adaptación no oficial en C++ de un juego de bloques clásico para PS Vita. Esta versión para testers incluye controles de Vita, guía de botones, contador de FPS y efectos de sonido. Fue probada en una consola real; puede presentar errores gráficos o cierres.

## Descarga

Descargá `VitaCraft.vpk` desde la sección [Releases](https://github.com/jonasrodriguezdb-png/VitaCraft/releases). Comprobá el SHA-256 con `SHA256SUMS.txt` si querés verificar el archivo.

## Instalación

1. Copiá `VitaCraft.vpk` a `ux0:data/` usando VitaShell.
2. Abrí el archivo en VitaShell y pulsá **X** para instalarlo. La aplicación actualiza versiones anteriores con el mismo identificador interno.
3. Antes de iniciar, comprobá que exista un `assets.pak` compatible en `ux0:data/vitacraft/`. Una instalación anterior en `ux0:data/opticraft/` se migra automáticamente al primer inicio.

**El VPK no contiene `assets.pak`.** Los testers deben aportar su propio paquete de recursos compatible; este repositorio no distribuye archivos de Minecraft. Sin ese paquete, el juego no puede arrancar correctamente.

Los mods Java, incluido OptiFine, no funcionan en esta versión C++. Los paquetes `.ochpack` reconocidos van en `ux0:data/vitacraft/.minecraft/mods/`.

## Informar fallos

Abrí un [Issue](https://github.com/jonasrodriguezdb-png/VitaCraft/issues) con el modelo de Vita, versión de firmware, pasos para reproducir, mensaje de error y, si existe, el archivo de crash. No adjuntes `assets.pak`, APK ni otros datos comerciales del juego.

## Licencia y créditos

El ejecutable deriva de [OptiCraft-Vita de DrDecki](https://github.com/DrDecki/OptiCraft-Vita) y se distribuye bajo GPLv2. Consultá [LICENSE](LICENSE) y la [oferta de código fuente](SOURCE-OFFER.md). Este repositorio publica archivos de prueba y documentación; el código correspondiente está disponible mediante solicitud según esa oferta.

VitaCraft no está afiliado a Mojang Studios, Microsoft ni Sony.
