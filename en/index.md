---
layout: default
lang: "en"
permalink: /en/
title: "Imperivm 1 HD and Mod - The Teuton Threat (Full HD Patch)"
description: "Download the mod «La Amenaza Teutón» (The Teuton Threat) and the Imperivm 1 Full HD patch for Imperivm - La Guerra de las Galias: new HD resolutions, better AI, units, random maps, multi-language support and Linux/Wine support."
banner_title: "Imperivm 1 - The Teuton Threat + Full HD Patch"
banner_tagline: "Imperivm 1 HD: the «La Amenaza Teutón» mod and the Full HD patch for Imperivm - La Guerra de las Galias. New HD resolutions, improved AI, units, maps, multi-language support and Linux/Wine support."
image: /capturas/AMENAZA_TEUTON.png
---

<p align="center">
    <img src="/capturas/AMENAZA_TEUTON.png" style="width: 75%;  max-width: 768px;" alt="The Teuton Threat artwork">
    <br>
    <b>Imperivm 1 - The Teuton Threat</b>
</p>

**Imperivm 1 HD** is a **mod** («La Amenaza Teutón», The Teuton Threat) and a **Full HD patch** for *Imperivm - La Guerra de las Galias* (Celtic Kings / Imperivm 1). It adds new **HD resolutions** up to 1920×1080, an **improved AI**, unit changes, random maps, **multi-language support** (Spanish, German, French, English and Italian) and support for playing on **Linux/Wine**.

## Downloads {#downloads}

