# HelAnime — descargas

App para ver anime en español, con estilo de cómic. Este repositorio solo contiene las versiones publicadas;
la app las usa para actualizarse sola.

## Instalar

Descarga la última versión en [Releases](../../releases/latest):

| Plataforma | Archivo |
|---|---|
| Android 10 o superior (arm64) | `HelAnime-<versión>.apk` |
| Arch Linux | `helanime-<versión>-1-x86_64.pkg.tar.zst` → `sudo pacman -U helanime-*.pkg.tar.zst` |

Cada versión trae `SHA256SUMS` para comprobar los archivos: `sha256sum -c SHA256SUMS`.

## Actualizaciones

La app revisa este repositorio como mucho una vez al día y, si hay una versión nueva, la descarga, comprueba
su SHA-256 e inicia la instalación.
