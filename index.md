---
layout: default
title: "Imperivm 1 HD y Mod - La Amenaza Teutón (Parche Full HD)"
description: "Descarga el mod «La Amenaza Teutón» y el parche Imperivm 1 Full HD para Imperivm - La Guerra de las Galias: nuevas resoluciones HD, mejor IA, unidades, mapas aleatorios, soporte multi idioma y soporte Linux/Wine."
image: /capturas/AMENAZA_TEUTON.png
---

<p align="center">
    <img src="capturas/AMENAZA_TEUTON.png" style="width: 75%;  max-width: 768px;"  alt="Amenaza Teutón Diseño">
    <br>
    <b>Imperivm 1 - La Amenaza Teutón</b>
</p>

**Imperivm 1 HD** es un **mod** («La Amenaza Teutón») y un **parche Full HD** para *Imperivm - La Guerra de las Galias* (Celtic Kings / Imperivm 1). Añade nuevas **resoluciones HD** hasta 1920×1080, una **IA mejorada**, cambios en unidades, mapas aleatorios, **soporte multi idioma** (Español, Alemán, Francés, Inglés e Italiano) y soporte para jugar en **Linux/Wine**.

## Descargar

[Descargar el mod](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Descargar Imperivm 1 HD (Sin mod)](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Descargar mapas](https://github.com/JosueCA/La-Amenaza-Teuton)  

[Descargar en Moddb](https://www.moddb.com/members/sacredgames120)  

[Descargar Imperivm 2 HD](https://www.moddb.com/members/sacredgames120)
  
---

## Compatibilidad con aventuras
Este MOD no es 100% compatible con las aventuras. Para disfrutar de la experiencia original en Full HD, utilizar el parche independiente para el juego.

[Compatibilidad aventuras](https://github.com/JosueCA/La-Amenaza-Teuton/blob/master/AdventuresMod/README.md)

## Tabla de Contenidos

1. [Notas de Instalación](#1-notas-de-instalación)
1. [Compatibilidad de audio](#2-compatibilidad-de-audio)
1. [Nuevas resoluciones HD de pantalla](#3-nuevas-resoluciones-hd-de-pantalla)
1. [Soporte multilingüe](#4-soporte-multilingüe)
1. [Cambios generales](#5-cambios-generales)
1. [Mapas aleatorios](#6-mapas-aleatorios)
1. [Cambios en Unidades](#7-cambios-en-unidades)
   - [Especialidades](#especialidades)
   - [Efectos visuales de las especialidades](#efectos-visuales-de-las-especialidades)
   - [Unidades Galas](#unidades-galas)
   - [Unidades Romanas](#unidades-romanas)
   - [Unidades Teutón](#unidades-teutón)
   - [Otras Unidades](#otras-unidades)
   - [Héroes](#héroes)
1. [Mejoras al juego](#8-mejoras-al-juego)
   - [Nueva IA «LAT»](#nueva-ia-lat)
   - [Fortaleza](#fortaleza)
   - [Taverna Romana](#taverna-romana)
   - [Eliminado 'entrenamiento' de las unidades](#eliminado-entrenamiento-de-las-unidades)
   - [Formaciones](#formaciones)
   - [Druidas y Magia](#druidas-y-magia)
   - [Teutones](#teutones)
   - [Catapultas](#catapultas)
   - [Aldeas](#aldeas)
   - [Fortines](#fortines)
   - [Animales](#animales)
   - [Otros](#otros)
1. [Correcciones al bioma de invierno](#9-correcciones-al-bioma-de-invierno)
1. [Colores de Jugadores](#10-colores-de-jugadores)

---

## 1. Notas de Instalación

Este MOD se aplica directamente sobre la instalación del juego de "Imperivm 1: La Guerra de las Galias" (versión española de Celtic Kings: Rage of War). Reemplazando los archivos .pak y demás directorios/ficheros incluidos en el zip.

<details class="pasos" markdown="1">
<summary>Paso a paso</summary>

1. Abre el disco (o la imagen del CD) de *Imperivm - La Guerra de las Galias* y ejecuta `Instalar.exe`.

   <img src="capturas/install/zi1.png" class="paso" alt="Contenido del disco de Imperivm con Instalar.exe seleccionado" loading="lazy">

1. En el menú del instalador, pulsa **OPCIONES**.

   <img src="capturas/install/zi2.png" class="paso" alt="Menú del instalador de Imperivm" loading="lazy">

1. Elige la unidad y la carpeta de destino y pulsa **INSTALAR**.

   <img src="capturas/install/zi3.png" class="paso" alt="Selección de unidad y carpeta de destino" loading="lazy">

1. Confirma la ruta de instalación con **Aceptar**.

   <img src="capturas/install/zi4.png" class="paso" alt="Confirmación de la carpeta de instalación" loading="lazy">

1. Espera mientras se copian los archivos del juego.

   <img src="capturas/install/zi5.png" class="paso" alt="Progreso de la copia de archivos" loading="lazy">

1. Acepta con **Sí** el contrato de licencia de **Microsoft DirectX 8.1**, necesario para el juego.

   <img src="capturas/install/zi6.png" class="paso" alt="Contrato de licencia de Microsoft DirectX 8.1" loading="lazy">

1. Al terminar, el instalador muestra **JUGAR**: el juego ya está instalado. Ciérralo con **SALIR**.

   <img src="capturas/install/zi7.png" class="paso" alt="Instalador con la opción JUGAR tras instalar el juego" loading="lazy">

1. Descomprime el zip del MOD sobre la carpeta de instalación del juego, reemplazando los archivos existentes.

</details>

En Linux/Wine, revisa además [Compatibilidad de audio](#2-compatibilidad-de-audio).

## 2. Compatibilidad de audio

### Nuevo motor de audio

Nuevo motor de audio con soporte para varias interfaces (WASAPI, DirectSound y WinMM). Activado por defecto, con detección automática de la interfaz. (Configurable en `config.ini`)

### Wine

**Las últimas versiones de Wine no necesitan un prefijo 32bits separado. Soportan 32 y 64 bits en el mismo prefijo de 64 bits**

- **Wine**: WinXP 32 bits
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

- **Conversión de codec de audio**: Los archivos de voz de las unidades usaban el codec Microsoft ADPCM, que Wine no soporta completamente. Se convirtieron **120+ archivos WAV** de voces (galos, romanos y teutones) a PCM estándar para que funcionen correctamente en Linux/Wine.
- Convertidos archivos de audio de las aventuras 'Celtic Kings Adventure' y 'Tutorial'

## 3. Nuevas resoluciones HD de pantalla

| Resolución | Ancho | Alto | Aspecto |
|------------|-------|------|---------|
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

**Soporte para resoluciones 1600px-1920px disponible desde la versión "La Amenaza Teuton v0.4.0"**

## 4. Soporte multilingüe
- Añadidos idiomas Alemán, Francés, Inglés, e Italiano (además del Español). Configurable desde el fichero 'vxSettings.ini'
- Corregido volumen de las voces en inglés

## 5. Cambios generales
- Cambios en la música
- Pequeños ajustes en la interfaz del juego
- Vídeo introductorio reemplazado por el trailer (mejor calidad)
- Mejorada estabilidad del juego
- La barra de vida de las unidades (función activada con la tecla '~') se ha limitado a los Héroes. Limitado a las unidades del jugador

<p align="center">
    <img src="capturas/captura_salud.png" style="width: 75%;  max-width: 768px;" alt="Barra de salud" loading="lazy">
</p>

- Nuevo tipo de partida 'Total war' (Eliminación, pero con reclutamiento multiplicado x5)
- Nuevo widget de selección rápida
<p align="center">
    <img src="capturas/ui/widget-shorcut-zoomed.jpg" style="width: 75%;  max-height: 579px;" alt="Widget" loading="lazy">
</p>

## 6. Mapas aleatorios
- Modificada generación de mapas aleatoria
- Reutilizados assets para generar decorados más variados
- Aumentado el ratio de decoraciones
- Añadidos más decorados que generan items
- Disminuido número de ciervos
- Nuevos decorados para aldeas, fortalezas, fortínes y campamentos teutones
- Mejorada colocación aleatoria de montañas sobre las aldeas

<span id="galeria"></span>

<div class="galeria" markdown="0">
  <a href="#img-decorados1"><img src="capturas/mapas/thumbs/captura_decorados_1.png" alt="Decorados 1" loading="lazy"></a>
  <a href="#img-decorados2"><img src="capturas/mapas/thumbs/captura_decorados_2.png" alt="Decorados 2" loading="lazy"></a>
  <a href="#img-romecity"><img src="capturas/mapas/thumbs/rome_city.png" alt="Ciudad romana" loading="lazy"></a>
  <a href="#img-gaulcity"><img src="capturas/mapas/thumbs/gaul_city.png" alt="Ciudad gala" loading="lazy"></a>
  <a href="#img-outpost1"><img src="capturas/mapas/thumbs/outpost1.png" alt="Fortín 1" loading="lazy"></a>
  <a href="#img-outpost2"><img src="capturas/mapas/thumbs/outpost2.png" alt="Fortín 2" loading="lazy"></a>
  <a href="#img-village1"><img src="capturas/mapas/thumbs/village1.png" alt="Aldea 1" loading="lazy"></a>
  <a href="#img-village2"><img src="capturas/mapas/thumbs/village2.png" alt="Aldea 2" loading="lazy"></a>
  <a href="#img-village3"><img src="capturas/mapas/thumbs/village3.png" alt="Aldea 3" loading="lazy"></a>
  <a href="#img-village4"><img src="capturas/mapas/thumbs/village4.png" alt="Aldea 4" loading="lazy"></a>
  <a href="#img-village5"><img src="capturas/mapas/thumbs/village5.png" alt="Aldea 5" loading="lazy"></a>
  <a href="#img-village6"><img src="capturas/mapas/thumbs/village6.png" alt="Aldea 6" loading="lazy"></a>
</div>

<div class="lightbox" id="img-decorados1"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/captura_decorados_1.png" alt="Decorados 1" loading="lazy"></div>
<div class="lightbox" id="img-decorados2"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/captura_decorados_2.png" alt="Decorados 2" loading="lazy"></div>
<div class="lightbox" id="img-romecity"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/rome_city.png" alt="Ciudad romana" loading="lazy"></div>
<div class="lightbox" id="img-gaulcity"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/gaul_city.png" alt="Ciudad gala" loading="lazy"></div>
<div class="lightbox" id="img-outpost1"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/outpost1.png" alt="Fortín 1" loading="lazy"></div>
<div class="lightbox" id="img-outpost2"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/outpost2.png" alt="Fortín 2" loading="lazy"></div>
<div class="lightbox" id="img-village1"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/village1.png" alt="Aldea 1" loading="lazy"></div>
<div class="lightbox" id="img-village2"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/village2.png" alt="Aldea 2" loading="lazy"></div>
<div class="lightbox" id="img-village3"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/village3.png" alt="Aldea 3" loading="lazy"></div>
<div class="lightbox" id="img-village4"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/village4.png" alt="Aldea 4" loading="lazy"></div>
<div class="lightbox" id="img-village5"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/village5.png" alt="Aldea 5" loading="lazy"></div>
<div class="lightbox" id="img-village6"><a href="#galeria" class="cerrar">&times;</a><img src="capturas/mapas/village6.png" alt="Aldea 6" loading="lazy"></div>

---

## 7. Cambios en Unidades

## Especialidades

- La especialidad 'golpe letal/death blow' no afecta a los héroes
- Corregida especialidad 'attack skill' que no funcionaba

| Especialidad | Valor | Descripción |
|---|---|---|
| `ataque continuo/attack skill` | +1 | Aumenta el daño con cada golpe contra el mismo objetivo |
| `berserk/berserker` | 100 % | Aumenta el daño al perder salud |
| `carga/charge` | 600 % / 8 000 ms | Multiplica el daño por 600% con una recarga de 8 segundos sin atacar |
| `daño conjunto/trample damage` | 50 % | La unidad inflige un 50 % de daño a los enemigos cercanos |
| `daño expansivo/spread damage` | 175 % | El daño aumenta cuanto más dañado esté el objetivo |
| `daño reflejado/spike damage` | 25 % | Devuelve 25% del daño al atacante. |
| `golpe del vampiro/vampire blow` | 33 % | Recupera el 33 % del daño infligido como salud propia. |
| `golpe letal/death blow` | 33 % | Cuando el objetivo tiene menos del 33% de vida el siguiente ataque lo mata de un golpe. |
| `libertad/freedom` | — | No permite unirse a los héroes. |
| `posición defensiva/defensive stand` | — | Resiste el primer golpe del atacante |

---

## Efectos visuales de las especialidades

| Especialidad | Efecto | Se muestra sobre | Cuándo aparece |
|---|---|---|---|
| `ataque continuo/attack skill` | <img src="capturas/feedbacks/Penetration.png" class="fbstrip" alt="Efecto ataque continuo" loading="lazy"> | Atacante | En cada golpe |
| `berserk/berserker` | <img src="capturas/feedbacks/Rage.png" class="fbstrip" alt="Efecto berserker" loading="lazy"> | Atacante | En cada golpe |
| `carga/charge` | <img src="capturas/feedbacks/Charge.png" class="fbstrip" alt="Efecto carga" loading="lazy"> | Atacante | **Solo** cuando la carga está recargada |
| `daño conjunto/trample damage` | <img src="capturas/feedbacks/TripleStrike.png" class="fbstrip" alt="Efecto daño conjunto" loading="lazy"> | Atacante | En cada golpe |
| `daño expansivo/spread damage` | <img src="capturas/feedbacks/BleedingAttack.png" class="fbstrip" alt="Efecto daño expansivo" loading="lazy"> | Objetivo | En cada golpe |
| `daño reflejado/spike damage` | <img src="capturas/feedbacks/SpikedArmor.png" class="fbstrip" alt="Efecto daño reflejado" loading="lazy"> | Defensor | En cada golpe |
| `golpe del vampiro/vampire blow` | <img src="capturas/feedbacks/StaminaBoost.png" class="fbstrip" alt="Efecto golpe del vampiro" loading="lazy"> | Atacante | En cada golpe |
| `golpe letal/death blow` | <img src="capturas/feedbacks/Revenge.png" class="fbstrip" alt="Efecto golpe letal" loading="lazy"> | Objetivo | **Solo** en el golpe que remata |
| `posición defensiva/defensive stand` | <img src="capturas/feedbacks/DefensiveStand.png" class="fbstrip" alt="Efecto posición defensiva" loading="lazy"> | Defensor | **Solo** en el primer golpe del atacante |

`libertad/freedom` es una habilidad pasiva y no tiene efecto visual.

---

## Unidades Galas

| Unidad | Salud | Ataque | Tipo de ataque | Def. Corte | Def. Pierce | Velocidad | Rango | Especialidad |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="capturas/iconos/gswordsman.png" class="icono" alt="Guerrero" loading="lazy"><span>Guerrero</span></span> | 160 | 10–18 | slash | 0 | 0 | 100 | — | — |
| <span class="unidad"><img src="capturas/iconos/garcher.png" class="icono" alt="Arquero" loading="lazy"><span>Arquero</span></span> | 100 | 6–10 | pierce | 0 | 0 | 80 | 400 | daño expansivo |
| <span class="unidad"><img src="capturas/iconos/gaxeman.png" class="icono" alt="Guerrero con hacha" loading="lazy"><span>Guerrero con hacha</span></span> | 280 | 16–24 | slash | 2 | 0 | 80 | — | daño conjunto |
| <span class="unidad"><img src="capturas/iconos/gspearman.png" class="icono" alt="Lancero" loading="lazy"><span>Lancero</span></span> | 300 | 16–24, x1.5 vs Caballería | pierce | 6 | 6 | 80 | — | posición defensiva, daño expansivo |
| <span class="unidad"><img src="capturas/iconos/ghorseman.png" class="icono" alt="Jinete" loading="lazy"><span>Jinete</span></span> | 380 | 20–28 | slash | 0 | 0 | 140 | — | carga |
| <span class="unidad"><img src="capturas/iconos/gwfighter.png" class="icono" alt="Mujer guerrera" loading="lazy"><span>Mujer guerrera</span></span> | 340 | 18–36 | slash | 0 | 8 | 80 | — | golpe del vampiro |
| <span class="unidad"><img src="capturas/iconos/gdruid.png" class="icono" alt="Druida" loading="lazy"><span>Druida</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="capturas/iconos/gvikinglord.png" class="icono" alt="Jefe Normando" loading="lazy"><span>Jefe Normando</span></span> | 3000 | 42–84 | slash | 6 | 6 | 80 | — | libertad, carga |
| <span class="unidad"><img src="capturas/iconos/ieliteguard.png" class="icono" alt="Guardia de élite" loading="lazy"><span>Guardia de élite</span></span> | 350 | 18–28 | slash | 6 | 6 | 80 | — | posición defensiva, ataque continuo |

---

## Unidades Romanas

| Unidad | Salud | Ataque | Tipo de ataque | Def. Corte | Def. Pierce | Velocidad | Rango | Especialidad |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="capturas/iconos/rswordsman.png" class="icono" alt="Legionario" loading="lazy"><span>Legionario</span></span> | 200 | 13–17 | slash | 0 | 5 | 80 | — | posición defensiva |
| <span class="unidad"><img src="capturas/iconos/rarcher.png" class="icono" alt="Arquero" loading="lazy"><span>Arquero</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | daño expansivo |
| <span class="unidad"><img src="capturas/iconos/rgladiator.png" class="icono" alt="Gladiador" loading="lazy"><span>Gladiador</span></span> | 255 | 21–21 | pierce | 5 | 0 | 100 | — | daño expansivo |
| <span class="unidad"><img src="capturas/iconos/rspearman.png" class="icono" alt="Princep" loading="lazy"><span>Princep</span></span> | 275 | 15–23, x1.5 vs Caballería | slash | 7 | 15 | 80 | — | posición defensiva, daño reflejado |
| <span class="unidad"><img src="capturas/iconos/rhorseman.png" class="icono" alt="Equite" loading="lazy"><span>Equite</span></span> | 330 | 17–25 | slash | 3 | 3 | 140 | — | carga |
| <span class="unidad"><img src="capturas/iconos/rpraetorian.png" class="icono" alt="Pretoriano" loading="lazy"><span>Pretoriano</span></span> | 475 | 27–47 | pierce | 7 | 7 | 80 | — | ataque continuo, golpe letal |
| <span class="unidad"><img src="capturas/iconos/rpriest.png" class="icono" alt="Sacerdote" loading="lazy"><span>Sacerdote</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="capturas/iconos/rliberatus.png" class="icono" alt="Liberati" loading="lazy"><span>Liberati</span></span> | 300 | 30–30 | slash | 0 | 0 | 120 | — | berserker |
| <span class="unidad"><img src="capturas/iconos/cwarelephant.png" class="icono" alt="Elefante de guerra" loading="lazy"><span>Elefante de guerra</span></span> | 2000 | 30–40 | slash | 10 | 10 | 60 | — | libertad, daño conjunto |

### Elefante de guerra
- Las unidades a distancia infligen x1.25 contra Elefantes de guerra

---

## Unidades Teutón

| Unidad | Salud | Ataque | Tipo de ataque | Def. Corte | Def. Pierce | Velocidad | Rango | Especialidad |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="capturas/iconos/teutonarcher.png" class="icono" alt="Arquero Teutón" loading="lazy"><span>Arquero Teutón</span></span> | 200 | 8–18, x2 vs Mulas | pierce | 0 | 0 | 160 | 400 | — |
| <span class="unidad"><img src="capturas/iconos/teutonmetal.png" class="icono" alt="Jinete Teutón" loading="lazy"><span>Jinete Teutón</span></span> | 250 | 10–20, x2 vs Mulas | slash | 0 | 0 | 160 | — | daño conjunto |
| <span class="unidad"><img src="capturas/iconos/garcher.png" class="icono" alt="Arquero Galo Teutón" loading="lazy"><span>Arquero Galo Teutón</span></span> | 100 | 6–12 | pierce | 2 | 2 | 80 | 400 | — |
| <span class="unidad"><img src="capturas/iconos/gswordsman.png" class="icono" alt="Espadachín Galo Teutón" loading="lazy"><span>Espadachín Galo Teutón</span></span> | 240 | 10–18 | slash | 2 | 2 | 100 | — | — |
| <span class="unidad"><img src="capturas/iconos/rarcher.png" class="icono" alt="Arquero Romano Teutón" loading="lazy"><span>Arquero Romano Teutón</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | — |
| <span class="unidad"><img src="capturas/iconos/rswordsman.png" class="icono" alt="Hastatus Romano Teutón" loading="lazy"><span>Hastatus Romano Teutón</span></span> | 240 | 13–17 | slash | 3 | 3 | 80 | — | — |

### Arquero teutón
- Configurada la animación 'taunt' de la unidad

---

## Otras Unidades

| Unidad | Salud | Ataque | Tipo de ataque | Def. Corte | Def. Pierce | Velocidad | Rango | Especialidad |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="capturas/iconos/imilitiaman.png" class="icono" alt="Miliciano" loading="lazy"><span>Miliciano</span></span> | 180 | 6–12 | slash | 4 | 0 | 80 | — | — |
| <span class="unidad"><img src="capturas/iconos/iarcher.png" class="icono" alt="Arquero íbero" loading="lazy"><span>Arquero</span></span> | 180 | 12–18 | pierce | 4 | 8 | 80 | 400 | — |
| <span class="unidad"><img src="capturas/iconos/islinger.png" class="icono" alt="Hondero" loading="lazy"><span>Hondero</span></span> | 200 | 20–30 | pierce | 0 | 0 | 100 | 300 | — |
| <span class="unidad"><img src="capturas/iconos/idefender.png" class="icono" alt="Defensor" loading="lazy"><span>Defensor</span></span> | 200 | 14–24 | pierce | 8 | 8 | 80 | — | posición defensiva |
| <span class="unidad"><img src="capturas/iconos/icavalry.png" class="icono" alt="Caballería ibera" loading="lazy"><span>Caballería</span></span> | 240 | 20–30 | slash | 6 | 6 | 160 | — | carga |
| <span class="unidad"><img src="capturas/iconos/imountaineer.png" class="icono" alt="Montañés" loading="lazy"><span>Montañés</span></span> | 400 | 24–48 | slash | 4 | 0 | 80 | — | libertad |
| <span class="unidad"><img src="capturas/iconos/teutonwolf.png" class="icono" alt="Lobo teutón" loading="lazy"><span>Lobo teutón</span></span> | 400 | 22–26 | slash | 8 | 4 | 160 | — | carga, daño conjunto |

---

### Héroes
- Modificaciones en las estadísticas base de héroes (más vida)
- Más vida por nivel
- Reutilizados assets de héroes para generar más héroes aleatorios
<p align="center">
    <img src="capturas/captura_heroes_1.png" style="width: 75%; max-width: 768px;" alt="Defensores del fortín" loading="lazy">
</p>

- Los héroes pueden ordenar a los Druidas/Sacerdotes asignados a lanzar sus hechizos
- Los héroes pueden ordenar a sus unidades construir una catapulta
- NOTA: dar una nueva orden desde los héroes, cancela la orden anterior de catapulta/hechizos
<p align="center">
    <img src="capturas/captura_heroe_hechizos.png" style="width: 75%; max-width: 768px;" alt="Héroes lanzan hechizos" loading="lazy">
</p>

- Modificado el reclutamiento aleatorio de los héroes, ahora es secuencial con el inicio aleatorio, para maximizar la distinción entre los assets/sprites de cada héroe en la partida.

## 8. Mejoras al juego

### Nueva IA «LAT»
- Mayor dificultad al jugar contra la IA
- Añadida una estrategia militar inicial
- Añadida una estrategia de exploración inicial
- Corregidos casos específicos en el algoritmo de asedio que mantenía a los ejércitos atascados sin poder asediar la fortaleza enemiga
- Mejorado algoritmo de investigación de tecnologías. La IA investiga las mejoras en el coliseo, taberna, templo
- Mejorado reclutamiento de las unidades especiales
- Mejorado reclutamiento de las unidades militares
- Mejorado cálculo y respuesta a las amenazas
- Mejorada gestión de objetivos, IA más agresiva
- Mejorado sistema de monitoreo y control de ejércitos
- Mejorada el sistema de retirada de los ejércitos
- Mejorado sistema de suministros de comida de los ejércitos
- Mejorado sistema de teletransporte (cuevas)
- Mejorado el uso de las ruinas
- Mejorado el sistema de recogida y uso de items  
- Reimplementado comercio de comida con los outpost galos
<p align="center">
    <img src="capturas/captura_ia_items_1.png" style="width: 75%;  max-width: 768px;" alt="Sistema de items" loading="lazy">
</p>

### Fortaleza
- Corregidas animaciones de campesinos en las fortalezas romanas, además de añadir los edificios faltantes
- Añadidos legionario (Roma)/arquero galo (Galo) a las animaciones de campesinos
- Ajustados parámetros de ataque de torres y puertas. Las puertas también disparan flechas.
- Añadida notificación cuando termina la investigación de una tecnología
- Desde el foro se pueden ejecutar los hechizos de los altares (el altar se elige aleatoriamente)
<p align="center">
    <img src="capturas/Captura_foro.png" style="width: 75%;  max-width: 768px;" alt="Hechizos en el foro" loading="lazy">
</p>

### Taverna Romana
- Nueva tecnología 'Campeonatos'
- Modificada tecnología 'Importar caballos'

### Eliminado 'entrenamiento' de las unidades
- Las unidades del cuartel se generan con el nivel de 'entrenamiento' investigado
<p align="center">
    <img src="capturas/captura_cuartel_1.png" style="width: 75%;  max-width: 768px;" alt="Entrenamiento" loading="lazy">
</p>

### Formaciones
- Reducido el 'radio' de las unidades en formación. Las unidades en formaciones están más cerca entre sí.
- Modificadas estructuras de las formaciones
<p align="center">
    <img src="capturas/Captura_formaciones.png" style="width: 75%;  max-width: 768px;" alt="Formaciones" loading="lazy">
</p>

### Druidas y Magia
- Reducido daño de los hechizos
- Reimplementada la 'Nube Venenosa' (sacerdote) para que no dañe a unidades amigas
- Ajustes al sistema de reclutamiento de druidas
- La IA utiliza los altares durante las partidas aleatorias
- La IA utiliza los hechizos en el combate (Espíritu Vampiro, Nube venenosa)
<p align="center">
    <img src="capturas/Captura6_ia_nube.png" style="width: 75%;  max-width: 768px;" alt="Hechizos de IA" loading="lazy">
</p>

### Teutones
- Mejorada IA de los ejércitos teutones
- Los Teutones pueden capturar fortalezas de los jugadores
<p align="center">
    <img src="capturas/Captura4.png" style="width: 75%;  max-width: 768px;" alt="Amenaza Teutón" loading="lazy">
</p>

### Catapultas
- Reducido límite de unidades de 10 a 5

### Aldeas
- Las aldeas producen campesinos automáticamente junto a las mulas de comida
- Corregido bug de campesinos/mulas atascados para siempre en las puertas de la fortaleza
- Mejorada captura de las aldeas, no es posible capturar la aldea capturando sus 'casas'

### Fortines
- Añadidos defensores iniciales a los fortines
<p align="center">
    <img src="capturas/captura_fortines_1.png" style="width: 75%;  max-width: 768px;" alt="Fortines Galos" loading="lazy">
</p>
<p align="center">
    <img src="capturas/captura_fortines_2.png" style="width: 75%;  max-width: 768px;" alt="Defensores del fortín" loading="lazy">
</p>


### Animales
- Corregido bug de los ciervos atascados en los bordes del mapa

### Otros
- Corregidos mensajes 'Handle Leak' en el vx.log
- Corregidos mensajes 'assets/interface/settlement icon' en vx.log
- Corregidos BONUS.XML que no tienen efecto aleatoriamente
- Corregidos crashes aleatorios al cargar mapas
- Corregido un error que provocaba la latencia máxima (limitada por MaxTickSize) en las partidas multijugador cuando el tiempo de actividad del ordenador de uno de los jugadores superaba los 24,86 días
- Corregida la interfaz de escaramuza, que asignaba una nación incorrecta en los mapas predefinidos al cambiar la posición de un jugador en la lista
- El pincel 'Agua' del editor con la acción 'Shift' ya no modifica la altura del terreno cercano
- Añadidos decorados de puentes, campamentos y ruinas de Imperivm 2
- Mejorada estabilidad en partidas multijugador

## 9. Correcciones al bioma de invierno
- Reemplazadas las imágenes de los minimap por las de verano
- Reducida la exposición (brillo) de las texturas de terreno de invierno
<p align="center">
    <img src="capturas/captura_mapa_invierno_1.png" style="width: 75%;  max-width: 768px;" alt="Mapa invierno" loading="lazy">
</p>
<p align="center">
    <img src="capturas/captura_decorados_inv_1.png" style="width: 75%;  max-width: 768px;" alt="Decorados invierno" loading="lazy">
</p>


## 10. Colores de Jugadores

Rediseño de los colores de los jugadores para maximizar la distinción visual entre ellos y evitar interferencias.

| ID    | Color original | HEX original | Color nuevo | HEX nuevo  |
|-------|---------------|--------------|-------------|------------|
| id1   | ![](capturas/colores/id1_old.png) | `#FF1717` | ![](capturas/colores/id1.png) | `#FF2222` |
| id2   | ![](capturas/colores/id2_old.png) | `#FFFF00` | ![](capturas/colores/id2.png) | `#CCBB00` |
| id3   | ![](capturas/colores/id3_old.png) | `#00FF00` | ![](capturas/colores/id3.png) | `#00BB77` |
| id4   | ![](capturas/colores/id4_old.png) | `#00E8E8` | ![](capturas/colores/id4.png) | `#00E8E8` |
| id5   | ![](capturas/colores/id5_old.png) | `#EDA0FF` | ![](capturas/colores/id5.png) | `#007700` |
| id6   | ![](capturas/colores/id6_old.png) | `#B6E686` | ![](capturas/colores/id6.png) | `#9900CC` |
| id7   | ![](capturas/colores/id7_old.png) | `#AE0000` | ![](capturas/colores/id7.png) | `#FF8800` |
| id8   | ![](capturas/colores/id8_old.png) | `#F99B20` | ![](capturas/colores/id8.png) | `#66AA00` |
| id9   | ![](capturas/colores/id9_old.png) | `#109B12` | ![](capturas/colores/id9.png) | `#0099CC` |
| id10  | ![](capturas/colores/id10_old.png) | `#0000F8` | ![](capturas/colores/id10.png) | `#555555` |
| id11  | ![](capturas/colores/id11_old.png) | `#C40DC6` | ![](capturas/colores/id11.png) | `#FF44CC` |
| id12  | ![](capturas/colores/id12_old.png) | `#9F9A00` | ![](capturas/colores/id12.png) | `#CC0055` |
| id13  | ![](capturas/colores/id13_old.png) | `#808080` | ![](capturas/colores/id13.png) | `#111111` |


## Y muchos más cambios sin documentar...
