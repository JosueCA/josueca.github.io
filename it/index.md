---
layout: default
lang: "it"
permalink: /it/
title: "Imperivm 1 HD e Mod - La Minaccia Teutone (patch Full HD)"
description: "Scarica la mod «La Amenaza Teutón» (La Minaccia Teutone) e la patch Full HD per Imperivm - La Guerra de las Galias: nuove risoluzioni HD, IA migliorata, unità, mappe casuali, supporto multilingua e supporto Linux/Wine."
banner_title: "Imperivm 1 - La Minaccia Teutone + patch Full HD"
banner_tagline: "Imperivm 1 HD: la mod «La Amenaza Teutón» e la patch Full HD per Imperivm - La Guerra de las Galias. Nuove risoluzioni HD, IA migliorata, unità, mappe, supporto multilingua e supporto Linux/Wine."
image: /capturas/AMENAZA_TEUTON.png
---

<p align="center">
    <img src="/capturas/AMENAZA_TEUTON.png" style="width: 75%;  max-width: 768px;" alt="Illustrazione La Minaccia Teutone">
    <br>
    <b>Imperivm 1 - La Minaccia Teutone</b>
</p>

**Imperivm 1 HD** è una **mod** («La Amenaza Teutón», La Minaccia Teutone) e una **patch Full HD** per *Imperivm - La Guerra de las Galias* (Celtic Kings / Imperivm 1). Aggiunge nuove **risoluzioni HD** fino a 1920×1080, un'**IA migliorata**, modifiche alle unità, mappe casuali, **supporto multilingua** (spagnolo, tedesco, francese, inglese e italiano) e il supporto per giocare su **Linux/Wine**.

## Download {#downloads}

