# RE3DC Launcher

<p align="center">
  <a href="https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/RE3DC-setup.exe"><b>⬇ DOWNLOAD RE3DC FOR WINDOWS (installer)</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/RE3DC-setup.exe"><b>⬇ DESCARGAR RE3DC PARA WINDOWS (instalador)</b></a>
  <br><sub>Windows 10/11 · 64-bit · ~108 MB · always the latest version / siempre la última versión</sub>
</p>

**English** · [Español](#español)

RE3DC is *Resident Evil 3: Nemesis* (1999, PC) rebuilt from its decompiled code, running natively on modern Windows,
in English and Spanish, with optional HD textures and dubs. The decompilation was done by **Llamix Tec**
([YouTube](https://www.youtube.com/@Llamix-Tec)). It is a non-commercial fan project, not affiliated with or endorsed
by Capcom.

**No game files are included.** You need **your own copy of Resident Evil 3 from GOG** (English and/or Spanish).
Nothing from Capcom, GOG, JuanchoTex HD or TTV is distributed here: the launcher checks your copies by their hashes
and builds everything on your PC.

## Download

**[⬇ Download the installer (RE3DC-setup.exe)](https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/RE3DC-setup.exe)**
— always the latest version (Windows 10/11, 64-bit, OpenGL 2.1). Older versions and the SHA-256 are in
[**Releases**](../../releases). Once installed, the launcher updates itself. It installs for your user only (no administrator rights) and adds an **RE3DC** shortcut. The executables are not
signed yet: if SmartScreen warns you, choose *More info → Run anyway*. Each release lists its SHA-256.

## How it works

Open **RE3DC**. The launcher has a big **PLAY** button at the top and a step-by-step wizard below:

1. **Your Resident Evil 3 from GOG** — found automatically in the usual GOG folders, or choose its folder or its
   offline installer. English, Spanish or both.
2. **Optional extras** — the HD textures and videos of *RE3 A.I. Overhaul 1.1 by JuanchoTex HD* (the `.7z` you
   downloaded from the author; 1.0 also works), his *Add-on Castellano* (Doblaje Spain), the Castilian Spanish dub by TTV and REC (`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`, from
   [their site](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/)), and RE3DC's own content.
3. **Review** — what will be installed and the disk space it needs. Optionally, also save the package `.zip` for
   your other devices.
4. **Install** — every file is checked; then **PLAY** turns on.

The launcher is in English and Spanish (buttons at the top right). Uninstalling removes everything **except your
saved games**.

## Android

Install RE3DC on your PC first. Then, on the launcher's main screen, press **Android** (under «Prepare a package for
other systems»).

It creates a `RE3DC-Android` folder on your desktop with three things:
- **the app**: the APK, downloaded from the [`android-*` releases](../../releases) of this repository;
- **your `re3dc-completo.zip`**: rebuilt from what you have installed on the PC, with every file checked;
- **`LEEME-ANDROID.txt`**, with the steps.

Then:
1. Install the APK on your phone.
2. Copy the zip to the phone's Downloads folder.
3. Open RE3DC and choose **«Instalar el paquete completo»** (the app is in Spanish).

Requirements: an arm64 phone or tablet with Android 8 or newer. The app updates itself from this repository and
sends nothing anywhere. The zip contains your own game files: it is just for you, don't share it.

## PS5 (jailbroken consoles)

Install RE3DC on your PC first. Then, on the launcher's main screen, press **PS5** and pick your **exFAT USB drive**.

It puts on the drive:
- **the RE3DC title** in `homebrew\PPSA99330`, downloaded from the [`ps5-*` releases](../../releases) of this repository;
- **your `re3dc-completo.zip`** in `RE3DC-PS5`, rebuilt from what you have installed on the PC, with every file checked;
- **the copier** (`re3dc-copiador.elf`) and **`LEEME-PS5.txt`**, with the steps.

Then:
1. Plug the USB into the PS5 with the jailbreak loaded (etaHEN + kstuff, elfldr, FTP and ShadowMount+). The RE3DC
   title shows up in the menu.
2. In the launcher, press **Send the copier to the PS5**: it finds the console on your local network and the copier
   installs your package on it (a few minutes; it shows its progress on the TV).
3. Open RE3DC on the PS5. Always quit in order: START → «Quit the game», then close the title.

Tested on firmware 13.40. The title is GPL-3.0 (it uses ps5-opengl); its source is offered on request: see
`THIRD_PARTY_NOTICES.md` in the release. The zip contains your own game files: it is just for you, don't share it.

## Files you need and where they usually are

| What | File / folder | Usual place |
|---|---|---|
| **Resident Evil 3 from GOG, English** (required, or the Spanish one) | the installed folder (with `ResidentEvil3.exe`, `Rofs1.dat` … `Rofs15.dat`, `zmovie\`) **or** its offline installer `setup_resident_evil_3_1.0_hotfix4_(86848).exe` + `…-1.bin` | `C:\GOG Games\Resident Evil 3` · `C:\Program Files (x86)\GOG Galaxy\Games\Resident Evil 3` · `Downloads` |
| **Resident Evil 3 from GOG, Spanish** (to play in Spanish) | **easiest:** the offline installer `setup_resident_evil_3_1.0_hotfix4_(spanish)_(86848).exe` + `…-1.bin` (the launcher extracts the Spanish copy, no install needed) **or** a folder installed **choosing «Español»** in the installer (it also has `Rofs16.dat`) | `Downloads` (GOG.com → your library → Resident Evil 3 → offline installers, Spanish) |
| HD textures | `RE3 A.I. OVERHAUL 1.1 by JTHD.7z` (or 1.0) | `Downloads` |
| Spanish add-on (Doblaje Spain) | `RE3 ADD-ON CASTELLANO by JTHD.7z` | `Downloads` |
| Castilian dub (TTV) | `RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z` | `Downloads` |

> ⚠ GOG installers contain several languages: if you **install** the game, choose **«Español»** as the installer's
> language, otherwise you get the English copy again (in another folder). The launcher detects it and tells you.
> Don't extract the `.7z` files: give the launcher the `.7z` as it is.

## Where to get the optional extras

RE3DC never distributes them: download them from their authors.

- **JuanchoTex HD (HD textures and videos).** The download links are in the author's videos (description and pinned
  comment):
  - [Resident Evil 3 Nemesis A.I. Overhaul — Update 1.1](https://www.youtube.com/watch?v=3sUvsibhLOY)
  - [RE3 Add-on Castellano for A.I. Overhaul 1.1](https://www.youtube.com/watch?v=o0-zQJU04Lg)

  - **A.I. Overhaul 1.1** (`RE3 A.I. OVERHAUL 1.1 by JTHD.7z`, recommended) or 1.0: put it in *HD textures*.
  - **Add-on Castellano** (`RE3 ADD-ON CASTELLANO by JTHD.7z`): put it in *Spanish add-on* (needs your Spanish GOG copy).
    RE3DC takes its Spanish voices and dubbed movies by **Doblaje Spain (JuanLuGames)**; in the game, choose
    *Options → Voices → Spanish (Doblaje Spain)*. Its translation differs from the game's Spanish texts, so the dubbed
    lines have no subtitles.
- **Castilian Spanish dub by TTV and REC.** On
  [tiovictor.romhackhispano.org → Resident Evil 3 Nemesis → Descargas](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/),
  open the **MEGA** or **MEDIAFIRE** folder. It has one file per console; download **only the one that says `PC_GOG`**:

  | File in the folder | Download? |
  |---|---|
  | **`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`** (~129 MB) | ✅ **Yes: this is the one for RE3DC** |
  | `…_DC_PAL.7z`, `…_NGC_PACKHD.7z`, `…_NGC_PAL.7z`, `…_PSX_NTSCU_DUAL.7z`, `…_PSX_PAL.7z` | ❌ No (Dreamcast, GameCube, PlayStation) |
  | `Leeme … v1.1.txt`, `LICENSE.TXT` | Optional: the authors' readme and license |

  Don't extract it: give the launcher the `.7z` as it is (box *Castilian dub*).

## What the launcher downloads

Only RE3DC's own content, from the [`recursos`](../../releases/tag/recursos) release of **this repository**. The
launcher and the game do not contact any other server (except your own PS5 on your local network, when you ask), and there is no telemetry.

| Package | What it is |
|---|---|
| `la` (doblaje latino) | RE3DC's Latin American Spanish dub: our own voices, plus patches for the Spanish texts |
| `apartamento` | Jill's own room and building (new rooms made by RE3DC) |
| `boutique` | The PlayStation boutique restored: small script patches applied to your own game files |
| `jthdtextos-ia` | RE3DC's own images for the HD texts (title, warning, *YOU DIED*) |

## Credits

- Decompilation, ports and launcher: **Llamix Tec** — YouTube channel:
  [youtube.com/@Llamix-Tec](https://www.youtube.com/@Llamix-Tec)
- HD textures and videos: **JuanchoTex HD (JTHD)**, *RE3 A.I. Overhaul 1.1* (and 1.0), built on RE:Enhance by SonicBOOM and
  TeamX's mask tools. You bring the author's download; RE3DC converts it on your PC.
- Add-on Castellano: dub by **Doblaje Spain (JuanLuGames)**, translation by Leigiboy, HD text files by Danny.DMF,
  assembled by JuanchoTex HD. You bring the author's download; RE3DC only converts its voices and movies on your PC.
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
en inglés y en español, con texturas HD y doblajes opcionales. La decompilación la hizo **Llamix Tec**
([YouTube](https://www.youtube.com/@Llamix-Tec)). Es un proyecto de fans sin ánimo de lucro, sin relación con Capcom.

**No trae ningún archivo del juego.** Hace falta **tu copia de Resident Evil 3 de GOG** (en inglés y/o en español).
Aquí no se reparte nada de Capcom, de GOG, de JuanchoTex HD ni de TTV: el launcher comprueba tus copias por sus hashes
y lo arma todo en tu PC.

## Descarga

**[⬇ Descargar el instalador (RE3DC-setup.exe)](https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/RE3DC-setup.exe)**
— siempre la última versión (Windows 10/11 de 64 bits, OpenGL 2.1). Las versiones anteriores y el SHA-256 están en
[**Releases**](../../releases). Una vez instalado, el launcher se actualiza solo. Se instala solo
para tu usuario (sin permisos de administrador) y deja un acceso **RE3DC**. Los ejecutables aún no están firmados: si
SmartScreen avisa, «Más información → Ejecutar de todas formas». Cada versión trae su SHA-256.

## Cómo funciona

Abre **RE3DC**. El launcher tiene arriba un botón grande de **JUGAR** y debajo un asistente paso a paso:

1. **Tu Resident Evil 3 de GOG**: lo busca solo en las carpetas habituales de GOG, o eliges su carpeta o su
   instalador offline. Inglés, español o los dos.
2. **Mejoras opcionales**: las texturas y vídeos HD de *RE3 A.I. Overhaul 1.1 de JuanchoTex HD* (el `.7z` que bajaste
   del autor; la 1.0 también vale), su *Add-on Castellano* (Doblaje Spain), el doblaje castellano de TTV y REC (`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`, de
   [su web](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/)) y el contenido propio de RE3DC.
3. **Resumen**: qué se instala y cuánto espacio hace falta. Si quieres, guarda también el paquete `.zip` para tus otros
   dispositivos.
4. **Instalar**: se comprueba cada archivo y se activa **JUGAR**.

El launcher está en inglés y en español (botones arriba a la derecha). La desinstalación lo borra todo **menos tus
partidas**.

## Android

Primero instala RE3DC en tu PC. Después, en la pantalla principal del launcher, pulsa **Android** (en «Preparar
paquete para otros sistemas»).

Se crea una carpeta `RE3DC-Android` en tu escritorio con tres cosas:
- **la app**: el APK, bajado de las versiones [`android-*`](../../releases) de este repositorio;
- **tu `re3dc-completo.zip`**: rearmado con lo que tienes instalado en el PC, comprobando cada archivo;
- **`LEEME-ANDROID.txt`**, con los pasos.

Luego:
1. Instala el APK en el teléfono.
2. Copia el zip a Descargas del teléfono.
3. Abre RE3DC y elige **«Instalar el paquete completo»**.

Requisitos: un teléfono o tableta arm64 con Android 8 o superior. La app se actualiza sola desde este repositorio y
no manda nada a ningún sitio. El zip lleva tus archivos del juego: es solo para ti, no lo compartas.

## PS5 (consolas liberadas)

Primero instala RE3DC en tu PC. Después, en la pantalla principal del launcher, pulsa **PS5** y elige tu **USB en
exFAT**.

En el USB deja:
- **el título RE3DC** en `homebrew\PPSA99330`, bajado de las [versiones `ps5-*`](../../releases) de este repositorio;
- **tu `re3dc-completo.zip`** en `RE3DC-PS5`, rearmado con lo que tienes instalado en el PC, con cada archivo comprobado;
- **el copiador** (`re3dc-copiador.elf`) y **`LEEME-PS5.txt`**, con los pasos.

Después:
1. Conecta el USB a la PS5 con el jailbreak cargado (etaHEN + kstuff, elfldr, FTP y ShadowMount+). El título RE3DC
   aparece en el menú.
2. En el launcher, pulsa **Mandar el copiador a la PS5**: encuentra la consola en tu red local y el copiador instala
   tu paquete en ella (unos minutos; muestra el avance en la tele).
3. Abre RE3DC en la PS5. Sal siempre en orden: START → «Salir del juego» y después cierra el título.

Probado en el firmware 13.40. El título es GPL-3.0 (usa ps5-opengl); su código fuente se entrega a quien lo pida: mira
`THIRD_PARTY_NOTICES.md` en la versión. El zip lleva tus propios archivos del juego: es solo para ti, no lo compartas.

## Qué archivos hacen falta y dónde suelen estar

| Qué | Archivo / carpeta | Dónde suele estar |
|---|---|---|
| **Resident Evil 3 de GOG, inglés** (obligatorio, o el español) | la carpeta instalada (con `ResidentEvil3.exe`, `Rofs1.dat` … `Rofs15.dat`, `zmovie\`) **o** su instalador offline `setup_resident_evil_3_1.0_hotfix4_(86848).exe` + `…-1.bin` | `C:\GOG Games\Resident Evil 3` · `C:\Program Files (x86)\GOG Galaxy\Games\Resident Evil 3` · `Descargas` |
| **Resident Evil 3 de GOG, español** (para jugar en español) | **lo más fácil:** el instalador offline `setup_resident_evil_3_1.0_hotfix4_(spanish)_(86848).exe` + `…-1.bin` (el launcher saca de él la copia española, sin instalar nada) **o** una carpeta instalada **eligiendo «Español»** en el instalador (trae además `Rofs16.dat`) | `Descargas` (GOG.com → tu biblioteca → Resident Evil 3 → instaladores offline, español) |
| Texturas HD | `RE3 A.I. OVERHAUL 1.1 by JTHD.7z` (o la 1.0) | `Descargas` |
| Addon castellano (Doblaje Spain) | `RE3 ADD-ON CASTELLANO by JTHD.7z` | `Descargas` |
| Doblaje castellano (TTV) | `RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z` | `Descargas` |

> ⚠ Los instaladores de GOG traen varios idiomas: si **instalas** el juego, elige **«Español»** en el idioma del
> instalador; si no, vuelves a tener la copia inglesa (en otra carpeta). El launcher lo detecta y te lo dice.
> No descomprimas los `.7z`: dale al launcher el `.7z` tal cual.

## Dónde conseguir las mejoras opcionales

RE3DC nunca las reparte: se bajan de sus autores.

- **JuanchoTex HD (texturas y vídeos HD).** Los enlaces de descarga están en los vídeos del autor (descripción y
  comentario fijado):
  - [Resident Evil 3 Nemesis A.I. Overhaul — Update 1.1](https://www.youtube.com/watch?v=3sUvsibhLOY)
  - [RE3 Add-on Castellano para A.I. Overhaul 1.1](https://www.youtube.com/watch?v=o0-zQJU04Lg)

  - **A.I. Overhaul 1.1** (`RE3 A.I. OVERHAUL 1.1 by JTHD.7z`, recomendada) o la 1.0: va en *Texturas HD*.
  - **Add-on Castellano** (`RE3 ADD-ON CASTELLANO by JTHD.7z`): va en *Addon castellano* (necesita tu GOG en español).
    RE3DC toma sus voces y películas dobladas al castellano por **Doblaje Spain (JuanLuGames)**; en el juego, elige
    *Opciones → Voces → Castellano (Doblaje Spain)*. Su traducción no es la de los textos en español del juego, así
    que lo doblado va sin subtítulos.
- **Doblaje castellano de TTV y REC.** En
  [tiovictor.romhackhispano.org → Resident Evil 3 Nemesis → Descargas](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/),
  entra en la carpeta de **MEGA** o de **MEDIAFIRE**. Hay un archivo por consola; baja **solo el que dice `PC_GOG`**:

  | Archivo de la carpeta | ¿Bajarlo? |
  |---|---|
  | **`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`** (~129 MB) | ✅ **Sí: este es el de RE3DC** |
  | `…_DC_PAL.7z`, `…_NGC_PACKHD.7z`, `…_NGC_PAL.7z`, `…_PSX_NTSCU_DUAL.7z`, `…_PSX_PAL.7z` | ❌ No (Dreamcast, GameCube, PlayStation) |
  | `Leeme … v1.1.txt`, `LICENSE.TXT` | Opcional: el léeme y la licencia de los autores |

  No lo descomprimas: dale al launcher el `.7z` tal cual (casilla *Doblaje castellano*).

## Qué descarga el launcher

Solo el contenido propio de RE3DC, de la versión [`recursos`](../../releases/tag/recursos) de **este repositorio**. Ni
el launcher ni el juego se conectan a ningún otro servidor (salvo a tu propia PS5 en tu red local, cuando lo pides), y no
hay telemetría.

| Paquete | Qué es |
|---|---|
| `la` (doblaje latino) | El doblaje latino de RE3DC: voces nuestras y parches de los textos en español |
| `apartamento` | La habitación propia de Jill y su edificio (salas nuevas hechas por RE3DC) |
| `boutique` | La boutique de PlayStation restaurada: pequeños parches de guion que se aplican a tus archivos |
| `jthdtextos-ia` | Las imágenes propias de RE3DC para los textos HD (título, advertencia, *HAS MUERTO*) |

## Créditos

- Decompilación, ports y launcher: **Llamix Tec** — canal de YouTube:
  [youtube.com/@Llamix-Tec](https://www.youtube.com/@Llamix-Tec)
- Texturas y vídeos HD: **JuanchoTex HD (JTHD)**, *RE3 A.I. Overhaul 1.1* (y la 1.0), sobre RE:Enhance de SonicBOOM y las
  herramientas de máscaras de TeamX. Tú aportas la descarga del autor; RE3DC la convierte en tu PC.
- Add-on Castellano: doblaje de **Doblaje Spain (JuanLuGames)**, traducción de Leigiboy, textos HD de Danny.DMF,
  montado por JuanchoTex HD. Tú aportas la descarga del autor; RE3DC solo convierte sus voces y películas en tu PC.
- Doblaje castellano: **Traducciones del Tío Víctor y Resident Evil Castellano** (proyecto de IlDucci). Hecho por fans
  y sin ánimo de lucro: prohibido venderlo, repartirlo junto al juego o usar sus voces con IA o TTS. RE3DC no lo
  reparte.
- Software libre dentro del instalador: SDL2, FFmpeg, libwebp, Python, Pillow, numpy, OpenCV y otros; sus licencias se
  instalan junto al programa (`licencias\`, `THIRD_PARTY_NOTICES.md`, `motor.json`).

*Resident Evil* y *Biohazard* son marcas de Capcom. Este repositorio no contiene código fuente ni material de Capcom:
solo esta descripción, el instalador y el contenido propio de RE3DC.