[Download the mod](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Download Imperivm 1 HD (no mod)](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Download maps](https://github.com/JosueCA/La-Amenaza-Teuton)  

[Download on ModDB](https://www.moddb.com/members/sacredgames120)  

[Download Imperivm 2 HD](https://www.moddb.com/members/sacredgames120)  

---

## Adventure compatibility {#adventures}

This MOD is not 100% compatible with the adventures. To enjoy the original experience in Full HD, use the standalone patch for the game.

[Adventure compatibility](https://github.com/JosueCA/La-Amenaza-Teuton/blob/master/AdventuresMod/README.md)

## Table of contents {#toc}

1. [Installation notes](#install)
1. [Audio compatibility](#sec1)
1. [New HD screen resolutions](#sec2)
1. [Multi-language support](#sec3)
1. [General changes](#sec4)
1. [Random maps](#sec5)
1. [Unit changes](#sec6)
   - [Specialities](#specialities)
   - [Speciality visual effects](#visual-effects)
   - [Gaulish units](#gaul-units)
   - [Roman units](#roman-units)
   - [Teuton units](#teuton-units)
   - [Other units](#other-units)
   - [Heroes](#heroes)
1. [Gameplay improvements](#sec7)
   - [New «LAT» AI](#lat-ai)
   - [Stronghold](#stronghold)
   - [Roman Tavern](#tavern)
   - [Unit 'training' removed](#training)
   - [Formations](#formations)
   - [Druids and Magic](#magic)
   - [Teutons](#teutons)
   - [Catapults](#catapults)
   - [Villages](#villages)
   - [Outposts](#outposts)
   - [Animals](#animals)
   - [Other](#other)
1. [Winter biome fixes](#sec8)
1. [Player colours](#sec9)

---

## 1. Installation notes {#install}

This MOD is applied directly on top of an existing installation of "Imperivm 1: La Guerra de las Galias" (the Spanish release of Celtic Kings: Rage of War), replacing the .pak files and the other folders/files included in the zip.

<details class="pasos" markdown="1">
<summary>Step by step</summary>

1. Open the *Imperivm - La Guerra de las Galias* disc (or CD image) and run `Instalar.exe`.

   <img src="/capturas/install/zi1.png" class="paso" alt="Contents of the Imperivm disc with Instalar.exe selected" loading="lazy">

1. In the installer menu, click **OPCIONES** (options).

   <img src="/capturas/install/zi2.png" class="paso" alt="Imperivm installer menu" loading="lazy">

1. Choose the drive and the destination folder, then click **INSTALAR** (install).

   <img src="/capturas/install/zi3.png" class="paso" alt="Drive and destination folder selection" loading="lazy">

1. Confirm the installation path with **Aceptar** (OK).

   <img src="/capturas/install/zi4.png" class="paso" alt="Installation folder confirmation" loading="lazy">

1. Wait while the game files are copied.

   <img src="/capturas/install/zi5.png" class="paso" alt="File copy progress" loading="lazy">

1. Accept the **Microsoft DirectX 8.1** licence agreement with **Sí** (yes); it is required by the game.

   <img src="/capturas/install/zi6.png" class="paso" alt="Microsoft DirectX 8.1 licence agreement" loading="lazy">

1. When it finishes, the installer shows **JUGAR** (play): the game is installed. Close it with **SALIR** (exit).

   <img src="/capturas/install/zi7.png" class="paso" alt="Installer showing the JUGAR option after installing the game" loading="lazy">

1. Unzip the MOD over the game's installation folder, replacing the existing files.

</details>

On Linux/Wine, see also [Audio compatibility](#sec1).

## 2. Audio compatibility {#sec1}

### New audio engine {#audio-backend}

New audio engine with multiple interfaces support (WASAPI, DirectSound and WinMM). Enabled by default, with auto detection of interface. (Configurable in `config.ini`)

### Wine {#wine}

**Recent Wine versions don't need a separate 32-bit prefix. They support 32-bit and 64-bit in the same 64-bit prefix**

- **Wine**: WinXP 32-bit
- **Winetricks**
```
dmband
dmcompos
dmime
dmloader
dmscript
dmstyle
dmsynth
dmusic
dmusic32
dsound
dswave
directmusic
```

- **Audio codec conversion**: the unit voice files used the Microsoft ADPCM codec, which Wine does not fully support. **120+ voice WAV files** (Gauls, Romans and Teutons) were converted to standard PCM so they work correctly on Linux/Wine.
- Converted the audio files of the 'Celtic Kings Adventure' and 'Tutorial' adventures

## 3. New HD screen resolutions {#sec2}

| Resolution | Width | Height | Aspect |
|---|---|---|---|
| Res1 | 1024 | 768 | 4:3 |
| Res2 | 1152 | 864 | 4:3 |
| Res3 | 1280 | 720 | 16:9 |
| Res4 | 1280 | 800 | 16:10 |
| Res5 | 1280 | 1024 | 5:4 |
| Res6 | 1360 | 768 | 16:9 |
| Res7 | 1366 | 768 | 16:9 |
| Res8 | 1400 | 1050 | 4:3 |
| Res9 | 1440 | 900 | 16:10 |
| Res10 | 1600 | 900 | 16:9 |
| Res11 | 1600 | 1024 | 25:16 |
| Res12 | 1600 | 1050 | 32:21 |
| Res13 | 1600 | 1200 | 4:3 |
| Res14 | 1600 | 1280 | 5:4 |
| Res15 | 1680 | 1050 | 16:10 |
| Res16 | 1920 | 1080 | 16:9 |
| Res17 | 1920 | 1200 | 16:10 |

**Support for 1600px-1920px resolutions available from version "La Amenaza Teuton v0.4.0"**

## 4. Multi-language support {#sec3}
- Added German, French, English and Italian (in addition to Spanish). Configurable from the 'vxSettings.ini' file
- Fixed the volume of the English voices

## 5. General changes {#sec4}
- Music changes
- Small tweaks to the game interface
- Intro video replaced with the trailer (better quality)
- Improved game stability
- The unit health bar (toggled with the '~' key) is now limited to Heroes, and only for the player's own units

<p align="center">
    <img src="/capturas/captura_salud.png" style="width: 75%;  max-width: 768px;" alt="Health bar" loading="lazy">
</p>

- New game type 'Total war' (Elimination, but with recruitment multiplied by 5)
- New quick selection widget
<p align="center">
    <img src="/capturas/ui/widget-shorcut-zoomed.jpg" style="width: 75%;  max-height: 579px;" alt="Widget" loading="lazy">
</p>

## 6. Random maps {#sec5}
- Reworked random map generation
- Reused assets to generate more varied scenery
- Increased the scenery ratio
- Added more scenery objects that generate items
- Reduced the number of deer
- New scenery for villages, strongholds, outposts and Teuton camps
- Improved random placement of mountains over villages

<span id="galeria"></span>

<div class="galeria" markdown="0">
  <a href="#img-decorados1"><img src="/capturas/mapas/thumbs/captura_decorados_1.png" alt="Scenery 1" loading="lazy"></a>
  <a href="#img-decorados2"><img src="/capturas/mapas/thumbs/captura_decorados_2.png" alt="Scenery 2" loading="lazy"></a>
  <a href="#img-romecity"><img src="/capturas/mapas/thumbs/rome_city.png" alt="Roman city" loading="lazy"></a>
  <a href="#img-gaulcity"><img src="/capturas/mapas/thumbs/gaul_city.png" alt="Gaulish city" loading="lazy"></a>
  <a href="#img-outpost1"><img src="/capturas/mapas/thumbs/outpost1.png" alt="Outpost 1" loading="lazy"></a>
  <a href="#img-outpost2"><img src="/capturas/mapas/thumbs/outpost2.png" alt="Outpost 2" loading="lazy"></a>
  <a href="#img-village1"><img src="/capturas/mapas/thumbs/village1.png" alt="Village 1" loading="lazy"></a>
  <a href="#img-village2"><img src="/capturas/mapas/thumbs/village2.png" alt="Village 2" loading="lazy"></a>
  <a href="#img-village3"><img src="/capturas/mapas/thumbs/village3.png" alt="Village 3" loading="lazy"></a>
  <a href="#img-village4"><img src="/capturas/mapas/thumbs/village4.png" alt="Village 4" loading="lazy"></a>
  <a href="#img-village5"><img src="/capturas/mapas/thumbs/village5.png" alt="Village 5" loading="lazy"></a>
  <a href="#img-village6"><img src="/capturas/mapas/thumbs/village6.png" alt="Village 6" loading="lazy"></a>
</div>

<div class="lightbox" id="img-decorados1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_1.png" alt="Scenery 1" loading="lazy"></div>
<div class="lightbox" id="img-decorados2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_2.png" alt="Scenery 2" loading="lazy"></div>
<div class="lightbox" id="img-romecity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/rome_city.png" alt="Roman city" loading="lazy"></div>
<div class="lightbox" id="img-gaulcity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/gaul_city.png" alt="Gaulish city" loading="lazy"></div>
<div class="lightbox" id="img-outpost1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost1.png" alt="Outpost 1" loading="lazy"></div>
<div class="lightbox" id="img-outpost2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost2.png" alt="Outpost 2" loading="lazy"></div>
<div class="lightbox" id="img-village1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village1.png" alt="Village 1" loading="lazy"></div>
<div class="lightbox" id="img-village2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village2.png" alt="Village 2" loading="lazy"></div>
<div class="lightbox" id="img-village3"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village3.png" alt="Village 3" loading="lazy"></div>
<div class="lightbox" id="img-village4"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village4.png" alt="Village 4" loading="lazy"></div>
<div class="lightbox" id="img-village5"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village5.png" alt="Village 5" loading="lazy"></div>
<div class="lightbox" id="img-village6"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village6.png" alt="Village 6" loading="lazy"></div>

---

## 7. Unit changes {#sec6}

## Specialities {#specialities}

- The 'death blow' speciality no longer affects heroes
- Fixed the 'attack skill' speciality, which did not work

| Speciality | Value | Description |
|---|---|---|
| `attack skill` | +1 | Damage increases with every consecutive hit on the same target |
| `berserker` | 100 % | Damage increases as health is lost |
| `charge` | 600 % / 8 000 ms | Multiplies damage by 600% with an 8-second cooldown without attacking |
| `trample damage` | 50 % | The unit deals 50 % damage to nearby enemies |
| `spread damage` | 175 % | Damage increases the more wounded the target is |
| `spike damage` | 25 % | Returns 25% of the damage to the attacker. |
| `vampire blow` | 33 % | Recovers 33 % of the damage dealt as own health. |
| `death blow` | 33 % | When the target is below 33% health, the next attack kills it in one blow. |
| `freedom` | — | Cannot join heroes. |
| `defensive stand` | — | Resists the attacker's first blow |

---

## Speciality visual effects {#visual-effects}

| Speciality | Effect | Shown on | When it appears |
|---|---|---|---|
| `attack skill` | <img src="/capturas/feedbacks/Penetration.png" class="fbstrip" alt="Effect of attack skill" loading="lazy"> | Attacker | On every hit |
| `berserker` | <img src="/capturas/feedbacks/Rage.png" class="fbstrip" alt="Effect of berserker" loading="lazy"> | Attacker | On every hit |
| `charge` | <img src="/capturas/feedbacks/Charge.png" class="fbstrip" alt="Effect of charge" loading="lazy"> | Attacker | **Only** when the charge is reloaded |
| `trample damage` | <img src="/capturas/feedbacks/TripleStrike.png" class="fbstrip" alt="Effect of trample damage" loading="lazy"> | Attacker | On every hit |
| `spread damage` | <img src="/capturas/feedbacks/BleedingAttack.png" class="fbstrip" alt="Effect of spread damage" loading="lazy"> | Target | On every hit |
| `spike damage` | <img src="/capturas/feedbacks/SpikedArmor.png" class="fbstrip" alt="Effect of spike damage" loading="lazy"> | Defender | On every hit |
| `vampire blow` | <img src="/capturas/feedbacks/StaminaBoost.png" class="fbstrip" alt="Effect of vampire blow" loading="lazy"> | Attacker | On every hit |
| `death blow` | <img src="/capturas/feedbacks/Revenge.png" class="fbstrip" alt="Effect of death blow" loading="lazy"> | Target | **Only** on the killing blow |
| `defensive stand` | <img src="/capturas/feedbacks/DefensiveStand.png" class="fbstrip" alt="Effect of defensive stand" loading="lazy"> | Defender | **Only** on the attacker's first blow |

`freedom` is a passive ability and has no visual effect.

---

## Gaulish units {#gaul-units}

| Unit | Health | Attack | Attack type | Slash def. | Pierce def. | Speed | Range | Speciality |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Swordsman" loading="lazy"><span>Swordsman</span></span> | 160 | 10–18 | slash | 0 | 0 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Archer" loading="lazy"><span>Archer</span></span> | 100 | 6–10 | pierce | 0 | 0 | 80 | 400 | spread damage |
| <span class="unidad"><img src="/capturas/iconos/gaxeman.png" class="icono" alt="Axeman" loading="lazy"><span>Axeman</span></span> | 280 | 16–24 | slash | 2 | 0 | 80 | — | trample damage |
| <span class="unidad"><img src="/capturas/iconos/gspearman.png" class="icono" alt="Spearman" loading="lazy"><span>Spearman</span></span> | 300 | 16–24, x1.5 vs Cavalry | pierce | 6 | 6 | 80 | — | defensive stand, spread damage |
| <span class="unidad"><img src="/capturas/iconos/ghorseman.png" class="icono" alt="Horseman" loading="lazy"><span>Horseman</span></span> | 380 | 20–28 | slash | 0 | 0 | 140 | — | charge |
| <span class="unidad"><img src="/capturas/iconos/gwfighter.png" class="icono" alt="Woman Warrior" loading="lazy"><span>Woman Warrior</span></span> | 340 | 18–36 | slash | 0 | 8 | 80 | — | vampire blow |
| <span class="unidad"><img src="/capturas/iconos/gdruid.png" class="icono" alt="Druid" loading="lazy"><span>Druid</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/gvikinglord.png" class="icono" alt="Viking Lord" loading="lazy"><span>Viking Lord</span></span> | 3000 | 42–84 | slash | 6 | 6 | 80 | — | freedom, charge |
| <span class="unidad"><img src="/capturas/iconos/ieliteguard.png" class="icono" alt="Elite Guard" loading="lazy"><span>Elite Guard</span></span> | 350 | 18–28 | slash | 6 | 6 | 80 | — | defensive stand, attack skill |

---

## Roman units {#roman-units}

| Unit | Health | Attack | Attack type | Slash def. | Pierce def. | Speed | Range | Speciality |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Hastatus" loading="lazy"><span>Hastatus</span></span> | 200 | 13–17 | slash | 0 | 5 | 80 | — | defensive stand |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Archer" loading="lazy"><span>Archer</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | spread damage |
| <span class="unidad"><img src="/capturas/iconos/rgladiator.png" class="icono" alt="Gladiator" loading="lazy"><span>Gladiator</span></span> | 255 | 21–21 | pierce | 5 | 0 | 100 | — | spread damage |
| <span class="unidad"><img src="/capturas/iconos/rspearman.png" class="icono" alt="Principle" loading="lazy"><span>Principle</span></span> | 275 | 15–23, x1.5 vs Cavalry | slash | 7 | 15 | 80 | — | defensive stand, spike damage |
| <span class="unidad"><img src="/capturas/iconos/rhorseman.png" class="icono" alt="Scout" loading="lazy"><span>Scout</span></span> | 330 | 17–25 | slash | 3 | 3 | 140 | — | charge |
| <span class="unidad"><img src="/capturas/iconos/rpraetorian.png" class="icono" alt="Praetorian" loading="lazy"><span>Praetorian</span></span> | 475 | 27–47 | pierce | 7 | 7 | 80 | — | attack skill, death blow |
| <span class="unidad"><img src="/capturas/iconos/rpriest.png" class="icono" alt="Priest" loading="lazy"><span>Priest</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/rliberatus.png" class="icono" alt="Liberatus" loading="lazy"><span>Liberatus</span></span> | 300 | 30–30 | slash | 0 | 0 | 120 | — | berserker |
| <span class="unidad"><img src="/capturas/iconos/cwarelephant.png" class="icono" alt="War Elephant" loading="lazy"><span>War Elephant</span></span> | 2000 | 30–40 | slash | 10 | 10 | 60 | — | freedom, trample damage |

### War Elephant {#war-elephant}
- Ranged units deal x1.25 against War Elephants

---

## Teuton units {#teuton-units}

| Unit | Health | Attack | Attack type | Slash def. | Pierce def. | Speed | Range | Speciality |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/teutonarcher.png" class="icono" alt="Teuton Archer" loading="lazy"><span>Teuton Archer</span></span> | 200 | 8–18, x2 vs Mules | pierce | 0 | 0 | 160 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/teutonmetal.png" class="icono" alt="Teuton Raider" loading="lazy"><span>Teuton Raider</span></span> | 250 | 10–20, x2 vs Mules | slash | 0 | 0 | 160 | — | trample damage |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Teuton Gaul Archer" loading="lazy"><span>Teuton Gaul Archer</span></span> | 100 | 6–12 | pierce | 2 | 2 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Teuton Gaul Swordsman" loading="lazy"><span>Teuton Gaul Swordsman</span></span> | 240 | 10–18 | slash | 2 | 2 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Teuton Roman Archer" loading="lazy"><span>Teuton Roman Archer</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Teuton Roman Hastatus" loading="lazy"><span>Teuton Roman Hastatus</span></span> | 240 | 13–17 | slash | 3 | 3 | 80 | — | — |

### Teuton Archer {#teuton-archer}
- Configured the unit's 'taunt' animation

---

## Other units {#other-units}

| Unit | Health | Attack | Attack type | Slash def. | Pierce def. | Speed | Range | Speciality |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/imilitiaman.png" class="icono" alt="Militiaman" loading="lazy"><span>Militiaman</span></span> | 180 | 6–12 | slash | 4 | 0 | 80 | — | — |
| <span class="unidad"><img src="/capturas/iconos/iarcher.png" class="icono" alt="Archer" loading="lazy"><span>Archer</span></span> | 180 | 12–18 | pierce | 4 | 8 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/islinger.png" class="icono" alt="Slinger" loading="lazy"><span>Slinger</span></span> | 200 | 20–30 | pierce | 0 | 0 | 100 | 300 | — |
| <span class="unidad"><img src="/capturas/iconos/idefender.png" class="icono" alt="Defender" loading="lazy"><span>Defender</span></span> | 200 | 14–24 | pierce | 8 | 8 | 80 | — | defensive stand |
| <span class="unidad"><img src="/capturas/iconos/icavalry.png" class="icono" alt="Cavalry" loading="lazy"><span>Cavalry</span></span> | 240 | 20–30 | slash | 6 | 6 | 160 | — | charge |
| <span class="unidad"><img src="/capturas/iconos/imountaineer.png" class="icono" alt="Mountaineer" loading="lazy"><span>Mountaineer</span></span> | 400 | 24–48 | slash | 4 | 0 | 80 | — | freedom |
| <span class="unidad"><img src="/capturas/iconos/teutonwolf.png" class="icono" alt="Teuton Wolf" loading="lazy"><span>Teuton Wolf</span></span> | 400 | 22–26 | slash | 8 | 4 | 160 | — | charge, trample damage |

---

### Heroes {#heroes}
- Changes to the base hero stats (more health)
- More health per level
- Reused hero assets to generate more random heroes
<p align="center">
    <img src="/capturas/captura_heroes_1.png" style="width: 75%; max-width: 768px;" alt="Random heroes" loading="lazy">
</p>

- Heroes can order their assigned Druids/Priests to cast their spells
- Heroes can order their units to build a catapult
- NOTE: giving a new order from the hero cancels the previous catapult/spell order
<p align="center">
    <img src="/capturas/captura_heroe_hechizos.png" style="width: 75%; max-width: 768px;" alt="Heroes casting spells" loading="lazy">
</p>

- Changed random hero recruitment: it is now sequential with a random start, to maximise the variety of hero assets/sprites within a game.

## 8. Gameplay improvements {#sec7}

### New «LAT» AI {#lat-ai}
- Higher difficulty when playing against the AI
- Added an initial military strategy
- Added an initial scouting strategy
- Fixed specific cases in the siege algorithm that left armies stuck, unable to besiege the enemy stronghold
- Improved technology research algorithm. The AI researches the upgrades in the arena, tavern and temple
- Improved recruitment of special units
- Improved recruitment of military units
- Improved threat calculation and response
- Improved objective management, more aggressive AI
- Improved army monitoring and control system
- Improved army retreat system
- Improved army food supply system
- Improved teleport (cave) system
- Improved use of the ruins
- Improved item pickup and usage system
- Reimplemented food trading with the Gaulish outposts
<p align="center">
    <img src="/capturas/captura_ia_items_1.png" style="width: 75%;  max-width: 768px;" alt="Item system" loading="lazy">
</p>

### Stronghold {#stronghold}
- Fixed peasant animations in the Roman strongholds, and added the missing buildings
- Added legionary (Rome)/Gaulish archer (Gaul) to the peasant animations
- Tuned the attack parameters of towers and gates. Gates now also fire arrows.
- Added a notification when a technology finishes researching
- Altar spells can be cast from the forum (the altar is chosen at random)
<p align="center">
    <img src="/capturas/Captura_foro.png" style="width: 75%;  max-width: 768px;" alt="Spells from the forum" loading="lazy">
</p>

### Roman Tavern {#tavern}
- New 'Championships' technology
- Reworked the 'Import horses' technology

### Unit 'training' removed {#training}
- Barracks units are created at the 'training' level already researched
<p align="center">
    <img src="/capturas/captura_cuartel_1.png" style="width: 75%;  max-width: 768px;" alt="Training" loading="lazy">
</p>

### Formations {#formations}
- Reduced the 'radius' of units in formation. Units in formation stand closer together.
- Reworked formation layouts
<p align="center">
    <img src="/capturas/Captura_formaciones.png" style="width: 75%;  max-width: 768px;" alt="Formations" loading="lazy">
</p>

### Druids and Magic {#magic}
- Reduced spell damage
- Reimplemented the 'Poison Cloud' (priest) so it no longer harms friendly units
- Tweaks to the druid recruitment system
- The AI uses the altars during random games
- The AI uses spells in combat (Vampire Spirit, Poison Cloud)
<p align="center">
    <img src="/capturas/Captura6_ia_nube.png" style="width: 75%;  max-width: 768px;" alt="AI spells" loading="lazy">
</p>

### Teutons {#teutons}
- Improved AI of the Teuton armies
- Teutons can capture player strongholds
<p align="center">
    <img src="/capturas/Captura4.png" style="width: 75%;  max-width: 768px;" alt="The Teuton Threat" loading="lazy">
</p>

### Catapults {#catapults}
- Reduced the unit limit from 10 to 5

### Villages {#villages}
- Villages produce peasants automatically along with the food mules
- Fixed the bug where peasants/mules got stuck forever at the stronghold gates
- Improved village capture: a village can no longer be captured by capturing its 'houses'

### Outposts {#outposts}
- Added starting defenders to the outposts
<p align="center">
    <img src="/capturas/captura_fortines_1.png" style="width: 75%;  max-width: 768px;" alt="Gaulish outposts" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_fortines_2.png" style="width: 75%;  max-width: 768px;" alt="Outpost defenders" loading="lazy">
</p>

### Animals {#animals}
- Fixed the bug where deer got stuck at the map edges

### Other {#other}
- Fixed 'Handle Leak' messages in vx.log
- Fixed 'assets/interface/settlement icon' messages in vx.log
- Fixed BONUS.XML entries that randomly had no effect
- Fixed random crashes when loading maps
- Fixed a bug that caused maximum latency (limited by MaxTickSize) in multiplayer games when one of the peers' computer uptime was more than 24.86 days
- Fixed the skirmish UI setting the wrong nation on predefined maps when changing a player's position in the list
- Changed the editor's 'Water' brush so the 'Shift' action no longer modifies the height of nearby terrain
- Added bridge, camp and ruin decorations from Imperivm 2
- Improved stability in multiplayer games

## 9. Winter biome fixes {#sec8}
- Replaced the minimap images with the summer ones
- Reduced the exposure (brightness) of the winter terrain textures
<p align="center">
    <img src="/capturas/captura_mapa_invierno_1.png" style="width: 75%;  max-width: 768px;" alt="Winter map" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_decorados_inv_1.png" style="width: 75%;  max-width: 768px;" alt="Winter scenery" loading="lazy">
</p>

## 10. Player colours {#sec9}

Redesigned player colours to maximise the visual distinction between them and avoid interference.

| ID | Original colour | Original HEX | New colour | New HEX |
|---|---|---|---|---|
| id1 | ![](/capturas/colores/id1_old.png) | `#FF1717` | ![](/capturas/colores/id1.png) | `#FF2222` |
| id2 | ![](/capturas/colores/id2_old.png) | `#FFFF00` | ![](/capturas/colores/id2.png) | `#CCBB00` |
| id3 | ![](/capturas/colores/id3_old.png) | `#00FF00` | ![](/capturas/colores/id3.png) | `#00BB77` |
| id4 | ![](/capturas/colores/id4_old.png) | `#00E8E8` | ![](/capturas/colores/id4.png) | `#00E8E8` |
| id5 | ![](/capturas/colores/id5_old.png) | `#EDA0FF` | ![](/capturas/colores/id5.png) | `#007700` |
| id6 | ![](/capturas/colores/id6_old.png) | `#B6E686` | ![](/capturas/colores/id6.png) | `#9900CC` |
| id7 | ![](/capturas/colores/id7_old.png) | `#AE0000` | ![](/capturas/colores/id7.png) | `#FF8800` |
| id8 | ![](/capturas/colores/id8_old.png) | `#F99B20` | ![](/capturas/colores/id8.png) | `#66AA00` |
| id9 | ![](/capturas/colores/id9_old.png) | `#109B12` | ![](/capturas/colores/id9.png) | `#0099CC` |
| id10 | ![](/capturas/colores/id10_old.png) | `#0000F8` | ![](/capturas/colores/id10.png) | `#555555` |
| id11 | ![](/capturas/colores/id11_old.png) | `#C40DC6` | ![](/capturas/colores/id11.png) | `#FF44CC` |
| id12 | ![](/capturas/colores/id12_old.png) | `#9F9A00` | ![](/capturas/colores/id12.png) | `#CC0055` |
| id13 | ![](/capturas/colores/id13_old.png) | `#808080` | ![](/capturas/colores/id13.png) | `#111111` |

## And many more undocumented changes... {#more}
