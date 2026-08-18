# avaFAC — Instaladores

Este repositorio aloja **únicamente los instaladores publicados** de avaFAC (archivos `.msi`).

**Acá no está el código fuente.** avaFAC es software propietario de
[Avanzar Sistemas](https://avafac.com.ar); el código vive en un repositorio privado. Este repo
existe solo porque los archivos adjuntos de un repositorio privado exigen un token de GitHub para
descargarse, y la PC de un comercio tiene que poder bajar el instalador sin credenciales.

## Descargar

Andá a **[Releases](../../releases)** y bajá el `.msi` de la última versión.

La aplicación también avisa sola cuando hay una versión nueva (menú **Ayuda → Actualizaciones**).

## Instalación

**No instales por tu cuenta si tenés un sistema en producción.** La actualización de un local con
varias terminales tiene un orden (backup, servidor primero, después las terminales) y la hace el
soporte técnico.

Consultas: **Avanzar Sistemas — 03487 431170** · [avafac.com.ar](https://avafac.com.ar)

## Convención de publicación

| Elemento | Formato | Ejemplo |
|---|---|---|
| Tag | `vX.Y.Z` | `v2.0.7` |
| Título del release | `X.Y.Z` | `2.0.7` |
| Archivo adjunto | `avaFAC-X.Y.Z.msi` | `avaFAC-2.0.7.msi` |
| Cuerpo del release | Novedades en lenguaje de cliente | — |

El **cuerpo del release es el texto que lee el comercio** en el aviso de actualización dentro del
sistema: escribirlo como se le explicaría a un cajero, no como un changelog técnico.
