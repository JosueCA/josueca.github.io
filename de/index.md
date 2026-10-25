---
layout: default
lang: "de"
permalink: /de/
title: "Imperivm 1 HD und Mod - Die Teutonen-Bedrohung (Full-HD-Patch)"
description: "Lade den Mod «La Amenaza Teutón» (Die Teutonen-Bedrohung) und den Full-HD-Patch für Imperivm - La Guerra de las Galias herunter: neue HD-Auflösungen, bessere KI, Einheiten, Zufallskarten, Mehrsprachigkeit und Linux/Wine-Unterstützung."
banner_title: "Imperivm 1 - Die Teutonen-Bedrohung + Full-HD-Patch"
banner_tagline: "Imperivm 1 HD: der Mod «La Amenaza Teutón» und der Full-HD-Patch für Imperivm - La Guerra de las Galias. Neue HD-Auflösungen, verbesserte KI, Einheiten, Karten, Mehrsprachigkeit und Linux/Wine-Unterstützung."
image: /capturas/AMENAZA_TEUTON.png
---

<p align="center">
    <img src="/capturas/AMENAZA_TEUTON.png" style="width: 75%;  max-width: 768px;" alt="Artwork Die Teutonen-Bedrohung">
    <br>
    <b>Imperivm 1 - Die Teutonen-Bedrohung</b>
</p>

**Imperivm 1 HD** ist ein **Mod** («La Amenaza Teutón», Die Teutonen-Bedrohung) und ein **Full-HD-Patch** für *Imperivm - La Guerra de las Galias* (Celtic Kings / Imperivm 1). Er fügt neue **HD-Auflösungen** bis 1920×1080, eine **verbesserte KI**, Änderungen an Einheiten, Zufallskarten, **Mehrsprachigkeit** (Spanisch, Deutsch, Französisch, Englisch und Italienisch) sowie Unterstützung für **Linux/Wine** hinzu.

## Downloads {#downloads}