[Scarica la mod](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Scarica Imperivm 1 HD (senza mod)](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Scarica le mappe](https://github.com/JosueCA/La-Amenaza-Teuton)  

[Scarica su ModDB](https://www.moddb.com/members/sacredgames120)  

[Scarica Imperivm 2 HD](https://www.moddb.com/members/sacredgames120)  

---

## Compatibilità con le avventure {#adventures}

Questa MOD non è compatibile al 100 % con le avventure. Per goderti l'esperienza originale in Full HD, usa la patch autonoma per il gioco.

[Compatibilità con le avventure](https://github.com/JosueCA/La-Amenaza-Teuton/blob/master/AdventuresMod/README.md)

## Indice {#toc}

1. [Note di installazione](#install)
1. [Compatibilità audio](#sec1)
1. [Nuove risoluzioni dello schermo HD](#sec2)
1. [Supporto multilingua](#sec3)
1. [Modifiche generali](#sec4)
1. [Mappe casuali](#sec5)
1. [Modifiche alle unità](#sec6)
   - [Abilità](#specialities)
   - [Effetti visivi delle abilità](#visual-effects)
   - [Unità galliche](#gaul-units)
   - [Unità romane](#roman-units)
   - [Unità teutoni](#teuton-units)
   - [Altre unità](#other-units)
   - [Eroi](#heroes)
1. [Miglioramenti al gioco](#sec7)
   - [Nuova IA «LAT»](#lat-ai)
   - [Roccaforte](#stronghold)
   - [Taverna romana](#tavern)
   - [Rimosso l'‘addestramento’ delle unità](#training)
   - [Formazioni](#formations)
   - [Druidi e magia](#magic)
   - [Teutoni](#teutons)
   - [Catapulte](#catapults)
   - [Villaggi](#villages)
   - [Avamposti](#outposts)
   - [Animali](#animals)
   - [Altro](#other)
1. [Correzioni al bioma invernale](#sec8)
1. [Colori dei giocatori](#sec9)

---

## 1. Note di installazione {#install}

Questa MOD si applica direttamente su un'installazione esistente di "Imperivm 1: La Guerra de las Galias" (la versione spagnola di Celtic Kings: Rage of War), sostituendo i file .pak e le altre cartelle/file inclusi nello zip.

<details class="pasos" markdown="1">
<summary>Passo dopo passo</summary>

1. Apri il disco (o l'immagine del CD) di *Imperivm - La Guerra de las Galias* ed esegui `Instalar.exe`.

   <img src="/capturas/install/zi1.png" class="paso" alt="Contenuto del disco di Imperivm con Instalar.exe selezionato" loading="lazy">

1. Nel menu dell'installer, premi **OPCIONES** (opzioni).

   <img src="/capturas/install/zi2.png" class="paso" alt="Menu dell'installer di Imperivm" loading="lazy">

1. Scegli l'unità e la cartella di destinazione e premi **INSTALAR** (installa).

   <img src="/capturas/install/zi3.png" class="paso" alt="Selezione dell'unità e della cartella di destinazione" loading="lazy">

1. Conferma il percorso di installazione con **Aceptar** (OK).

   <img src="/capturas/install/zi4.png" class="paso" alt="Conferma della cartella di installazione" loading="lazy">

1. Attendi la copia dei file del gioco.

   <img src="/capturas/install/zi5.png" class="paso" alt="Avanzamento della copia dei file" loading="lazy">

1. Accetta con **Sí** (sì) il contratto di licenza di **Microsoft DirectX 8.1**, richiesto dal gioco.

   <img src="/capturas/install/zi6.png" class="paso" alt="Contratto di licenza di Microsoft DirectX 8.1" loading="lazy">

1. Al termine l'installer mostra **JUGAR** (gioca): il gioco è installato. Chiudilo con **SALIR** (esci).

   <img src="/capturas/install/zi7.png" class="paso" alt="Installer con l'opzione JUGAR dopo l'installazione" loading="lazy">

1. Estrai lo zip della MOD sulla cartella di installazione del gioco, sostituendo i file esistenti.

</details>

Su Linux/Wine, vedi anche [Compatibilità audio](#sec1).

## 2. Compatibilità audio {#sec1}

### Nuovo motore audio {#audio-backend}

Nuovo motore audio con supporto per più interfacce (WASAPI, DirectSound e WinMM). Attivo per impostazione predefinita, con rilevamento automatico dell'interfaccia. (Configurabile in `config.ini`)

### Wine {#wine}

**Le versioni più recenti di Wine non richiedono un prefisso a 32 bit separato. Supportano 32 e 64 bit nello stesso prefisso a 64 bit**

- **Wine**: WinXP 32 bit
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

- **Conversione del codec audio**: i file vocali delle unità usavano il codec Microsoft ADPCM, che Wine non supporta completamente. Oltre **120 file WAV** di voci (Galli, Romani e Teutoni) sono stati convertiti in PCM standard perché funzionino correttamente su Linux/Wine.
- Convertiti i file audio delle avventure 'Celtic Kings Adventure' e 'Tutorial'

## 3. Nuove risoluzioni dello schermo HD {#sec2}

| Risoluzione | Larghezza | Altezza | Formato |
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

**Supporto per le risoluzioni 1600px-1920px disponibile dalla versione "La Amenaza Teuton v0.4.0"**

## 4. Supporto multilingua {#sec3}
- Aggiunti tedesco, francese, inglese e italiano (oltre allo spagnolo). Configurabile dal file 'vxSettings.ini'
- Corretto il volume delle voci in inglese

## 5. Modifiche generali {#sec4}
- Modifiche alla musica
- Piccoli ritocchi all'interfaccia di gioco
- Video introduttivo sostituito dal trailer (qualità migliore)
- Migliorata la stabilità del gioco
- La barra della salute delle unità (tasto '~') è ora limitata agli eroi, e alle sole unità del giocatore

<p align="center">
    <img src="/capturas/captura_salud.png" style="width: 75%;  max-width: 768px;" alt="Barra della salute" loading="lazy">
</p>

- Nuovo tipo di partita 'Total war' (Eliminazione, ma con reclutamento moltiplicato per 5)
- Nuovo widget di selezione rapida
<p align="center">
    <img src="/capturas/ui/widget-shorcut-zoomed.jpg" style="width: 75%;  max-height: 579px;" alt="Widget" loading="lazy">
</p>

## 6. Mappe casuali {#sec5}
- Rivista la generazione delle mappe casuali
- Riutilizzati gli asset per generare scenari più vari
- Aumentata la quantità di decorazioni
- Aggiunte altre decorazioni che generano oggetti
- Ridotto il numero di cervi
- Nuovi scenari per villaggi, roccaforti, avamposti e accampamenti teutoni
- Migliorata la disposizione casuale delle montagne sopra i villaggi

<span id="galeria"></span>

<div class="galeria" markdown="0">
  <a href="#img-decorados1"><img src="/capturas/mapas/thumbs/captura_decorados_1.png" alt="Scenari 1" loading="lazy"></a>
  <a href="#img-decorados2"><img src="/capturas/mapas/thumbs/captura_decorados_2.png" alt="Scenari 2" loading="lazy"></a>
  <a href="#img-romecity"><img src="/capturas/mapas/thumbs/rome_city.png" alt="Città romana" loading="lazy"></a>
  <a href="#img-gaulcity"><img src="/capturas/mapas/thumbs/gaul_city.png" alt="Città gallica" loading="lazy"></a>
  <a href="#img-outpost1"><img src="/capturas/mapas/thumbs/outpost1.png" alt="Avamposto 1" loading="lazy"></a>
  <a href="#img-outpost2"><img src="/capturas/mapas/thumbs/outpost2.png" alt="Avamposto 2" loading="lazy"></a>
  <a href="#img-village1"><img src="/capturas/mapas/thumbs/village1.png" alt="Villaggio 1" loading="lazy"></a>
  <a href="#img-village2"><img src="/capturas/mapas/thumbs/village2.png" alt="Villaggio 2" loading="lazy"></a>
  <a href="#img-village3"><img src="/capturas/mapas/thumbs/village3.png" alt="Villaggio 3" loading="lazy"></a>
  <a href="#img-village4"><img src="/capturas/mapas/thumbs/village4.png" alt="Villaggio 4" loading="lazy"></a>
  <a href="#img-village5"><img src="/capturas/mapas/thumbs/village5.png" alt="Villaggio 5" loading="lazy"></a>
  <a href="#img-village6"><img src="/capturas/mapas/thumbs/village6.png" alt="Villaggio 6" loading="lazy"></a>
</div>

<div class="lightbox" id="img-decorados1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_1.png" alt="Scenari 1" loading="lazy"></div>
<div class="lightbox" id="img-decorados2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_2.png" alt="Scenari 2" loading="lazy"></div>
<div class="lightbox" id="img-romecity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/rome_city.png" alt="Città romana" loading="lazy"></div>
<div class="lightbox" id="img-gaulcity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/gaul_city.png" alt="Città gallica" loading="lazy"></div>
<div class="lightbox" id="img-outpost1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost1.png" alt="Avamposto 1" loading="lazy"></div>
<div class="lightbox" id="img-outpost2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost2.png" alt="Avamposto 2" loading="lazy"></div>
<div class="lightbox" id="img-village1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village1.png" alt="Villaggio 1" loading="lazy"></div>
<div class="lightbox" id="img-village2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village2.png" alt="Villaggio 2" loading="lazy"></div>
<div class="lightbox" id="img-village3"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village3.png" alt="Villaggio 3" loading="lazy"></div>
<div class="lightbox" id="img-village4"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village4.png" alt="Villaggio 4" loading="lazy"></div>
<div class="lightbox" id="img-village5"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village5.png" alt="Villaggio 5" loading="lazy"></div>
<div class="lightbox" id="img-village6"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village6.png" alt="Villaggio 6" loading="lazy"></div>

---

## 7. Modifiche alle unità {#sec6}

## Abilità {#specialities}

- L'abilità 'arco mortale' non influisce più sugli eroi
- Corretta l'abilità 'abilità di attacco', che non funzionava

| Abilità | Valore | Descrizione |
|---|---|---|
| `abilità di attacco/attack skill` | +1 | Il danno aumenta a ogni colpo consecutivo sullo stesso bersaglio |
| `berserker` | 100 % | Il danno aumenta man mano che si perde salute |
| `assalto/charge` | 600 % / 8 000 ms | Moltiplica il danno per 600 % con una ricarica di 8 secondi senza attaccare |
| `danno di violazione/trample damage` | 50 % | L'unità infligge il 50 % di danno ai nemici vicini |
| `danno diffuso/spread damage` | 175 % | Il danno aumenta quanto più il bersaglio è ferito |
| `danno da arma da punta/spike damage` | 25 % | Restituisce il 25 % del danno all'attaccante. |
| `attacco del vampiro/vampire blow` | 33 % | Recupera il 33 % del danno inflitto come salute propria. |
| `arco mortale/death blow` | 33 % | Quando il bersaglio scende sotto il 33 % di vita, l'attacco successivo lo uccide con un colpo solo. |
| `libertà/freedom` | — | Non può unirsi agli eroi. |
| `capacità difensiva/defensive stand` | — | Resiste al primo colpo dell'attaccante |

---

## Effetti visivi delle abilità {#visual-effects}

| Abilità | Effetto | Mostrato su | Quando compare |
|---|---|---|---|
| `abilità di attacco/attack skill` | <img src="/capturas/feedbacks/Penetration.png" class="fbstrip" alt="Effetto abilità di attacco" loading="lazy"> | Attaccante | A ogni colpo |
| `berserker` | <img src="/capturas/feedbacks/Rage.png" class="fbstrip" alt="Effetto berserker" loading="lazy"> | Attaccante | A ogni colpo |
| `assalto/charge` | <img src="/capturas/feedbacks/Charge.png" class="fbstrip" alt="Effetto assalto" loading="lazy"> | Attaccante | **Solo** quando l'assalto è ricaricato |
| `danno di violazione/trample damage` | <img src="/capturas/feedbacks/TripleStrike.png" class="fbstrip" alt="Effetto danno di violazione" loading="lazy"> | Attaccante | A ogni colpo |
| `danno diffuso/spread damage` | <img src="/capturas/feedbacks/BleedingAttack.png" class="fbstrip" alt="Effetto danno diffuso" loading="lazy"> | Bersaglio | A ogni colpo |
| `danno da arma da punta/spike damage` | <img src="/capturas/feedbacks/SpikedArmor.png" class="fbstrip" alt="Effetto danno da arma da punta" loading="lazy"> | Difensore | A ogni colpo |
| `attacco del vampiro/vampire blow` | <img src="/capturas/feedbacks/StaminaBoost.png" class="fbstrip" alt="Effetto attacco del vampiro" loading="lazy"> | Attaccante | A ogni colpo |
| `arco mortale/death blow` | <img src="/capturas/feedbacks/Revenge.png" class="fbstrip" alt="Effetto arco mortale" loading="lazy"> | Bersaglio | **Solo** sul colpo di grazia |
| `capacità difensiva/defensive stand` | <img src="/capturas/feedbacks/DefensiveStand.png" class="fbstrip" alt="Effetto capacità difensiva" loading="lazy"> | Difensore | **Solo** al primo colpo dell'attaccante |

`libertà` è un'abilità passiva e non ha effetto visivo.

---

## Unità galliche {#gaul-units}

| Unità | Salute | Attacco | Tipo di attacco | Dif. taglio | Dif. perfora | Velocità | Gittata | Abilità |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Guerriero con spadone" loading="lazy"><span>Guerriero con spadone</span></span> | 160 | 10–18 | slash | 0 | 0 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Arciere" loading="lazy"><span>Arciere</span></span> | 100 | 6–10 | pierce | 0 | 0 | 80 | 400 | danno diffuso |
| <span class="unidad"><img src="/capturas/iconos/gaxeman.png" class="icono" alt="Lanciatore d'ascia" loading="lazy"><span>Lanciatore d'ascia</span></span> | 280 | 16–24 | slash | 2 | 0 | 80 | — | danno di violazione |
| <span class="unidad"><img src="/capturas/iconos/gspearman.png" class="icono" alt="Lanciere" loading="lazy"><span>Lanciere</span></span> | 300 | 16–24, x1,5 contro Cavalleria | pierce | 6 | 6 | 80 | — | capacità difensiva, danno diffuso |
| <span class="unidad"><img src="/capturas/iconos/ghorseman.png" class="icono" alt="Cavaliere" loading="lazy"><span>Cavaliere</span></span> | 380 | 20–28 | slash | 0 | 0 | 140 | — | assalto |
| <span class="unidad"><img src="/capturas/iconos/gwfighter.png" class="icono" alt="Guerriera" loading="lazy"><span>Guerriera</span></span> | 340 | 18–36 | slash | 0 | 8 | 80 | — | attacco del vampiro |
| <span class="unidad"><img src="/capturas/iconos/gdruid.png" class="icono" alt="Druido" loading="lazy"><span>Druido</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/gvikinglord.png" class="icono" alt="Lord Vichingo" loading="lazy"><span>Lord Vichingo</span></span> | 3000 | 42–84 | slash | 6 | 6 | 80 | — | libertà, assalto |
| <span class="unidad"><img src="/capturas/iconos/ieliteguard.png" class="icono" alt="Guardia scelta" loading="lazy"><span>Guardia scelta</span></span> | 350 | 18–28 | slash | 6 | 6 | 80 | — | capacità difensiva, abilità di attacco |

---

## Unità romane {#roman-units}

| Unità | Salute | Attacco | Tipo di attacco | Dif. taglio | Dif. perfora | Velocità | Gittata | Abilità |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Astato" loading="lazy"><span>Astato</span></span> | 200 | 13–17 | slash | 0 | 5 | 80 | — | capacità difensiva |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Arciere" loading="lazy"><span>Arciere</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | danno diffuso |
| <span class="unidad"><img src="/capturas/iconos/rgladiator.png" class="icono" alt="Gladiatore" loading="lazy"><span>Gladiatore</span></span> | 255 | 21–21 | pierce | 5 | 0 | 100 | — | danno diffuso |
| <span class="unidad"><img src="/capturas/iconos/rspearman.png" class="icono" alt="Principe" loading="lazy"><span>Principe</span></span> | 275 | 15–23, x1,5 contro Cavalleria | slash | 7 | 15 | 80 | — | capacità difensiva, danno da arma da punta |
| <span class="unidad"><img src="/capturas/iconos/rhorseman.png" class="icono" alt="Esploratore" loading="lazy"><span>Esploratore</span></span> | 330 | 17–25 | slash | 3 | 3 | 140 | — | assalto |
| <span class="unidad"><img src="/capturas/iconos/rpraetorian.png" class="icono" alt="Pretoriano" loading="lazy"><span>Pretoriano</span></span> | 475 | 27–47 | pierce | 7 | 7 | 80 | — | abilità di attacco, arco mortale |
| <span class="unidad"><img src="/capturas/iconos/rpriest.png" class="icono" alt="Sacerdote" loading="lazy"><span>Sacerdote</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/rliberatus.png" class="icono" alt="Liberto" loading="lazy"><span>Liberto</span></span> | 300 | 30–30 | slash | 0 | 0 | 120 | — | berserker |
| <span class="unidad"><img src="/capturas/iconos/cwarelephant.png" class="icono" alt="Elefante da guerra" loading="lazy"><span>Elefante da guerra</span></span> | 2000 | 30–40 | slash | 10 | 10 | 60 | — | libertà, danno di violazione |

### Elefante da guerra {#war-elephant}
- Le unità a distanza infliggono x1,25 contro gli Elefanti da guerra

---

## Unità teutoni {#teuton-units}

| Unità | Salute | Attacco | Tipo di attacco | Dif. taglio | Dif. perfora | Velocità | Gittata | Abilità |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/teutonarcher.png" class="icono" alt="Arciere teutone" loading="lazy"><span>Arciere teutone</span></span> | 200 | 8–18, x2 contro Muli | pierce | 0 | 0 | 160 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/teutonmetal.png" class="icono" alt="Cavaliere teutone" loading="lazy"><span>Cavaliere teutone</span></span> | 250 | 10–20, x2 contro Muli | slash | 0 | 0 | 160 | — | danno di violazione |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Arciere gallico teutone" loading="lazy"><span>Arciere gallico teutone</span></span> | 100 | 6–12 | pierce | 2 | 2 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Guerriero gallico teutone" loading="lazy"><span>Guerriero gallico teutone</span></span> | 240 | 10–18 | slash | 2 | 2 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Arciere romano teutone" loading="lazy"><span>Arciere romano teutone</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Astato romano teutone" loading="lazy"><span>Astato romano teutone</span></span> | 240 | 13–17 | slash | 3 | 3 | 80 | — | — |

### Arciere teutone {#teuton-archer}
- Configurata l'animazione 'taunt' dell'unità

---

## Altre unità {#other-units}

| Unità | Salute | Attacco | Tipo di attacco | Dif. taglio | Dif. perfora | Velocità | Gittata | Abilità |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/imilitiaman.png" class="icono" alt="Miliziano" loading="lazy"><span>Miliziano</span></span> | 180 | 6–12 | slash | 4 | 0 | 80 | — | — |
| <span class="unidad"><img src="/capturas/iconos/iarcher.png" class="icono" alt="Arciere" loading="lazy"><span>Arciere</span></span> | 180 | 12–18 | pierce | 4 | 8 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/islinger.png" class="icono" alt="Fromboliere" loading="lazy"><span>Fromboliere</span></span> | 200 | 20–30 | pierce | 0 | 0 | 100 | 300 | — |
| <span class="unidad"><img src="/capturas/iconos/idefender.png" class="icono" alt="Difensore" loading="lazy"><span>Difensore</span></span> | 200 | 14–24 | pierce | 8 | 8 | 80 | — | capacità difensiva |
| <span class="unidad"><img src="/capturas/iconos/icavalry.png" class="icono" alt="Cavalleria" loading="lazy"><span>Cavalleria</span></span> | 240 | 20–30 | slash | 6 | 6 | 160 | — | assalto |
| <span class="unidad"><img src="/capturas/iconos/imountaineer.png" class="icono" alt="Montanaro" loading="lazy"><span>Montanaro</span></span> | 400 | 24–48 | slash | 4 | 0 | 80 | — | libertà |
| <span class="unidad"><img src="/capturas/iconos/teutonwolf.png" class="icono" alt="Lupo Teutone" loading="lazy"><span>Lupo Teutone</span></span> | 400 | 22–26 | slash | 8 | 4 | 160 | — | assalto, danno di violazione |

---

### Eroi {#heroes}
- Modifiche alle statistiche di base degli eroi (più vita)
- Più vita per livello
- Riutilizzati gli asset degli eroi per generare più eroi casuali
<p align="center">
    <img src="/capturas/captura_heroes_1.png" style="width: 75%; max-width: 768px;" alt="Eroi casuali" loading="lazy">
</p>

- Gli eroi possono ordinare ai druidi/sacerdoti assegnati di lanciare i loro incantesimi
- Gli eroi possono ordinare alle proprie unità di costruire una catapulta
- NOTA: dare un nuovo ordine all'eroe annulla il precedente ordine di catapulta/incantesimo
<p align="center">
    <img src="/capturas/captura_heroe_hechizos.png" style="width: 75%; max-width: 768px;" alt="Eroi che lanciano incantesimi" loading="lazy">
</p>

- Modificato il reclutamento casuale degli eroi: ora è sequenziale con avvio casuale, per massimizzare la varietà degli asset/sprite degli eroi in una partita.

## 8. Miglioramenti al gioco {#sec7}

### Nuova IA «LAT» {#lat-ai}
- Maggiore difficoltà giocando contro l'IA
- Aggiunta una strategia militare iniziale
- Aggiunta una strategia di esplorazione iniziale
- Corretti casi specifici nell'algoritmo di assedio che lasciavano gli eserciti bloccati, incapaci di assediare la roccaforte nemica
- Migliorato l'algoritmo di ricerca tecnologica. L'IA ricerca i miglioramenti in arena, taverna e tempio
- Migliorato il reclutamento delle unità speciali
- Migliorato il reclutamento delle unità militari
- Migliorati il calcolo delle minacce e la risposta
- Migliorata la gestione degli obiettivi, IA più aggressiva
- Migliorato il sistema di monitoraggio e controllo degli eserciti
- Migliorato il sistema di ritirata degli eserciti
- Migliorato il sistema di rifornimento di viveri degli eserciti
- Migliorato il sistema di teletrasporto (grotte)
- Migliorato l'uso delle rovine
- Migliorato il sistema di raccolta e uso degli oggetti
- Reimplementato il commercio di viveri con gli avamposti gallici
<p align="center">
    <img src="/capturas/captura_ia_items_1.png" style="width: 75%;  max-width: 768px;" alt="Sistema di oggetti" loading="lazy">
</p>

### Roccaforte {#stronghold}
- Corrette le animazioni dei contadini nelle roccaforti romane e aggiunti gli edifici mancanti
- Aggiunti legionario (Roma)/arciere gallico (Gallia) alle animazioni dei contadini
- Regolati i parametri di attacco di torri e porte. Anche le porte ora scagliano frecce.
- Aggiunta una notifica al termine della ricerca di una tecnologia
- Dal foro si possono lanciare gli incantesimi degli altari (l'altare viene scelto a caso)
<p align="center">
    <img src="/capturas/Captura_foro.png" style="width: 75%;  max-width: 768px;" alt="Incantesimi dal foro" loading="lazy">
</p>

### Taverna romana {#tavern}
- Nuova tecnologia 'Campionati'
- Rivista la tecnologia 'Importa cavalli'

### Rimosso l'‘addestramento’ delle unità {#training}
- Le unità della caserma vengono create già al livello di 'addestramento' ricercato
<p align="center">
    <img src="/capturas/captura_cuartel_1.png" style="width: 75%;  max-width: 768px;" alt="Addestramento" loading="lazy">
</p>

### Formazioni {#formations}
- Ridotto il 'raggio' delle unità in formazione. Le unità in formazione stanno più vicine tra loro.
- Riviste le strutture delle formazioni
<p align="center">
    <img src="/capturas/Captura_formaciones.png" style="width: 75%;  max-width: 768px;" alt="Formazioni" loading="lazy">
</p>

### Druidi e magia {#magic}
- Ridotto il danno degli incantesimi
- Reimplementata la 'Nube velenosa' (sacerdote) perché non danneggi le unità alleate
- Ritocchi al sistema di reclutamento dei druidi
- L'IA usa gli altari nelle partite casuali
- L'IA usa gli incantesimi in combattimento (Spirito vampiro, Nube velenosa)
<p align="center">
    <img src="/capturas/Captura6_ia_nube.png" style="width: 75%;  max-width: 768px;" alt="Incantesimi dell'IA" loading="lazy">
</p>

### Teutoni {#teutons}
- Migliorata l'IA degli eserciti teutoni
- I Teutoni possono conquistare le roccaforti dei giocatori
<p align="center">
    <img src="/capturas/Captura4.png" style="width: 75%;  max-width: 768px;" alt="La Minaccia Teutone" loading="lazy">
</p>

### Catapulte {#catapults}
- Ridotto il limite di unità da 10 a 5

### Villaggi {#villages}
- I villaggi producono contadini automaticamente insieme ai muli dei viveri
- Corretto il bug per cui contadini/muli restavano bloccati per sempre alle porte della roccaforte
- Migliorata la conquista dei villaggi: non è più possibile conquistare un villaggio conquistandone le 'case'

### Avamposti {#outposts}
- Aggiunti difensori iniziali agli avamposti
<p align="center">
    <img src="/capturas/captura_fortines_1.png" style="width: 75%;  max-width: 768px;" alt="Avamposti gallici" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_fortines_2.png" style="width: 75%;  max-width: 768px;" alt="Difensori dell'avamposto" loading="lazy">
</p>

### Animali {#animals}
- Corretto il bug per cui i cervi restavano bloccati ai bordi della mappa

### Altro {#other}
- Corretti i messaggi 'Handle Leak' nel vx.log
- Corretti i messaggi 'assets/interface/settlement icon' nel vx.log
- Corrette le voci di BONUS.XML che a volte non avevano effetto
- Corretti i crash casuali durante il caricamento delle mappe
- Corretto un bug che causava la latenza massima (limitata da MaxTickSize) nelle partite multigiocatore quando il computer di uno dei giocatori era acceso da più di 24,86 giorni
- Corretta l'interfaccia della schermaglia, che assegnava una nazione errata nelle mappe predefinite quando si cambiava la posizione di un giocatore nella lista
- Il pennello 'Acqua' dell'editor con l'azione 'Shift' non modifica più l'altezza del terreno vicino
- Aggiunte decorazioni di ponti, accampamenti e rovine da Imperivm 2
- Migliorata la stabilità nelle partite multigiocatore

## 9. Correzioni al bioma invernale {#sec8}
- Sostituite le immagini delle minimappe con quelle estive
- Ridotta l'esposizione (luminosità) delle texture del terreno invernale
<p align="center">
    <img src="/capturas/captura_mapa_invierno_1.png" style="width: 75%;  max-width: 768px;" alt="Mappa invernale" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_decorados_inv_1.png" style="width: 75%;  max-width: 768px;" alt="Scenari invernali" loading="lazy">
</p>

## 10. Colori dei giocatori {#sec9}

Ridisegno dei colori dei giocatori per massimizzarne la distinzione visiva ed evitare confusione.

| ID | Colore originale | HEX originale | Nuovo colore | Nuovo HEX |
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

## E molti altri cambiamenti non documentati... {#more}
