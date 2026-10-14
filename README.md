# RE3DC Launcher

<p align="center">
  <a href="https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/RE3DC-setup.exe"><b>⬇ DOWNLOAD RE3DC FOR WINDOWS (installer)</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/RE3DC-setup.exe"><b>⬇ DESCARGAR RE3DC PARA WINDOWS (instalador)</b></a>
  <br><sub>Windows 10/11 · 64-bit · ~105 MB · always the latest version / siempre la última versión</sub>
  <br><br><b>Steam Deck / Linux</b> — in Desktop Mode, open Konsole and paste · <i>en el modo Escritorio, abre Konsole y pega</i>:
  <br><code>curl -fsSL https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/instalar-deck.sh | bash</code>
</p>

**English** · [Español](#español)

RE3DC is *Resident Evil 3: Nemesis* (1999, PC) rebuilt from its decompiled code, running natively on modern Windows
and on the Steam Deck / Linux, in English and Spanish, with optional HD textures and dubs. The decompilation was done by **Llamix Tec**
([YouTube](https://www.youtube.com/@Llamix-Tec)). It is a non-commercial fan project, not affiliated with or endorsed
by Capcom.

**No game files are included.** You need **your own copy of Resident Evil 3 from GOG** (English and/or Spanish).
Nothing from Capcom, GOG, JuanchoTex HD or TTV is distributed here: the launcher checks your copies by their hashes
and builds everything on your PC.

## What's new (game 0.2.13 · launcher 0.2.23)

- **JuanchoTex HD «1.1 fix2» recognized.** The launcher accepts `RE3 A.I. OVERHAUL 1.1 fix2 by JTHD.7z` (the 7z as the
  author gives it, or its folder) besides 1.1 and 1.0: it tells the version apart by its file names and sizes and says
  which one it found. The fix2 gives the same HD as 1.1. In *Downloads* it prefers fix2, then 1.1, then 1.0. The game
  doesn't change (0.2.13).

### Game 0.2.13 · launcher 0.2.22

- **Random zombies.** In START/F9 → *Models…*, the four zombie groups have a new option, **«Random (one per zombie)»**,
  and the row **«Zombies: all random»** sets all four at once: every zombie that appears gets one of the models you have
  for its type (1999, HD, Remake, each RE1 HD zombie) and keeps it while it lives. Off by default. Also in PS5 0.3.4 and
  the Android app 0.9.31.

### Launcher 0.2.21

- **Fixed «RE1 HD: the conversion failed (exit status 1)» on Windows in Spanish** (and other non-English Windows): the
  RE1 HD and RE3 (2020) characters steps no longer break when the tools print accented text.
- **Windows:** under «RE1 HD: Jill and characters» the launcher shows the Resident Evil HD REMASTER folder it found in
  Steam, with **«Change…»** to pick another one.

### Game 0.2.12 · launcher 0.2.20

- **The Remake Nemesis now shows up in the game** (1st and 2nd form) when you pick «Remake» for him; the Nemesis forms
  without a Remake model use the 1999 one. Also in PS5 0.3.3 and the Android app 0.9.30.

### Game 0.2.11 · launcher 0.2.19

- **The model viewer shows only the model in use**, including the **1999 Original read from your GOG copy**.
- **The RE3 (2020) Jill by default** if you built her (otherwise RE1 HD → HD → 1999); your own choices are kept.
- **The 17 RE1 HD zombies**, each on its own, the normal one by default (RE1 HD package 7: tick it again to rebuild).
- **No invisible weapons** (the 1999 one shows if a model doesn't carry it); the Mercenaries pistols with the Remake Jill.
- **PS5 is back:** [`ps5-0.3.2`](../../releases/tag/ps5-0.3.2) with the same game, prepared from the **PS5** tile (Windows
  and Steam Deck / Linux). Not tested on a console yet.
- Android app **0.9.29** with the same game.

### Game 0.2.10 · launcher 0.2.18

- **Model viewer, fixed:** «Original» shows the 1999 model itself (before it looked like HD), and the animations are a
  **list** with name and length; the chosen one plays by itself, in a loop (up / down choose).
- **Platform icons are back in the launcher:** the Steam Deck / Linux launcher has its *Other systems* row again
  (Android, PS5, Windows), and each launcher shows its own system in the header (Windows, Steam Deck or Linux).
- Android app **0.9.27** with the fixed viewer.

### Game 0.2.9 · launcher 0.2.17

- **Model and animation viewer** in the «Models…» panel (START / F9 → *Models…* → **A** on a row): the model in use next
  to the 1999 one, turning, with its data (triangles, textures, bones, GPU memory) and its animations — the rest pose, the
  last seconds of what that character did in the game (recorded) and the clips of the RE1 and Remake Jills. ◂ ▸ change
  the animation, A plays / pauses, LB / RB frame by frame or the speed, X / Y rotate, up / down zoom, B back.
- Android app **0.9.26** with the same viewer.

### Game 0.2.8 · launcher 0.2.16

- **«Models…» panel** in the in-game menu (START / F9): the model of each kind of character or enemy separately (Original,
  HD, Remake or RE1 HD and their variants), with *Reset* and *Save as default*.
- **RE1 HD:** the standard zombie (the Crimson Head is a separate choice) and a more natural skin tone for the RE1 Jill.
- **Android is back:** the *Android* tile on Windows (*For Android…* on the Steam Deck / Linux) prepares the app (0.9.25)
  and your complete package for your phone.

### Launcher 0.2.15

- **Install from a complete package (.zip)** (launcher 0.2.15): on the Steam Deck / Linux, a button on the start page finds
  an RE3DC complete package already built (in Downloads or on the microSD card), checks it and installs it. On Windows,
  *I already have an RE3DC complete package (.zip)* does the same.

- **Steam Deck and Linux are back**, with their own launcher that does everything on the Deck: it finds your copies,
  builds the packages, installs, has a big **PLAY** button and updates itself. **One command** to install it (see
  [Steam Deck and Linux](#steam-deck-and-linux)).
- **RE1 HD models** (optional, **off by default**): Jill (with the 1999 animations or with her own RE1 animations; with a
  special outfit, her S.T.A.R.S. uniform) and the zombies, Hunter, Cerberus, crow and spider of *Resident Evil HD
  REMASTER* (2015), made on your PC from **your own Steam copy**. New launcher checkbox *RE1 HD: Jill and characters*; in
  the game, *Options → Jill: RE1 Remake (1999 anim.) / RE1 Remake (RE1 anim.)* and *Options → Characters: RE1 HD*.
- **Choose where to install** (Windows): in the launcher's review step, *Change…* puts the game data on another folder
  or drive. What is already installed, with your saved games, is moved there.
- **Fewer crashes**: fixes for the 0.2.6 out-of-memory crashes (HD and Remake models that are not drawn for a while are
  unloaded, a failed sound buffer no longer crashes the game, a Remake model that does not fit falls back to the 1999
  one) and, to find the rest, the logs of the previous sessions and a crash dump are kept.
- Everything new starts **off**: the game starts like 0.2.6; turn things on in *Options*.

### Game 0.2.6 · launcher 0.2.13

- **16:9 camera panning** (like Fusion Fix): the picture fills a wide screen and follows Jill up and down; menus, the
  inventory and cutscenes go back to the whole 4:3 picture. On by default (*Options → Widescreen*).
- **Three Jills** (*Options → Jill*): **Original**; **HD**, the 1999 model smoothed with 4x textures, made on your PC
  from your own GOG copy; and **Remake**, the *Resident Evil 3 (2020)* model imported from **your own Steam copy**, with
  our animations and the weapon always in her hand.
- **HD characters** (*Options → Characters*): zombies, Carlos, Nikolai, Nemesis and the rest, the 1999 designs smoothed
  with the game's own lighting; and the **Remake characters**, the RE3 (2020) models moving with the original
  animations.
- Our own font for the title menu, the Options screen and the in-game menu (START), HD icons in inventory slots 7 and
  8, and «Back to the title» in the in-game menu.

> **Now on Windows, Steam Deck / Linux, Android and PS5** (jailbroken; 0.3.2–0.3.4 not yet tested on a console).

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
   downloaded from the author: 1.1 fix2, 1.1 or 1.0), his *Add-on Castellano* (Doblaje Spain), the Castilian Spanish dub by TTV and REC (`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`, from
   [their site](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/)), and RE3DC's own content.
   **Jill and characters:** *HD Jill (1999)* and *HD characters* are made from your GOG copy; *RE3 (2020) Jill* and
   *RE3 (2020) characters* need your **Steam copy of Resident Evil 3 (2020)**, and *RE1 HD: Jill and characters* your
   **Steam copy of Resident Evil HD REMASTER** (the launcher finds their folders).
3. **Review** — what will be installed, the disk space it needs and **where** (*Change…* to use another drive).
4. **Install** — every file is checked; then **PLAY** turns on.

The launcher is in English and Spanish (buttons at the top right). Uninstalling removes everything **except your
saved games**.

## Steam Deck and Linux

In **Desktop Mode**, open **Konsole** and paste:

```
curl -fsSL https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/instalar-deck.sh | bash
```

No password or `sudo` needed. It downloads the launcher, the game and the conversion tools (~190 MB, checked by their
SHA-256) to `~/RE3DC`, adds **RE3DC Launcher** to the applications menu and to your Steam library (*Non-Steam*). Open it
and press **Install RE3DC**: the same wizard as on Windows, with the controller, the touchscreen or a mouse. It finds
your Resident Evil 3 from GOG installed with **Heroic**, Lutris or Bottles (also on the microSD card), or its offline
installers in `Downloads`; the `.7z` extras in `Downloads`; and Resident Evil 3 (2020) / Resident Evil HD REMASTER in
your Steam library. Then **PLAY**, and **Add to Steam** to play it from Game Mode. The launcher updates itself from this
page. Works on any 64-bit Linux with glibc 2.35 or newer and SDL2.

Tip: choose the files in Desktop Mode (Game Mode has no file picker; the launcher finds what is in the usual places).

## Other systems

**Android:** install RE3DC on your PC or Steam Deck first, then press the *Android* tile (on Windows, and in *Other systems* on the Steam Deck / Linux): a `RE3DC-Android` folder
gets the app ([`android-0.9.31`](../../releases/tag/android-0.9.31), arm64, Android 8+), your complete package and a README with the three steps.
Since 0.9.28 the app has its **own launcher**: it can also install straight on the phone from your GOG folder or from the
GOG offline installer (`.exe` + `.bin`), from a complete or single package (.zip) or from a folder, with the options and
updates outside the game. Video tutorial (Spanish): https://www.youtube.com/watch?v=I44xCRiZbeg.

**PS5 (jailbroken):** the **PS5** tile (Windows, and *Other systems* on the Steam Deck / Linux) prepares the USB drive
with the title ([`ps5-0.3.4`](../../releases/tag/ps5-0.3.4)), your complete package and the copier; steps in `INSTALAR.md`.

## Files you need and where they usually are

| What | File / folder | Usual place |
|---|---|---|
| **Resident Evil 3 from GOG, English** (required, or the Spanish one) | the installed folder (with `ResidentEvil3.exe`, `Rofs1.dat` … `Rofs15.dat`, `zmovie\`) **or** its offline installer `setup_resident_evil_3_1.0_hotfix4_(86848).exe` + `…-1.bin` | `C:\GOG Games\Resident Evil 3` · `C:\Program Files (x86)\GOG Galaxy\Games\Resident Evil 3` · `Downloads` |
| **Resident Evil 3 from GOG, Spanish** (to play in Spanish) | **easiest:** the offline installer `setup_resident_evil_3_1.0_hotfix4_(spanish)_(86848).exe` + `…-1.bin` (the launcher extracts the Spanish copy, no install needed) **or** a folder installed **choosing «Español»** in the installer (it also has `Rofs16.dat`) | `Downloads` (GOG.com → your library → Resident Evil 3 → offline installers, Spanish) |
| HD textures | `RE3 A.I. OVERHAUL 1.1 fix2 by JTHD.7z` (or 1.1, 1.0) | `Downloads` |
| Spanish add-on (Doblaje Spain) | `RE3 ADD-ON CASTELLANO by JTHD.7z` | `Downloads` |
| Castilian dub (TTV) | `RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z` | `Downloads` |
| RE3 (2020) Jill and characters | your Steam **Resident Evil 3** (2020) folder (with `re_chunk_000.pak`) | `C:\Program Files (x86)\Steam\steamapps\common\RE3` |
| RE1 HD Jill and characters | your Steam **Resident Evil (biohazard HD REMASTER)** folder (with `bhd.exe` and `nativePC`) | `C:\Program Files (x86)\Steam\steamapps\common\Resident Evil Biohazard HD REMASTER` |
| On the Steam Deck / Linux | the same files | GOG: `~/Games/Heroic/…` (Heroic), the microSD card, `~/Downloads`; Steam: `~/.local/share/Steam/steamapps/common/…` or the microSD card |

> ⚠ GOG installers contain several languages: if you **install** the game, choose **«Español»** as the installer's
> language, otherwise you get the English copy again (in another folder). The launcher detects it and tells you.
> Don't extract the `.7z` files: give the launcher the `.7z` as it is.

## Where to get the optional extras

RE3DC never distributes them: download them from their authors.

- **JuanchoTex HD (HD textures and videos).** The download links are in the author's videos (description and pinned
  comment):
  - [Resident Evil 3 Nemesis A.I. Overhaul — Update 1.1](https://www.youtube.com/watch?v=3sUvsibhLOY)
  - [RE3 Add-on Castellano for A.I. Overhaul 1.1](https://www.youtube.com/watch?v=o0-zQJU04Lg)

  - **A.I. Overhaul 1.1 fix2** (`RE3 A.I. OVERHAUL 1.1 fix2 by JTHD.7z`, recommended), 1.1 or 1.0: put it in *HD textures*.
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
launcher and the game do not contact any other server and there is no telemetry.

| Package | What it is |
|---|---|
| `la` (doblaje latino) | RE3DC's Latin American Spanish dub: our own voices, plus patches for the Spanish texts |
| `apartamento` | Jill's own room and building (new rooms made by RE3DC) |
| `boutique` | The PlayStation boutique restored: small script patches applied to your own game files |
| `jthdtextos-ia` | RE3DC's own images for the HD texts (title, warning, *YOU DIED*) |

## Credits

- Decompilation, ports and launcher: **Llamix Tec** — YouTube channel:
  [youtube.com/@Llamix-Tec](https://www.youtube.com/@Llamix-Tec)
- HD textures and videos: **JuanchoTex HD (JTHD)**, *RE3 A.I. Overhaul 1.1 fix2* (and 1.1, 1.0), built on RE:Enhance by SonicBOOM and
  TeamX's mask tools. You bring the author's download; RE3DC converts it on your PC.
- Add-on Castellano: dub by **Doblaje Spain (JuanLuGames)**, translation by Leigiboy, HD text files by Danny.DMF,
  assembled by JuanchoTex HD. You bring the author's download; RE3DC only converts its voices and movies on your PC.
- Castilian Spanish dub: **Traducciones del Tío Víctor and Resident Evil Castellano** (project by IlDucci). Fan-made
  and non-profit: it must not be sold, shared together with the game, or used to train or feed AI/TTS voices. RE3DC
  does not distribute it.
- Free software inside the installer and the Steam Deck package: SDL2, FFmpeg, libwebp, Python, Pillow, numpy, OpenCV,
  innoextract and others; their licenses are installed next to the program (`licencias`, `THIRD_PARTY_NOTICES.md`,
  `motor.json`) and in each release (`THIRD_PARTY_NOTICES.md`).

*Resident Evil* and *Biohazard* are trademarks of Capcom. This repository contains no source code and no Capcom
material: only this description, the installer and RE3DC's own content.

---

## Español

RE3DC es *Resident Evil 3: Nemesis* (1999, PC) reconstruido desde su código decompilado, nativo en el Windows de hoy
y en la Steam Deck / Linux, en inglés y en español, con texturas HD y doblajes opcionales. La decompilación la hizo **Llamix Tec**
([YouTube](https://www.youtube.com/@Llamix-Tec)). Es un proyecto de fans sin ánimo de lucro, sin relación con Capcom.

**No trae ningún archivo del juego.** Hace falta **tu copia de Resident Evil 3 de GOG** (en inglés y/o en español).
Aquí no se reparte nada de Capcom, de GOG, de JuanchoTex HD ni de TTV: el launcher comprueba tus copias por sus hashes
y lo arma todo en tu PC.

## Novedades (juego 0.2.13 · launcher 0.2.23)

- **La JuanchoTex HD «1.1 fix2», reconocida.** El launcher acepta `RE3 A.I. OVERHAUL 1.1 fix2 by JTHD.7z` (el 7z tal
  cual lo da el autor, o su carpeta) además de la 1.1 y la 1.0: distingue la versión por los nombres y tamaños de sus
  ficheros y dice cuál encontró. La fix2 da el mismo HD que la 1.1. En *Descargas* prefiere la fix2, luego la 1.1 y luego
  la 1.0. El juego no cambia (0.2.13).

### Juego 0.2.13 · launcher 0.2.22

- **Zombis aleatorios.** En START/F9 → *Modelos…*, los cuatro grupos de zombis tienen una opción nueva, **«Aleatorio (uno
  por zombi)»**, y la fila **«Zombis: todos aleatorios»** pone los cuatro a la vez: a cada zombi que aparece le toca uno de
  los modelos que tengas para su tipo (1999, HD, Remake, cada zombi del RE1 HD) y se queda con él mientras vive. Apagado de
  serie. También en la PS5 0.3.4 y en la app de Android 0.9.31.

### Launcher 0.2.21

- **Arreglado «RE1 HD: la conversión falló (exit status 1)» en un Windows en español** (y en otros idiomas): las
  etapas del RE1 HD y de los personajes del RE3 (2020) ya no se rompen cuando las herramientas escriben tildes.
- **Windows:** debajo de «RE1 HD: Jill y personajes» se ve la carpeta de Resident Evil HD REMASTER que encontró en
  Steam, con **«Cambiar…»** para elegir otra.

### Juego 0.2.12 · launcher 0.2.20

- **El Nemesis del Remake ya se ve en el juego** (1.ª y 2.ª forma) al elegir «Remake» para él; las formas sin modelo del
  Remake usan la de 1999. También en la PS5 0.3.3 y en la app de Android 0.9.30.

### Juego 0.2.11 · launcher 0.2.19

- **El visor enseña solo el modelo en uso**, también el **Original de 1999 sacado de tu GOG**.
- **La Jill del Remake por defecto** si la armaste (si no, RE1 HD → HD → 1999); lo que tú elegiste se respeta.
- **Los 17 zombis del RE1 HD**, cada uno por separado, con el normal por defecto (paquete RE1 HD 7: vuelve a marcarlo).
- **Ningún arma invisible** (si el modelo no la trae, sale la de 1999); las pistolas de Mercenarios con la Jill del Remake.
- **Vuelve la PS5:** [`ps5-0.3.2`](../../releases/tag/ps5-0.3.2) con el mismo juego, preparada desde el mosaico **PS5**
  (Windows y Steam Deck / Linux). Aún sin probar en una consola.
- La app de Android **0.9.29**, con el mismo juego.

### Juego 0.2.10 · launcher 0.2.18

- **El visor de modelos, arreglado:** «Original» enseña el modelo de 1999 (antes se veía como el HD) y las animaciones son
  una **lista** con nombre y duración; la elegida se reproduce sola, en bucle (arriba / abajo eligen).
- **Vuelven los iconos de los sistemas al launcher:** el de la Steam Deck / Linux tiene otra vez su fila *Otros sistemas*
  (Android, PS5, Windows) y cada launcher enseña su propio sistema en la cabecera (Windows, Steam Deck o Linux).
- La app de Android **0.9.27**, con el visor arreglado.

### Juego 0.2.9 · launcher 0.2.17

- **Visor de modelos y animaciones** en el panel «Modelos…» (START / F9 → *Modelos…* → **A** sobre una fila): el modelo en
  uso junto al de 1999, girando, con sus datos (triángulos, texturas, huesos, memoria en la GPU) y sus animaciones —el
  reposo, los últimos segundos de lo que ese personaje hizo en la partida (grabado) y los clips de las Jill del RE1 y del
  Remake—. ◂ ▸ cambian de animación, A en marcha / pausa, LB / RB cuadro a cuadro o la velocidad, X / Y giran, arriba /
  abajo acercan, B vuelve.
- La app de Android **0.9.26**, con el mismo visor.

### Juego 0.2.8 · launcher 0.2.16

- **Panel «Modelos…»** en el menú de la partida (START / F9): el modelo de cada tipo de personaje o enemigo por separado
  (Original, HD, Remake o RE1 HD y sus variantes), con *Restablecer* y *Guardar como predeterminado*.
- **RE1 HD:** el zombi estándar (el Crimson Head, aparte) y un tono de piel más natural para la Jill del RE1.
- **Vuelve Android:** el mosaico *Android* en Windows (*Para Android…* en la Steam Deck / Linux) prepara la app (0.9.25) y
  tu paquete completo para el teléfono.

### Launcher 0.2.15

- **Instalar desde un paquete completo (.zip)** (launcher 0.2.15): en la Steam Deck / Linux, un botón en el inicio encuentra
  un paquete RE3DC completo ya armado (en Descargas o en la microSD), lo comprueba y lo instala. En Windows, *Ya tengo un
  paquete RE3DC completo (.zip)* hace lo mismo.

- **Vuelven la Steam Deck y Linux**, con su propio launcher que lo hace todo en la Deck: encuentra tus copias, arma los
  paquetes, instala, tiene un botón grande de **JUGAR** y se actualiza solo. Se instala con **un comando** (mira
  [Steam Deck y Linux](#steam-deck-y-linux)).
- **Modelos del RE1 HD** (opcionales, **apagados por defecto**): Jill (con las animaciones de 1999 o con sus propias
  animaciones del RE1; con un traje especial, su uniforme S.T.A.R.S.) y los zombis, el Hunter, el Cerberus, el cuervo y la
  araña de *Resident Evil HD REMASTER* (2015), hechos en tu PC desde **tu propia copia de Steam**. Casilla nueva en el
  launcher, *RE1 HD: Jill y personajes*; en el juego, *Opciones → Jill: RE1 Remake (anim. 1999) / RE1 Remake (anim. RE1)*
  y *Opciones → Personajes: RE1 HD*.
- **Elige dónde instalar** (Windows): en el resumen del launcher, *Cambiar…* pone los datos del juego en otra carpeta o
  unidad. Lo que ya tengas instalado, con tus partidas, se mueve allí.
- **Menos cierres**: arreglos de los cierres por falta de memoria de la 0.2.6 (los modelos HD y del Remake que llevan un
  rato sin dibujarse se descargan, un búfer de sonido que falla ya no cierra el juego, un modelo del Remake que no cabe
  vuelve al de 1999) y, para encontrar los que queden, se guardan los diarios de las sesiones anteriores y un volcado.
- Todo lo nuevo empieza **apagado**: el juego arranca como la 0.2.6; se enciende en *Opciones*.

### Juego 0.2.6 · launcher 0.2.13

- **Paneo de cámara 16:9** (como Fusion Fix): la imagen llena una pantalla ancha y sigue a Jill hacia arriba y hacia
  abajo; los menús, el inventario y las escenas vuelven al 4:3 entero. Encendido por defecto (*Opciones → Pantalla
  ancha*).
- **Tres Jill** (*Opciones → Jill*): la **Original**; la **HD**, el modelo de 1999 suavizado y con texturas a 4x, hecho en
  tu PC desde tu propia copia de GOG; y la del **Remake**, el modelo de *Resident Evil 3 (2020)* importado de **tu propia
  copia de Steam**, con nuestras animaciones y el arma siempre en la mano.
- **Personajes HD** (*Opciones → Personajes*): zombis, Carlos, Nikolai, Nemesis y los demás, con los diseños de 1999
  suavizados y la luz del propio juego; y los **personajes del Remake**, los modelos del RE3 (2020) con las animaciones
  originales.
- Letra propia en el menú del título, en Opciones y en el menú de la partida (START), iconos HD en las casillas 7 y 8 del
  inventario y «Volver al título» en el menú de la partida.

> **Ya en Windows, la Steam Deck / Linux, Android y PS5** (liberada; de la 0.3.2 a la 0.3.4, aún sin probar en una consola).

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
   del autor: la 1.1 fix2, la 1.1 o la 1.0), su *Add-on Castellano* (Doblaje Spain), el doblaje castellano de TTV y REC (`RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z`, de
   [su web](https://tiovictor.romhackhispano.org/resident-evil-3-nemesis/descargar/)) y el contenido propio de RE3DC.
   **Jill y personajes:** la *Jill HD (1999)* y los *personajes HD* se hacen desde tu copia de GOG; la *Jill del RE3
   (2020)* y los *personajes del RE3 (2020)* necesitan **tu copia de Steam de Resident Evil 3 (2020)**, y *RE1 HD: Jill y
   personajes*, **tu copia de Steam de Resident Evil HD REMASTER** (el launcher encuentra sus carpetas).
3. **Resumen**: qué se instala, cuánto espacio hace falta y **dónde** (*Cambiar…* para usar otra unidad).
4. **Instalar**: se comprueba cada archivo y se activa **JUGAR**.

El launcher está en inglés y en español (botones arriba a la derecha). La desinstalación lo borra todo **menos tus
partidas**.

## Steam Deck y Linux

En el **modo Escritorio**, abre **Konsole** y pega:

```
curl -fsSL https://github.com/carloxmario3/re3dc-launcher/releases/latest/download/instalar-deck.sh | bash
```

Sin contraseña ni `sudo`. Baja el launcher, el juego y las herramientas de conversión (~190 MB, comprobados por su
SHA-256) a `~/RE3DC`, añade **RE3DC Launcher** al menú de aplicaciones y a tu biblioteca de Steam (*No de Steam*). Ábrelo
y pulsa **Instalar RE3DC**: el mismo asistente que en Windows, con el mando, la pantalla táctil o un ratón. Encuentra tu
Resident Evil 3 de GOG instalado con **Heroic**, Lutris o Bottles (también en la microSD), o sus instaladores offline en
`Descargas`; las mejoras `.7z` en `Descargas`; y Resident Evil 3 (2020) / Resident Evil HD REMASTER en tu biblioteca de
Steam. Después **JUGAR**, y **Añadir a Steam** para jugarlo desde el modo Juego. El launcher se actualiza solo desde esta
página. Vale en cualquier Linux de 64 bits con glibc 2.35 o más nueva y SDL2.

Consejo: elige los archivos en el modo Escritorio (el modo Juego no tiene selector de archivos; el launcher encuentra lo
que está en los sitios de siempre).

## Otros sistemas

**Android:** instala RE3DC primero en tu PC o en tu Steam Deck y pulsa el mosaico *Android* (en Windows, y en *Otros
sistemas* en la Steam Deck / Linux): en una carpeta `RE3DC-Android` quedan la app ([`android-0.9.31`](../../releases/tag/android-0.9.31),
arm64, Android 8+), tu paquete completo y un LEEME con los tres pasos. Desde la 0.9.28 la app tiene su **propio
launcher**: también instala directamente en el teléfono desde la carpeta de tu GOG o desde su instalador offline (`.exe` +
`.bin`), desde un paquete completo o suelto (.zip) o desde una carpeta, con las opciones y las actualizaciones fuera del
juego. Tutorial en video: https://www.youtube.com/watch?v=I44xCRiZbeg.

**PS5 (liberada):** el mosaico **PS5** (en Windows, y en *Otros sistemas* en la Steam Deck / Linux) prepara el USB con el
título ([`ps5-0.3.4`](../../releases/tag/ps5-0.3.4)), tu paquete completo y el copiador; los pasos, en `INSTALAR.md`.

## Qué archivos hacen falta y dónde suelen estar

| Qué | Archivo / carpeta | Dónde suele estar |
|---|---|---|
| **Resident Evil 3 de GOG, inglés** (obligatorio, o el español) | la carpeta instalada (con `ResidentEvil3.exe`, `Rofs1.dat` … `Rofs15.dat`, `zmovie\`) **o** su instalador offline `setup_resident_evil_3_1.0_hotfix4_(86848).exe` + `…-1.bin` | `C:\GOG Games\Resident Evil 3` · `C:\Program Files (x86)\GOG Galaxy\Games\Resident Evil 3` · `Descargas` |
| **Resident Evil 3 de GOG, español** (para jugar en español) | **lo más fácil:** el instalador offline `setup_resident_evil_3_1.0_hotfix4_(spanish)_(86848).exe` + `…-1.bin` (el launcher saca de él la copia española, sin instalar nada) **o** una carpeta instalada **eligiendo «Español»** en el instalador (trae además `Rofs16.dat`) | `Descargas` (GOG.com → tu biblioteca → Resident Evil 3 → instaladores offline, español) |
| Texturas HD | `RE3 A.I. OVERHAUL 1.1 fix2 by JTHD.7z` (o la 1.1, la 1.0) | `Descargas` |
| Addon castellano (Doblaje Spain) | `RE3 ADD-ON CASTELLANO by JTHD.7z` | `Descargas` |
| Doblaje castellano (TTV) | `RE3_DOBLAJEESP_TTVyREC_1_1_PC_GOG.7z` | `Descargas` |
| Jill y personajes del RE3 (2020) | la carpeta de Steam de **Resident Evil 3** (2020) (con `re_chunk_000.pak`) | `C:\Program Files (x86)\Steam\steamapps\common\RE3` |
| Jill y personajes del RE1 HD | la carpeta de Steam de **Resident Evil (biohazard HD REMASTER)** (con `bhd.exe` y `nativePC`) | `C:\Program Files (x86)\Steam\steamapps\common\Resident Evil Biohazard HD REMASTER` |
| En la Steam Deck / Linux | los mismos archivos | GOG: `~/Games/Heroic/…` (Heroic), la microSD, `~/Downloads`; Steam: `~/.local/share/Steam/steamapps/common/…` o la microSD |

> ⚠ Los instaladores de GOG traen varios idiomas: si **instalas** el juego, elige **«Español»** en el idioma del
> instalador; si no, vuelves a tener la copia inglesa (en otra carpeta). El launcher lo detecta y te lo dice.
> No descomprimas los `.7z`: dale al launcher el `.7z` tal cual.

## Dónde conseguir las mejoras opcionales

RE3DC nunca las reparte: se bajan de sus autores.

- **JuanchoTex HD (texturas y vídeos HD).** Los enlaces de descarga están en los vídeos del autor (descripción y
  comentario fijado):
  - [Resident Evil 3 Nemesis A.I. Overhaul — Update 1.1](https://www.youtube.com/watch?v=3sUvsibhLOY)
  - [RE3 Add-on Castellano para A.I. Overhaul 1.1](https://www.youtube.com/watch?v=o0-zQJU04Lg)

  - **A.I. Overhaul 1.1 fix2** (`RE3 A.I. OVERHAUL 1.1 fix2 by JTHD.7z`, recomendada), la 1.1 o la 1.0: va en *Texturas HD*.
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
el launcher ni el juego se conectan a ningún otro servidor y no
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
- Texturas y vídeos HD: **JuanchoTex HD (JTHD)**, *RE3 A.I. Overhaul 1.1 fix2* (y la 1.1 y la 1.0), sobre RE:Enhance de SonicBOOM y las
  herramientas de máscaras de TeamX. Tú aportas la descarga del autor; RE3DC la convierte en tu PC.
- Add-on Castellano: doblaje de **Doblaje Spain (JuanLuGames)**, traducción de Leigiboy, textos HD de Danny.DMF,
  montado por JuanchoTex HD. Tú aportas la descarga del autor; RE3DC solo convierte sus voces y películas en tu PC.
- Doblaje castellano: **Traducciones del Tío Víctor y Resident Evil Castellano** (proyecto de IlDucci). Hecho por fans
  y sin ánimo de lucro: prohibido venderlo, repartirlo junto al juego o usar sus voces con IA o TTS. RE3DC no lo
  reparte.
- Software libre dentro del instalador y del paquete de la Steam Deck: SDL2, FFmpeg, libwebp, Python, Pillow, numpy,
  OpenCV, innoextract y otros; sus licencias se instalan junto al programa (`licencias`, `THIRD_PARTY_NOTICES.md`,
  `motor.json`) y van en cada versión (`THIRD_PARTY_NOTICES.md`).

*Resident Evil* y *Biohazard* son marcas de Capcom. Este repositorio no contiene código fuente ni material de Capcom:
solo esta descripción, el instalador y el contenido propio de RE3DC.