[Mod herunterladen](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Imperivm 1 HD herunterladen (ohne Mod)](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Karten herunterladen](https://github.com/JosueCA/La-Amenaza-Teuton)  

[Auf ModDB herunterladen](https://www.moddb.com/members/sacredgames120)  

[Imperivm 2 HD herunterladen](https://www.moddb.com/members/sacredgames120)  

---

## Kompatibilität mit den Abenteuern {#adventures}

Dieser MOD ist nicht zu 100 % mit den Abenteuern kompatibel. Für das Originalerlebnis in Full HD den eigenständigen Patch für das Spiel verwenden.

[Kompatibilität mit den Abenteuern](https://github.com/JosueCA/La-Amenaza-Teuton/blob/master/AdventuresMod/README.md)

## Inhaltsverzeichnis {#toc}

1. [Installationshinweise](#install)
1. [Audio-Kompatibilität](#sec1)
1. [Neue HD-Bildschirmauflösungen](#sec2)
1. [Mehrsprachigkeit](#sec3)
1. [Allgemeine Änderungen](#sec4)
1. [Zufallskarten](#sec5)
1. [Änderungen an Einheiten](#sec6)
   - [Fähigkeiten](#specialities)
   - [Visuelle Effekte der Fähigkeiten](#visual-effects)
   - [Gallische Einheiten](#gaul-units)
   - [Römische Einheiten](#roman-units)
   - [Teutonische Einheiten](#teuton-units)
   - [Andere Einheiten](#other-units)
   - [Helden](#heroes)
1. [Spielverbesserungen](#sec7)
   - [Neue KI «LAT»](#lat-ai)
   - [Festung](#stronghold)
   - [Römische Taverne](#tavern)
   - ['Ausbildung' der Einheiten entfernt](#training)
   - [Formationen](#formations)
   - [Druiden und Magie](#magic)
   - [Teutonen](#teutons)
   - [Katapulte](#catapults)
   - [Dörfer](#villages)
   - [Vorposten](#outposts)
   - [Tiere](#animals)
   - [Sonstiges](#other)
1. [Korrekturen am Winter-Biom](#sec8)
1. [Spielerfarben](#sec9)

---

## 1. Installationshinweise {#install}

Dieser MOD wird direkt über eine bestehende Installation von "Imperivm 1: La Guerra de las Galias" (der spanischen Fassung von Celtic Kings: Rage of War) gelegt und ersetzt die .pak-Dateien sowie die übrigen im ZIP enthaltenen Ordner/Dateien.

<details class="pasos" markdown="1">
<summary>Schritt für Schritt</summary>

1. Die Disc (oder das CD-Image) von *Imperivm - La Guerra de las Galias* öffnen und `Instalar.exe` ausführen.

   <img src="/capturas/install/zi1.png" class="paso" alt="Inhalt der Imperivm-Disc mit ausgewählter Instalar.exe" loading="lazy">

1. Im Menü des Installers auf **OPCIONES** (Optionen) klicken.

   <img src="/capturas/install/zi2.png" class="paso" alt="Menü des Imperivm-Installers" loading="lazy">

1. Laufwerk und Zielordner wählen und auf **INSTALAR** (installieren) klicken.

   <img src="/capturas/install/zi3.png" class="paso" alt="Auswahl von Laufwerk und Zielordner" loading="lazy">

1. Den Installationspfad mit **Aceptar** (OK) bestätigen.

   <img src="/capturas/install/zi4.png" class="paso" alt="Bestätigung des Installationsordners" loading="lazy">

1. Warten, bis die Spieldateien kopiert sind.

   <img src="/capturas/install/zi5.png" class="paso" alt="Fortschritt beim Kopieren der Dateien" loading="lazy">

1. Den Lizenzvertrag von **Microsoft DirectX 8.1** mit **Sí** (ja) annehmen; er wird vom Spiel benötigt.

   <img src="/capturas/install/zi6.png" class="paso" alt="Lizenzvertrag von Microsoft DirectX 8.1" loading="lazy">

1. Am Ende zeigt der Installer **JUGAR** (spielen): Das Spiel ist installiert. Mit **SALIR** (beenden) schließen.

   <img src="/capturas/install/zi7.png" class="paso" alt="Installer mit der Option JUGAR nach der Installation" loading="lazy">

1. Das ZIP des MODs über den Installationsordner des Spiels entpacken und die vorhandenen Dateien ersetzen.

</details>

Unter Linux/Wine außerdem [Audio-Kompatibilität](#sec1) beachten.

## 2. Audio-Kompatibilität {#sec1}

### Neue Audio-Engine {#audio-backend}

Neue Audio-Engine mit Unterstützung mehrerer Schnittstellen (WASAPI, DirectSound und WinMM). Standardmäßig aktiviert, mit automatischer Erkennung der Schnittstelle. (Konfigurierbar in `config.ini`)

### Wine {#wine}

**Aktuelle Wine-Versionen benötigen kein separates 32-Bit-Präfix. Sie unterstützen 32 und 64 Bit im selben 64-Bit-Präfix**

- **Wine**: WinXP 32 Bit
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

- **Umwandlung des Audio-Codecs**: Die Sprachdateien der Einheiten verwendeten den Microsoft-ADPCM-Codec, den Wine nicht vollständig unterstützt. **Über 120 WAV-Sprachdateien** (Gallier, Römer und Teutonen) wurden in Standard-PCM umgewandelt, damit sie unter Linux/Wine korrekt funktionieren.
- Audiodateien der Abenteuer 'Celtic Kings Adventure' und 'Tutorial' umgewandelt

## 3. Neue HD-Bildschirmauflösungen {#sec2}

| Auflösung | Breite | Höhe | Seitenverhältnis |
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

**Unterstützung für Auflösungen von 1600px bis 1920px ab Version "La Amenaza Teuton v0.4.0"**

## 4. Mehrsprachigkeit {#sec3}
- Deutsch, Französisch, Englisch und Italienisch hinzugefügt (zusätzlich zu Spanisch). Einstellbar über die Datei 'vxSettings.ini'
- Lautstärke der englischen Sprachausgabe korrigiert

## 5. Allgemeine Änderungen {#sec4}
- Änderungen an der Musik
- Kleine Anpassungen an der Spieloberfläche
- Intro-Video durch den Trailer ersetzt (bessere Qualität)
- Stabilität des Spiels verbessert
- Die Lebensleiste der Einheiten (Taste '~') ist jetzt auf Helden beschränkt, und nur für die eigenen Einheiten

<p align="center">
    <img src="/capturas/captura_salud.png" style="width: 75%;  max-width: 768px;" alt="Lebensleiste" loading="lazy">
</p>

- Neuer Spielmodus 'Total war' (Vernichtung, aber mit fünffacher Rekrutierung)
- Neues Schnellauswahl-Widget
<p align="center">
    <img src="/capturas/ui/widget-shorcut-zoomed.jpg" style="width: 75%;  max-height: 579px;" alt="Widget" loading="lazy">
</p>

## 6. Zufallskarten {#sec5}
- Überarbeitete Erzeugung von Zufallskarten
- Assets wiederverwendet, um abwechslungsreichere Landschaften zu erzeugen
- Anteil der Landschaftsobjekte erhöht
- Mehr Landschaftsobjekte, die Gegenstände erzeugen
- Anzahl der Hirsche verringert
- Neue Landschaften für Dörfer, Festungen, Vorposten und Teutonenlager
- Zufällige Platzierung von Bergen über Dörfern verbessert

<span id="galeria"></span>

<div class="galeria" markdown="0">
  <a href="#img-decorados1"><img src="/capturas/mapas/thumbs/captura_decorados_1.png" alt="Landschaft 1" loading="lazy"></a>
  <a href="#img-decorados2"><img src="/capturas/mapas/thumbs/captura_decorados_2.png" alt="Landschaft 2" loading="lazy"></a>
  <a href="#img-romecity"><img src="/capturas/mapas/thumbs/rome_city.png" alt="Römische Stadt" loading="lazy"></a>
  <a href="#img-gaulcity"><img src="/capturas/mapas/thumbs/gaul_city.png" alt="Gallische Stadt" loading="lazy"></a>
  <a href="#img-outpost1"><img src="/capturas/mapas/thumbs/outpost1.png" alt="Vorposten 1" loading="lazy"></a>
  <a href="#img-outpost2"><img src="/capturas/mapas/thumbs/outpost2.png" alt="Vorposten 2" loading="lazy"></a>
  <a href="#img-village1"><img src="/capturas/mapas/thumbs/village1.png" alt="Dorf 1" loading="lazy"></a>
  <a href="#img-village2"><img src="/capturas/mapas/thumbs/village2.png" alt="Dorf 2" loading="lazy"></a>
  <a href="#img-village3"><img src="/capturas/mapas/thumbs/village3.png" alt="Dorf 3" loading="lazy"></a>
  <a href="#img-village4"><img src="/capturas/mapas/thumbs/village4.png" alt="Dorf 4" loading="lazy"></a>
  <a href="#img-village5"><img src="/capturas/mapas/thumbs/village5.png" alt="Dorf 5" loading="lazy"></a>
  <a href="#img-village6"><img src="/capturas/mapas/thumbs/village6.png" alt="Dorf 6" loading="lazy"></a>
</div>

<div class="lightbox" id="img-decorados1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_1.png" alt="Landschaft 1" loading="lazy"></div>
<div class="lightbox" id="img-decorados2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_2.png" alt="Landschaft 2" loading="lazy"></div>
<div class="lightbox" id="img-romecity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/rome_city.png" alt="Römische Stadt" loading="lazy"></div>
<div class="lightbox" id="img-gaulcity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/gaul_city.png" alt="Gallische Stadt" loading="lazy"></div>
<div class="lightbox" id="img-outpost1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost1.png" alt="Vorposten 1" loading="lazy"></div>
<div class="lightbox" id="img-outpost2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost2.png" alt="Vorposten 2" loading="lazy"></div>
<div class="lightbox" id="img-village1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village1.png" alt="Dorf 1" loading="lazy"></div>
<div class="lightbox" id="img-village2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village2.png" alt="Dorf 2" loading="lazy"></div>
<div class="lightbox" id="img-village3"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village3.png" alt="Dorf 3" loading="lazy"></div>
<div class="lightbox" id="img-village4"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village4.png" alt="Dorf 4" loading="lazy"></div>
<div class="lightbox" id="img-village5"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village5.png" alt="Dorf 5" loading="lazy"></div>
<div class="lightbox" id="img-village6"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village6.png" alt="Dorf 6" loading="lazy"></div>

---

## 7. Änderungen an Einheiten {#sec6}

## Fähigkeiten {#specialities}

- Die Fähigkeit 'Todesstoß' wirkt nicht mehr gegen Helden
- Die Fähigkeit 'Angriffsfertigkeit' korrigiert, sie funktionierte nicht

| Fähigkeit | Wert | Beschreibung |
|---|---|---|
| `Angriffsfertigkeit/attack skill` | +1 | Der Schaden steigt mit jedem weiteren Treffer auf dasselbe Ziel |
| `Berserker/berserker` | 100 % | Der Schaden steigt, je mehr Leben verloren geht |
| `Atempause/charge` | 600 % / 8 000 ms | Vervielfacht den Schaden um 600 %, mit 8 Sekunden Abklingzeit ohne Angriff |
| `Rundumschlag/trample damage` | 50 % | Die Einheit fügt nahen Gegnern 50 % Schaden zu |
| `Angemessener Schaden/spread damage` | 175 % | Der Schaden steigt, je stärker das Ziel verwundet ist |
| `Vergeltungsschlag/spike damage` | 25 % | Gibt 25 % des Schadens an den Angreifer zurück. |
| `Vampirschlag/vampire blow` | 33 % | Stellt 33 % des zugefügten Schadens als eigenes Leben wieder her. |
| `Todesstoß/death blow` | 33 % | Sinkt das Ziel unter 33 % Leben, tötet es der nächste Angriff mit einem Schlag. |
| `Freiheit/freedom` | — | Kann sich Helden nicht anschließen. |
| `Verteidigungsfertigkeit/defensive stand` | — | Widersteht dem ersten Schlag des Angreifers |

---

## Visuelle Effekte der Fähigkeiten {#visual-effects}

| Fähigkeit | Effekt | Angezeigt auf | Wann er erscheint |
|---|---|---|---|
| `Angriffsfertigkeit/attack skill` | <img src="/capturas/feedbacks/Penetration.png" class="fbstrip" alt="Effekt Angriffsfertigkeit" loading="lazy"> | Angreifer | Bei jedem Treffer |
| `Berserker/berserker` | <img src="/capturas/feedbacks/Rage.png" class="fbstrip" alt="Effekt Berserker" loading="lazy"> | Angreifer | Bei jedem Treffer |
| `Atempause/charge` | <img src="/capturas/feedbacks/Charge.png" class="fbstrip" alt="Effekt Atempause" loading="lazy"> | Angreifer | **Nur** wenn die Attacke wieder aufgeladen ist |
| `Rundumschlag/trample damage` | <img src="/capturas/feedbacks/TripleStrike.png" class="fbstrip" alt="Effekt Rundumschlag" loading="lazy"> | Angreifer | Bei jedem Treffer |
| `Angemessener Schaden/spread damage` | <img src="/capturas/feedbacks/BleedingAttack.png" class="fbstrip" alt="Effekt Angemessener Schaden" loading="lazy"> | Ziel | Bei jedem Treffer |
| `Vergeltungsschlag/spike damage` | <img src="/capturas/feedbacks/SpikedArmor.png" class="fbstrip" alt="Effekt Vergeltungsschlag" loading="lazy"> | Verteidiger | Bei jedem Treffer |
| `Vampirschlag/vampire blow` | <img src="/capturas/feedbacks/StaminaBoost.png" class="fbstrip" alt="Effekt Vampirschlag" loading="lazy"> | Angreifer | Bei jedem Treffer |
| `Todesstoß/death blow` | <img src="/capturas/feedbacks/Revenge.png" class="fbstrip" alt="Effekt Todesstoß" loading="lazy"> | Ziel | **Nur** beim tödlichen Schlag |
| `Verteidigungsfertigkeit/defensive stand` | <img src="/capturas/feedbacks/DefensiveStand.png" class="fbstrip" alt="Effekt Verteidigungsfertigkeit" loading="lazy"> | Verteidiger | **Nur** beim ersten Schlag des Angreifers |

`Freiheit` ist eine passive Fähigkeit und hat keinen visuellen Effekt.

---

## Gallische Einheiten {#gaul-units}

| Einheit | Leben | Angriff | Angriffsart | Hiebabwehr | Stichabwehr | Tempo | Reichweite | Fähigkeit |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Schwertkämpfer" loading="lazy"><span>Schwertkämpfer</span></span> | 160 | 10–18 | slash | 0 | 0 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Bogenschütze" loading="lazy"><span>Bogenschütze</span></span> | 100 | 6–10 | pierce | 0 | 0 | 80 | 400 | Angemessener Schaden |
| <span class="unidad"><img src="/capturas/iconos/gaxeman.png" class="icono" alt="Axtkämpfer" loading="lazy"><span>Axtkämpfer</span></span> | 280 | 16–24 | slash | 2 | 0 | 80 | — | Rundumschlag |
| <span class="unidad"><img src="/capturas/iconos/gspearman.png" class="icono" alt="Speerkämpfer" loading="lazy"><span>Speerkämpfer</span></span> | 300 | 16–24, x1,5 gegen Reiterei | pierce | 6 | 6 | 80 | — | Verteidigungsfertigkeit, Angemessener Schaden |
| <span class="unidad"><img src="/capturas/iconos/ghorseman.png" class="icono" alt="Reiter" loading="lazy"><span>Reiter</span></span> | 380 | 20–28 | slash | 0 | 0 | 140 | — | Atempause |
| <span class="unidad"><img src="/capturas/iconos/gwfighter.png" class="icono" alt="Kriegerin" loading="lazy"><span>Kriegerin</span></span> | 340 | 18–36 | slash | 0 | 8 | 80 | — | Vampirschlag |
| <span class="unidad"><img src="/capturas/iconos/gdruid.png" class="icono" alt="Druide" loading="lazy"><span>Druide</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/gvikinglord.png" class="icono" alt="Wikingerfürst" loading="lazy"><span>Wikingerfürst</span></span> | 3000 | 42–84 | slash | 6 | 6 | 80 | — | Freiheit, Atempause |
| <span class="unidad"><img src="/capturas/iconos/ieliteguard.png" class="icono" alt="Elitewache" loading="lazy"><span>Elitewache</span></span> | 350 | 18–28 | slash | 6 | 6 | 80 | — | Verteidigungsfertigkeit, Angriffsfertigkeit |

---

## Römische Einheiten {#roman-units}

| Einheit | Leben | Angriff | Angriffsart | Hiebabwehr | Stichabwehr | Tempo | Reichweite | Fähigkeit |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Hastatus" loading="lazy"><span>Hastatus</span></span> | 200 | 13–17 | slash | 0 | 5 | 80 | — | Verteidigungsfertigkeit |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Bogenschütze" loading="lazy"><span>Bogenschütze</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | Angemessener Schaden |
| <span class="unidad"><img src="/capturas/iconos/rgladiator.png" class="icono" alt="Gladiator" loading="lazy"><span>Gladiator</span></span> | 255 | 21–21 | pierce | 5 | 0 | 100 | — | Angemessener Schaden |
| <span class="unidad"><img src="/capturas/iconos/rspearman.png" class="icono" alt="Speerkämpfer" loading="lazy"><span>Speerkämpfer</span></span> | 275 | 15–23, x1,5 gegen Reiterei | slash | 7 | 15 | 80 | — | Verteidigungsfertigkeit, Vergeltungsschlag |
| <span class="unidad"><img src="/capturas/iconos/rhorseman.png" class="icono" alt="Späher" loading="lazy"><span>Späher</span></span> | 330 | 17–25 | slash | 3 | 3 | 140 | — | Atempause |
| <span class="unidad"><img src="/capturas/iconos/rpraetorian.png" class="icono" alt="Prätorianer" loading="lazy"><span>Prätorianer</span></span> | 475 | 27–47 | pierce | 7 | 7 | 80 | — | Angriffsfertigkeit, Todesstoß |
| <span class="unidad"><img src="/capturas/iconos/rpriest.png" class="icono" alt="Priester" loading="lazy"><span>Priester</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/rliberatus.png" class="icono" alt="Befreiter" loading="lazy"><span>Befreiter</span></span> | 300 | 30–30 | slash | 0 | 0 | 120 | — | Berserker |
| <span class="unidad"><img src="/capturas/iconos/cwarelephant.png" class="icono" alt="Kriegselefant" loading="lazy"><span>Kriegselefant</span></span> | 2000 | 30–40 | slash | 10 | 10 | 60 | — | Freiheit, Rundumschlag |

### Kriegselefant {#war-elephant}
- Fernkampfeinheiten verursachen x1,25 Schaden gegen Kriegselefanten

---

## Teutonische Einheiten {#teuton-units}

| Einheit | Leben | Angriff | Angriffsart | Hiebabwehr | Stichabwehr | Tempo | Reichweite | Fähigkeit |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/teutonarcher.png" class="icono" alt="Teutonischer Bogenschütze" loading="lazy"><span>Teutonischer Bogenschütze</span></span> | 200 | 8–18, x2 gegen Maultiere | pierce | 0 | 0 | 160 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/teutonmetal.png" class="icono" alt="Teutonischer Reiter" loading="lazy"><span>Teutonischer Reiter</span></span> | 250 | 10–20, x2 gegen Maultiere | slash | 0 | 0 | 160 | — | Rundumschlag |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Gallischer Bogenschütze (Teutonen)" loading="lazy"><span>Gallischer Bogenschütze (Teutonen)</span></span> | 100 | 6–12 | pierce | 2 | 2 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Gallischer Schwertkämpfer (Teutonen)" loading="lazy"><span>Gallischer Schwertkämpfer (Teutonen)</span></span> | 240 | 10–18 | slash | 2 | 2 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Römischer Bogenschütze (Teutonen)" loading="lazy"><span>Römischer Bogenschütze (Teutonen)</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Römischer Hastatus (Teutonen)" loading="lazy"><span>Römischer Hastatus (Teutonen)</span></span> | 240 | 13–17 | slash | 3 | 3 | 80 | — | — |

### Teutonischer Bogenschütze {#teuton-archer}
- 'Taunt'-Animation der Einheit eingerichtet

---

## Andere Einheiten {#other-units}

| Einheit | Leben | Angriff | Angriffsart | Hiebabwehr | Stichabwehr | Tempo | Reichweite | Fähigkeit |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/imilitiaman.png" class="icono" alt="Milizsoldat" loading="lazy"><span>Milizsoldat</span></span> | 180 | 6–12 | slash | 4 | 0 | 80 | — | — |
| <span class="unidad"><img src="/capturas/iconos/iarcher.png" class="icono" alt="Bogenschütze" loading="lazy"><span>Bogenschütze</span></span> | 180 | 12–18 | pierce | 4 | 8 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/islinger.png" class="icono" alt="Schleuderer" loading="lazy"><span>Schleuderer</span></span> | 200 | 20–30 | pierce | 0 | 0 | 100 | 300 | — |
| <span class="unidad"><img src="/capturas/iconos/idefender.png" class="icono" alt="Verteidiger" loading="lazy"><span>Verteidiger</span></span> | 200 | 14–24 | pierce | 8 | 8 | 80 | — | Verteidigungsfertigkeit |
| <span class="unidad"><img src="/capturas/iconos/icavalry.png" class="icono" alt="Kavallerie" loading="lazy"><span>Kavallerie</span></span> | 240 | 20–30 | slash | 6 | 6 | 160 | — | Atempause |
| <span class="unidad"><img src="/capturas/iconos/imountaineer.png" class="icono" alt="Bergsteiger" loading="lazy"><span>Bergsteiger</span></span> | 400 | 24–48 | slash | 4 | 0 | 80 | — | Freiheit |
| <span class="unidad"><img src="/capturas/iconos/teutonwolf.png" class="icono" alt="Wolf (Germanen)" loading="lazy"><span>Wolf (Germanen)</span></span> | 400 | 22–26 | slash | 8 | 4 | 160 | — | Atempause, Rundumschlag |

---

### Helden {#heroes}
- Änderungen an den Grundwerten der Helden (mehr Leben)
- Mehr Leben pro Stufe
- Helden-Assets wiederverwendet, um mehr zufällige Helden zu erzeugen
<p align="center">
    <img src="/capturas/captura_heroes_1.png" style="width: 75%; max-width: 768px;" alt="Zufällige Helden" loading="lazy">
</p>

- Helden können ihren zugewiesenen Druiden/Priestern befehlen, ihre Zauber zu wirken
- Helden können ihren Einheiten befehlen, eine Katapult zu bauen
- HINWEIS: Ein neuer Befehl an den Helden bricht den vorherigen Katapult-/Zauberbefehl ab
<p align="center">
    <img src="/capturas/captura_heroe_hechizos.png" style="width: 75%; max-width: 768px;" alt="Helden wirken Zauber" loading="lazy">
</p>

- Die zufällige Rekrutierung der Helden wurde geändert: Sie ist nun sequenziell mit zufälligem Startpunkt, um die Vielfalt der Helden-Assets/Sprites in einer Partie zu maximieren.

## 8. Spielverbesserungen {#sec7}

### Neue KI «LAT» {#lat-ai}
- Höherer Schwierigkeitsgrad im Spiel gegen die KI
- Anfängliche Militärstrategie hinzugefügt
- Anfängliche Erkundungsstrategie hinzugefügt
- Bestimmte Fälle im Belagerungsalgorithmus behoben, die Armeen festhängen ließen, ohne die feindliche Festung belagern zu können
- Verbesserter Forschungsalgorithmus. Die KI erforscht die Verbesserungen in Arena, Taverne und Tempel
- Verbesserte Rekrutierung der Spezialeinheiten
- Verbesserte Rekrutierung der Militäreinheiten
- Verbesserte Berechnung von und Reaktion auf Bedrohungen
- Verbesserte Zielverwaltung, aggressivere KI
- Verbessertes System zur Überwachung und Steuerung der Armeen
- Verbessertes Rückzugssystem der Armeen
- Verbessertes Nachschubsystem für die Verpflegung der Armeen
- Verbessertes Teleport-System (Höhlen)
- Verbesserte Nutzung der Ruinen
- Verbessertes System zum Aufsammeln und Verwenden von Gegenständen
- Nahrungshandel mit den gallischen Vorposten neu umgesetzt
<p align="center">
    <img src="/capturas/captura_ia_items_1.png" style="width: 75%;  max-width: 768px;" alt="Gegenstandssystem" loading="lazy">
</p>

### Festung {#stronghold}
- Bauernanimationen in den römischen Festungen korrigiert und die fehlenden Gebäude ergänzt
- Legionär (Rom)/gallischer Bogenschütze (Gallien) zu den Bauernanimationen hinzugefügt
- Angriffswerte von Türmen und Toren angepasst. Tore schießen jetzt ebenfalls Pfeile.
- Benachrichtigung hinzugefügt, wenn eine Technologie fertig erforscht ist
- Vom Forum aus lassen sich die Zauber der Altäre wirken (der Altar wird zufällig gewählt)
<p align="center">
    <img src="/capturas/Captura_foro.png" style="width: 75%;  max-width: 768px;" alt="Zauber aus dem Forum" loading="lazy">
</p>

### Römische Taverne {#tavern}
- Neue Technologie 'Meisterschaften'
- Technologie 'Pferde importieren' überarbeitet

### 'Ausbildung' der Einheiten entfernt {#training}
- Einheiten aus der Kaserne werden bereits mit der erforschten 'Ausbildungsstufe' erzeugt
<p align="center">
    <img src="/capturas/captura_cuartel_1.png" style="width: 75%;  max-width: 768px;" alt="Ausbildung" loading="lazy">
</p>

### Formationen {#formations}
- 'Radius' der Einheiten in Formation verringert. Einheiten in Formation stehen enger beieinander.
- Aufbau der Formationen überarbeitet
<p align="center">
    <img src="/capturas/Captura_formaciones.png" style="width: 75%;  max-width: 768px;" alt="Formationen" loading="lazy">
</p>

### Druiden und Magie {#magic}
- Zauberschaden verringert
- Die 'Giftwolke' (Priester) neu umgesetzt, damit sie befreundete Einheiten nicht mehr verletzt
- Anpassungen am Rekrutierungssystem der Druiden
- Die KI nutzt die Altäre in Zufallspartien
- Die KI setzt im Kampf Zauber ein (Vampirgeist, Giftwolke)
<p align="center">
    <img src="/capturas/Captura6_ia_nube.png" style="width: 75%;  max-width: 768px;" alt="Zauber der KI" loading="lazy">
</p>

### Teutonen {#teutons}
- KI der teutonischen Armeen verbessert
- Teutonen können Festungen der Spieler erobern
<p align="center">
    <img src="/capturas/Captura4.png" style="width: 75%;  max-width: 768px;" alt="Die Teutonen-Bedrohung" loading="lazy">
</p>

### Katapulte {#catapults}
- Einheitenlimit von 10 auf 5 verringert

### Dörfer {#villages}
- Dörfer erzeugen zusammen mit den Nahrungsmaultieren automatisch Bauern
- Fehler behoben, bei dem Bauern/Maultiere für immer an den Festungstoren hängen blieben
- Eroberung der Dörfer verbessert: Ein Dorf lässt sich nicht mehr durch das Erobern seiner 'Häuser' einnehmen

### Vorposten {#outposts}
- Startverteidiger zu den Vorposten hinzugefügt
<p align="center">
    <img src="/capturas/captura_fortines_1.png" style="width: 75%;  max-width: 768px;" alt="Gallische Vorposten" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_fortines_2.png" style="width: 75%;  max-width: 768px;" alt="Verteidiger des Vorpostens" loading="lazy">
</p>

### Tiere {#animals}
- Fehler behoben, bei dem Hirsche an den Kartenrändern hängen blieben

### Sonstiges {#other}
- 'Handle Leak'-Meldungen in der vx.log behoben
- 'assets/interface/settlement icon'-Meldungen in der vx.log behoben
- BONUS.XML-Einträge behoben, die zufällig keine Wirkung hatten
- Zufällige Abstürze beim Laden von Karten behoben
- Fehler behoben, der in Mehrspielerpartien maximale Latenz (begrenzt durch MaxTickSize) verursachte, wenn die Betriebszeit des Computers eines Mitspielers mehr als 24,86 Tage betrug
- Fehler in der Gefechtsoberfläche behoben, die auf vordefinierten Karten beim Ändern der Position eines Spielers in der Liste die falsche Nation festlegte
- Der 'Wasser'-Pinsel des Editors verändert mit der 'Shift'-Aktion nicht mehr die Höhe des umliegenden Geländes
- Brücken, Lager und Ruinen als Landschaftsobjekte aus Imperivm 2 hinzugefügt
- Stabilität in Mehrspielerpartien verbessert

## 9. Korrekturen am Winter-Biom {#sec8}
- Minimap-Bilder durch die Sommerversionen ersetzt
- Belichtung (Helligkeit) der Winter-Geländetexturen verringert
<p align="center">
    <img src="/capturas/captura_mapa_invierno_1.png" style="width: 75%;  max-width: 768px;" alt="Winterkarte" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_decorados_inv_1.png" style="width: 75%;  max-width: 768px;" alt="Winterlandschaft" loading="lazy">
</p>

## 10. Spielerfarben {#sec9}

Neugestaltung der Spielerfarben, um sie optisch maximal unterscheidbar zu machen und Verwechslungen zu vermeiden.

| ID | Ursprüngliche Farbe | HEX ursprünglich | Neue Farbe | HEX neu |
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

## Und viele weitere undokumentierte Änderungen... {#more}
