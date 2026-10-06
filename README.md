# RE3DC Launcher

**English** · [Español](#español)

RE3DC is *Resident Evil 3: Nemesis* (1999, PC) rebuilt from its decompiled code, running natively on modern Windows,
in English and Spanish, with optional HD textures and dubs. It is a non-commercial fan project, not affiliated with or
endorsed by Capcom.

**No game files are included.** You need **your own copy of Resident Evil 3 from GOG** (English and/or Spanish).
Nothing from Capcom, GOG, JuanchoTex HD or TTV is distributed here: the launcher checks your copies by their hashes
and builds everything on your PC.

## Download

Go to [**Releases**](../../releases) and download `RE3DC-…-setup.exe` (Windows 10/11, 64-bit, OpenGL 2.1).
It installs for your user only (no administrator rights) and adds an **RE3DC** shortcut. The executables are not
signed yet: if SmartScreen warns you, choose *More info → Run anyway*. Each release lists its SHA-256.

## How it works

Open **RE3DC**. The launcher has a big **PLAY** button at the top and a step-by-step wizard below:

1. **Your Resident Evil 3 from GOG** — found automatically in the usual GOG folders, or choose its folder or its
   offline installer. English, Spanish or both.
2. **Optional extras** — the HD textures and videos of *RE3 A.I. Overhaul 1.0 by JuanchoTex HD* (the `.7z` you
   downloaded from the author), the Castilian Spanish dub by TTV and REC (`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`, from
   [their site](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/)), and RE3DC's own content.
3. **Review** — what will be installed and the disk space it needs. Optionally, also save the package `.zip` for
   your other devices.
4. **Install** — every file is checked; then **PLAY** turns on.

The launcher is in English and Spanish (buttons at the top right). Uninstalling removes everything **except your
saved games**.

## What the launcher downloads

Only RE3DC's own content, from the [`recursos`](../../releases/tag/recursos) release of **this repository**. The
launcher and the game do not contact any other server, and there is no telemetry.

| Package | What it is |
|---|---|
| `la` (doblaje latino) | RE3DC's Latin American Spanish dub: our own voices, plus patches for the Spanish texts |
| `apartamento` | Jill's own room and building (new rooms made by RE3DC) |
| `boutique` | The PlayStation boutique restored: small script patches applied to your own game files |
| `jthdtextos-ia` | RE3DC's own images for the HD texts (title, warning, *YOU DIED*) |

## Credits

- HD textures and videos: **JuanchoTex HD (JTHD)**, *RE3 A.I. Overhaul 1.0*, built on RE:Enhance by SonicBOOM and
  TeamX's mask tools. You bring the author's download; RE3DC converts it on your PC.
- Castilian Spanish dub: **Traducciones del Tío Víctor and Resident Evil Castellano** (project by IlDucci). Fan-made
  and non-profit: it must not be sold, shared together with the game, or used to train or feed AI/TTS voices. RE3DC
  does not distribute it.
- Free software inside the installer: SDL2, FFmpeg, libwebp, Python, Pillow, numpy, OpenCV and others; their licenses
  are installed next to the program (`licencias\`, `THIRD_PARTY_NOTICES.md`, `motor.json`).

*Resident Evil* and *Biohazard* are trademarks of Capcom. This repository contains no source code and no Capcom
material: only this description, the installer and RE3DC's own content.

---

## Español

RE3DC es *Resident Evil 3: Nemesis* (1999, PC) reconstruido desde su código decompilado, nativo en el Windows de hoy,
en inglés y en español, con texturas HD y doblajes opcionales. Es un proyecto de fans sin ánimo de lucro, sin relación
con Capcom.

**No trae ningún archivo del juego.** Hace falta **tu copia de Resident Evil 3 de GOG** (en inglés y/o en español).
Aquí no se reparte nada de Capcom, de GOG, de JuanchoTex HD ni de TTV: el launcher comprueba tus copias por sus hashes
y lo arma todo en tu PC.

## Descarga

En [**Releases**](../../releases) baja `RE3DC-…-setup.exe` (Windows 10/11 de 64 bits, OpenGL 2.1). Se instala solo
para tu usuario (sin permisos de administrador) y deja un acceso **RE3DC**. Los ejecutables aún no están firmados: si
SmartScreen avisa, «Más información → Ejecutar de todas formas». Cada versión trae su SHA-256.

## Cómo funciona

Abre **RE3DC**. El launcher tiene arriba un botón grande de **JUGAR** y debajo un asistente paso a paso:

1. **Tu Resident Evil 3 de GOG**: lo busca solo en las carpetas habituales de GOG, o eliges su carpeta o su
   instalador offline. Inglés, español o los dos.
2. **Mejoras opcionales**: las texturas y vídeos HD de *RE3 A.I. Overhaul 1.0 de JuanchoTex HD* (el `.7z` que bajaste
   del autor), el doblaje castellano de TTV y REC (`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`, de
   [su web](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/)) y el contenido propio de RE3DC.
3. **Resumen**: qué se instala y cuánto espacio hace falta. Si quieres, guarda también el paquete `.zip` para tus otros
   dispositivos.
4. **Instalar**: se comprueba cada archivo y se activa **JUGAR**.

El launcher está en inglés y en español (botones arriba a la derecha). La desinstalación lo borra todo **menos tus
partidas**.

## Qué descarga el launcher

Solo el contenido propio de RE3DC, de la versión [`recursos`](../../releases/tag/recursos) de **este repositorio**. Ni
el launcher ni el juego se conectan a ningún otro servidor, y no hay telemetría.

| Paquete | Qué es |
|---|---|
| `la` (doblaje latino) | El doblaje latino de RE3DC: voces nuestras y parches de los textos en español |
| `apartamento` | La habitación propia de Jill y su edificio (salas nuevas hechas por RE3DC) |
| `boutique` | La boutique de PlayStation restaurada: pequeños parches de guion que se aplican a tus archivos |
| `jthdtextos-ia` | Las imágenes propias de RE3DC para los textos HD (título, advertencia, *HAS MUERTO*) |

## Créditos

- Texturas y vídeos HD: **JuanchoTex HD (JTHD)**, *RE3 A.I. Overhaul 1.0*, sobre RE:Enhance de SonicBOOM y las
  herramientas de máscaras de TeamX. Tú aportas la descarga del autor; RE3DC la convierte en tu PC.
- Doblaje castellano: **Traducciones del Tío Víctor y Resident Evil Castellano** (proyecto de IlDucci). Hecho por fans
  y sin ánimo de lucro: prohibido venderlo, repartirlo junto al juego o usar sus voces con IA o TTS. RE3DC no lo
  reparte.
- Software libre dentro del instalador: SDL2, FFmpeg, libwebp, Python, Pillow, numpy, OpenCV y otros; sus licencias se
  instalan junto al programa (`licencias\`, `THIRD_PARTY_NOTICES.md`, `motor.json`).

*Resident Evil* y *Biohazard* son marcas de Capcom. Este repositorio no contiene código fuente ni material de Capcom:
solo esta descripción, el instalador y el contenido propio de RE3DC.
