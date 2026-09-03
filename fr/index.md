---
layout: default
lang: "fr"
permalink: /fr/
title: "Imperivm 1 HD et Mod - La Menace Teutonne (patch Full HD)"
description: "Téléchargez le mod «La Amenaza Teutón» (La Menace Teutonne) et le patch Full HD pour Imperivm - La Guerra de las Galias : nouvelles résolutions HD, meilleure IA, unités, cartes aléatoires, support multilingue et support Linux/Wine."
banner_title: "Imperivm 1 - La Menace Teutonne + patch Full HD"
banner_tagline: "Imperivm 1 HD : le mod «La Amenaza Teutón» et le patch Full HD pour Imperivm - La Guerra de las Galias. Nouvelles résolutions HD, IA améliorée, unités, cartes, support multilingue et support Linux/Wine."
image: /capturas/AMENAZA_TEUTON.png
---

<p align="center">
    <img src="/capturas/AMENAZA_TEUTON.png" style="width: 75%;  max-width: 768px;" alt="Illustration La Menace Teutonne">
    <br>
    <b>Imperivm 1 - La Menace Teutonne</b>
</p>

**Imperivm 1 HD** est un **mod** («La Amenaza Teutón», La Menace Teutonne) et un **patch Full HD** pour *Imperivm - La Guerra de las Galias* (Celtic Kings / Imperivm 1). Il ajoute de nouvelles **résolutions HD** jusqu'à 1920×1080, une **IA améliorée**, des changements d'unités, des cartes aléatoires, un **support multilingue** (espagnol, allemand, français, anglais et italien) et la prise en charge de **Linux/Wine**.

## Téléchargements {#downloads}

[Télécharger le mod](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Télécharger Imperivm 1 HD (sans mod)](https://github.com/JosueCA/La-Amenaza-Teuton/releases)  

[Télécharger les cartes](https://github.com/JosueCA/La-Amenaza-Teuton)  

[Télécharger sur ModDB](https://www.moddb.com/mods/la-amenaza-teuton)  

### Notes d'installation {#install}

Ce MOD s'applique directement par-dessus une installation existante de "Imperivm 1: La Guerra de las Galias" (la version espagnole de Celtic Kings: Rage of War), en remplaçant les fichiers .pak ainsi que les autres dossiers/fichiers inclus dans le zip.

---

## Compatibilité avec les aventures {#adventures}

Ce MOD n'est pas compatible à 100 % avec les aventures. Pour profiter de l'expérience originale en Full HD, utilisez le patch autonome pour le jeu.

[Compatibilité avec les aventures](https://github.com/JosueCA/La-Amenaza-Teuton/blob/master/AdventuresMod/README.md)

## Table des matières {#toc}

1. [Compatibilité Wine](#sec1)
1. [Nouvelles résolutions d'écran HD](#sec2)
1. [Support multilingue](#sec3)
1. [Changements généraux](#sec4)
1. [Cartes aléatoires](#sec5)
1. [Changements d'unités](#sec6)
   - [Compétences](#specialities)
   - [Effets visuels des compétences](#visual-effects)
   - [Unités gauloises](#gaul-units)
   - [Unités romaines](#roman-units)
   - [Unités teutonnes](#teuton-units)
   - [Autres unités](#other-units)
   - [Héros](#heroes)
1. [Améliorations du jeu](#sec7)
   - [Nouvelle IA «LAT»](#lat-ai)
   - [Place forte](#stronghold)
   - [Taverne romaine](#tavern)
   - ['Entraînement' des unités supprimé](#training)
   - [Formations](#formations)
   - [Druides et magie](#magic)
   - [Teutons](#teutons)
   - [Catapultes](#catapults)
   - [Villages](#villages)
   - [Avant-postes](#outposts)
   - [Animaux](#animals)
   - [Divers](#other)
1. [Corrections du biome d'hiver](#sec8)
1. [Couleurs des joueurs](#sec9)

---

## 1. Compatibilité Wine {#sec1}
- **Wine** : WinXP 32 bits
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

- **Conversion du codec audio** : les fichiers de voix des unités utilisaient le codec Microsoft ADPCM, que Wine ne prend pas totalement en charge. **Plus de 120 fichiers WAV** de voix (Gaulois, Romains et Teutons) ont été convertis en PCM standard pour qu'ils fonctionnent correctement sous Linux/Wine.
- Fichiers audio des aventures 'Celtic Kings Adventure' et 'Tutorial' convertis

## 2. Nouvelles résolutions d'écran HD {#sec2}

| Résolution | Largeur | Hauteur | Format |
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

**Prise en charge des résolutions 1600px-1920px disponible à partir de la version "La Amenaza Teuton v0.4.0"**

## 3. Support multilingue {#sec3}
- Ajout de l'allemand, du français, de l'anglais et de l'italien (en plus de l'espagnol). Configurable depuis le fichier 'vxSettings.ini'
- Volume des voix anglaises corrigé

## 4. Changements généraux {#sec4}
- Changements dans la musique
- Petits ajustements de l'interface du jeu
- Vidéo d'introduction remplacée par la bande-annonce (meilleure qualité)
- Stabilité du jeu améliorée
- La barre de vie des unités (touche '~') est désormais limitée aux héros, et uniquement aux unités du joueur

<p align="center">
    <img src="/capturas/captura_salud.png" style="width: 75%;  max-width: 768px;" alt="Barre de vie" loading="lazy">
</p>

- Nouveau type de partie 'Total war' (Élimination, mais avec un recrutement multiplié par 5)

## 5. Cartes aléatoires {#sec5}
- Génération des cartes aléatoires revue
- Assets réutilisés pour générer des décors plus variés
- Proportion de décors augmentée
- Ajout de décors supplémentaires qui génèrent des objets
- Nombre de cerfs réduit
- Nouveaux décors pour les villages, les places fortes, les avant-postes et les camps teutons
- Placement aléatoire des montagnes sur les villages amélioré

<span id="galeria"></span>

<div class="galeria" markdown="0">
  <a href="#img-decorados1"><img src="/capturas/mapas/thumbs/captura_decorados_1.png" alt="Décors 1" loading="lazy"></a>
  <a href="#img-decorados2"><img src="/capturas/mapas/thumbs/captura_decorados_2.png" alt="Décors 2" loading="lazy"></a>
  <a href="#img-romecity"><img src="/capturas/mapas/thumbs/rome_city.png" alt="Cité romaine" loading="lazy"></a>
  <a href="#img-gaulcity"><img src="/capturas/mapas/thumbs/gaul_city.png" alt="Cité gauloise" loading="lazy"></a>
  <a href="#img-outpost1"><img src="/capturas/mapas/thumbs/outpost1.png" alt="Avant-poste 1" loading="lazy"></a>
  <a href="#img-outpost2"><img src="/capturas/mapas/thumbs/outpost2.png" alt="Avant-poste 2" loading="lazy"></a>
  <a href="#img-village1"><img src="/capturas/mapas/thumbs/village1.png" alt="Village 1" loading="lazy"></a>
  <a href="#img-village2"><img src="/capturas/mapas/thumbs/village2.png" alt="Village 2" loading="lazy"></a>
  <a href="#img-village3"><img src="/capturas/mapas/thumbs/village3.png" alt="Village 3" loading="lazy"></a>
  <a href="#img-village4"><img src="/capturas/mapas/thumbs/village4.png" alt="Village 4" loading="lazy"></a>
  <a href="#img-village5"><img src="/capturas/mapas/thumbs/village5.png" alt="Village 5" loading="lazy"></a>
  <a href="#img-village6"><img src="/capturas/mapas/thumbs/village6.png" alt="Village 6" loading="lazy"></a>
</div>

<div class="lightbox" id="img-decorados1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_1.png" alt="Décors 1" loading="lazy"></div>
<div class="lightbox" id="img-decorados2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/captura_decorados_2.png" alt="Décors 2" loading="lazy"></div>
<div class="lightbox" id="img-romecity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/rome_city.png" alt="Cité romaine" loading="lazy"></div>
<div class="lightbox" id="img-gaulcity"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/gaul_city.png" alt="Cité gauloise" loading="lazy"></div>
<div class="lightbox" id="img-outpost1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost1.png" alt="Avant-poste 1" loading="lazy"></div>
<div class="lightbox" id="img-outpost2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/outpost2.png" alt="Avant-poste 2" loading="lazy"></div>
<div class="lightbox" id="img-village1"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village1.png" alt="Village 1" loading="lazy"></div>
<div class="lightbox" id="img-village2"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village2.png" alt="Village 2" loading="lazy"></div>
<div class="lightbox" id="img-village3"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village3.png" alt="Village 3" loading="lazy"></div>
<div class="lightbox" id="img-village4"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village4.png" alt="Village 4" loading="lazy"></div>
<div class="lightbox" id="img-village5"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village5.png" alt="Village 5" loading="lazy"></div>
<div class="lightbox" id="img-village6"><a href="#galeria" class="cerrar">&times;</a><img src="/capturas/mapas/village6.png" alt="Village 6" loading="lazy"></div>

---

## 6. Changements d'unités {#sec6}

## Compétences {#specialities}

- La compétence 'coup mortel' n'affecte plus les héros
- Correction de la compétence 'compétence en attaque', qui ne fonctionnait pas

| Compétence | Valeur | Description |
|---|---|---|
| `compétence en attaque/attack skill` | +1 | Les dégâts augmentent à chaque coup porté sur la même cible |
| `berserker` | 100 % | Les dégâts augmentent à mesure que la santé diminue |
| `charge` | 600 % / 8 000 ms | Multiplie les dégâts par 600 % avec un temps de recharge de 8 secondes sans attaquer |
| `dégâts d'écrasement/trample damage` | 50 % | L'unité inflige 50 % de dégâts aux ennemis proches |
| `dégâts étendus/spread damage` | 175 % | Les dégâts augmentent selon les blessures de la cible |
| `dégâts des pointes/spike damage` | 25 % | Renvoie 25 % des dégâts à l'attaquant. |
| `coup vampirique/vampire blow` | 33 % | Récupère 33 % des dégâts infligés sous forme de santé. |
| `coup mortel/death blow` | 33 % | Quand la cible est sous 33 % de vie, l'attaque suivante la tue d'un seul coup. |
| `liberté/freedom` | — | Ne peut pas rejoindre les héros. |
| `posture défensive/defensive stand` | — | Résiste au premier coup de l'attaquant |

---

## Effets visuels des compétences {#visual-effects}

| Compétence | Effet | Affiché sur | Quand il apparaît |
|---|---|---|---|
| `compétence en attaque/attack skill` | <img src="/capturas/feedbacks/Penetration.png" class="fbstrip" alt="Effet compétence en attaque" loading="lazy"> | Attaquant | À chaque coup |
| `berserker` | <img src="/capturas/feedbacks/Rage.png" class="fbstrip" alt="Effet berserker" loading="lazy"> | Attaquant | À chaque coup |
| `charge` | <img src="/capturas/feedbacks/Charge.png" class="fbstrip" alt="Effet charge" loading="lazy"> | Attaquant | **Uniquement** quand la charge est rechargée |
| `dégâts d'écrasement/trample damage` | <img src="/capturas/feedbacks/TripleStrike.png" class="fbstrip" alt="Effet dégâts d'écrasement" loading="lazy"> | Attaquant | À chaque coup |
| `dégâts étendus/spread damage` | <img src="/capturas/feedbacks/BleedingAttack.png" class="fbstrip" alt="Effet dégâts étendus" loading="lazy"> | Cible | À chaque coup |
| `dégâts des pointes/spike damage` | <img src="/capturas/feedbacks/SpikedArmor.png" class="fbstrip" alt="Effet dégâts des pointes" loading="lazy"> | Défenseur | À chaque coup |
| `coup vampirique/vampire blow` | <img src="/capturas/feedbacks/StaminaBoost.png" class="fbstrip" alt="Effet coup vampirique" loading="lazy"> | Attaquant | À chaque coup |
| `coup mortel/death blow` | <img src="/capturas/feedbacks/Revenge.png" class="fbstrip" alt="Effet coup mortel" loading="lazy"> | Cible | **Uniquement** sur le coup fatal |
| `posture défensive/defensive stand` | <img src="/capturas/feedbacks/DefensiveStand.png" class="fbstrip" alt="Effet posture défensive" loading="lazy"> | Défenseur | **Uniquement** au premier coup de l'attaquant |

`liberté` est une capacité passive et n'a pas d'effet visuel.

---

## Unités gauloises {#gaul-units}

| Unité | Santé | Attaque | Type d'attaque | Déf. taille | Déf. perce | Vitesse | Portée | Compétence |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Épéiste" loading="lazy"><span>Épéiste</span></span> | 160 | 10–18 | slash | 0 | 0 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Archer" loading="lazy"><span>Archer</span></span> | 100 | 6–10 | pierce | 0 | 0 | 80 | 400 | dégâts étendus |
| <span class="unidad"><img src="/capturas/iconos/gaxeman.png" class="icono" alt="Porteur de hache" loading="lazy"><span>Porteur de hache</span></span> | 280 | 16–24 | slash | 2 | 0 | 80 | — | dégâts d'écrasement |
| <span class="unidad"><img src="/capturas/iconos/gspearman.png" class="icono" alt="Lancier" loading="lazy"><span>Lancier</span></span> | 300 | 16–24, x1,5 contre Cavalerie | pierce | 6 | 6 | 80 | — | posture défensive, dégâts étendus |
| <span class="unidad"><img src="/capturas/iconos/ghorseman.png" class="icono" alt="Cavalier" loading="lazy"><span>Cavalier</span></span> | 380 | 20–28 | slash | 0 | 0 | 140 | — | charge |
| <span class="unidad"><img src="/capturas/iconos/gwfighter.png" class="icono" alt="Guerrière" loading="lazy"><span>Guerrière</span></span> | 340 | 18–36 | slash | 0 | 8 | 80 | — | coup vampirique |
| <span class="unidad"><img src="/capturas/iconos/gdruid.png" class="icono" alt="Druide" loading="lazy"><span>Druide</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/gvikinglord.png" class="icono" alt="Seigneur viking" loading="lazy"><span>Seigneur viking</span></span> | 3000 | 42–84 | slash | 6 | 6 | 80 | — | liberté, charge |
| <span class="unidad"><img src="/capturas/iconos/ieliteguard.png" class="icono" alt="Garde d'élite" loading="lazy"><span>Garde d'élite</span></span> | 350 | 18–28 | slash | 10 | 10 | 80 | — | posture défensive, compétence en attaque |

---

## Unités romaines {#roman-units}

| Unité | Santé | Attaque | Type d'attaque | Déf. taille | Déf. perce | Vitesse | Portée | Compétence |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Recrue" loading="lazy"><span>Recrue</span></span> | 200 | 13–17 | slash | 0 | 5 | 80 | — | posture défensive |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Archer" loading="lazy"><span>Archer</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | dégâts étendus |
| <span class="unidad"><img src="/capturas/iconos/rgladiator.png" class="icono" alt="Gladiateur" loading="lazy"><span>Gladiateur</span></span> | 255 | 21–21 | pierce | 5 | 0 | 100 | — | dégâts étendus |
| <span class="unidad"><img src="/capturas/iconos/rspearman.png" class="icono" alt="Vétéran" loading="lazy"><span>Vétéran</span></span> | 275 | 15–23, x1,5 contre Cavalerie | slash | 7 | 15 | 80 | — | posture défensive, dégâts des pointes |
| <span class="unidad"><img src="/capturas/iconos/rhorseman.png" class="icono" alt="Éclaireur" loading="lazy"><span>Éclaireur</span></span> | 330 | 17–25 | slash | 3 | 3 | 140 | — | charge |
| <span class="unidad"><img src="/capturas/iconos/rpraetorian.png" class="icono" alt="Prétorien" loading="lazy"><span>Prétorien</span></span> | 475 | 27–47 | pierce | 7 | 7 | 80 | — | compétence en attaque, coup mortel |
| <span class="unidad"><img src="/capturas/iconos/rpriest.png" class="icono" alt="Prêtre" loading="lazy"><span>Prêtre</span></span> | 120 | — | — | — | — | 60 | 200 | — |
| <span class="unidad"><img src="/capturas/iconos/rliberatus.png" class="icono" alt="Affranchi" loading="lazy"><span>Affranchi</span></span> | 300 | 30–30 | slash | 0 | 0 | 120 | — | berserker |
| <span class="unidad"><img src="/capturas/iconos/cwarelephant.png" class="icono" alt="Éléphant de guerre" loading="lazy"><span>Éléphant de guerre</span></span> | 2000 | 30–40 | slash | 10 | 10 | 60 | — | liberté, dégâts d'écrasement |

### Éléphant de guerre {#war-elephant}
- Les unités à distance infligent x1,5 contre les Éléphants de guerre

---

## Unités teutonnes {#teuton-units}

| Unité | Santé | Attaque | Type d'attaque | Déf. taille | Déf. perce | Vitesse | Portée | Compétence |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/teutonarcher.png" class="icono" alt="Archer teuton" loading="lazy"><span>Archer teuton</span></span> | 200 | 8–18, x2 contre Mules | pierce | 0 | 0 | 160 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/teutonmetal.png" class="icono" alt="Cavalier teuton" loading="lazy"><span>Cavalier teuton</span></span> | 250 | 10–20, x2 contre Mules | slash | 0 | 0 | 160 | — | dégâts d'écrasement |
| <span class="unidad"><img src="/capturas/iconos/garcher.png" class="icono" alt="Archer gaulois teuton" loading="lazy"><span>Archer gaulois teuton</span></span> | 100 | 6–12 | pierce | 2 | 2 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/gswordsman.png" class="icono" alt="Épéiste gaulois teuton" loading="lazy"><span>Épéiste gaulois teuton</span></span> | 240 | 10–18 | slash | 2 | 2 | 100 | — | — |
| <span class="unidad"><img src="/capturas/iconos/rarcher.png" class="icono" alt="Archer romain teuton" loading="lazy"><span>Archer romain teuton</span></span> | 125 | 9–13 | pierce | 3 | 3 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/rswordsman.png" class="icono" alt="Recrue romaine teutonne" loading="lazy"><span>Recrue romaine teutonne</span></span> | 240 | 13–17 | slash | 3 | 3 | 80 | — | — |

### Archer teuton {#teuton-archer}
- Animation 'taunt' de l'unité configurée

---

## Autres unités {#other-units}

| Unité | Santé | Attaque | Type d'attaque | Déf. taille | Déf. perce | Vitesse | Portée | Compétence |
|---|---|---|---|---|---|---|---|---|
| <span class="unidad"><img src="/capturas/iconos/imilitiaman.png" class="icono" alt="Milicien" loading="lazy"><span>Milicien</span></span> | 180 | 6–12 | slash | 4 | 0 | 80 | — | — |
| <span class="unidad"><img src="/capturas/iconos/iarcher.png" class="icono" alt="Archer" loading="lazy"><span>Archer</span></span> | 180 | 12–18 | pierce | 4 | 8 | 80 | 400 | — |
| <span class="unidad"><img src="/capturas/iconos/islinger.png" class="icono" alt="Frondeur" loading="lazy"><span>Frondeur</span></span> | 200 | 20–30 | pierce | 0 | 0 | 100 | 300 | — |
| <span class="unidad"><img src="/capturas/iconos/idefender.png" class="icono" alt="Défenseur" loading="lazy"><span>Défenseur</span></span> | 200 | 14–24 | pierce | 8 | 8 | 80 | — | posture défensive |
| <span class="unidad"><img src="/capturas/iconos/icavalry.png" class="icono" alt="Cavalerie" loading="lazy"><span>Cavalerie</span></span> | 240 | 20–30 | slash | 6 | 6 | 160 | — | charge |
| <span class="unidad"><img src="/capturas/iconos/imountaineer.png" class="icono" alt="Montagnard" loading="lazy"><span>Montagnard</span></span> | 400 | 24–48 | slash | 4 | 0 | 80 | — | liberté |

---

### Héros {#heroes}
- Modifications des statistiques de base des héros (plus de vie)
- Plus de vie par niveau
- Assets de héros réutilisés pour générer davantage de héros aléatoires
<p align="center">
    <img src="/capturas/captura_heroes_1.png" style="width: 75%; max-width: 768px;" alt="Héros aléatoires" loading="lazy">
</p>

- Les héros peuvent ordonner à leurs druides/prêtres assignés de lancer leurs sorts
- Les héros peuvent ordonner à leurs unités de construire une catapulte
- REMARQUE : donner un nouvel ordre au héros annule l'ordre de catapulte/sort précédent
<p align="center">
    <img src="/capturas/captura_heroe_hechizos.png" style="width: 75%; max-width: 768px;" alt="Héros lançant des sorts" loading="lazy">
</p>

- Recrutement aléatoire des héros modifié : il est désormais séquentiel avec un départ aléatoire, afin de maximiser la variété des assets/sprites de héros dans une partie.

## 7. Améliorations du jeu {#sec7}

### Nouvelle IA «LAT» {#lat-ai}
- Difficulté accrue face à l'IA
- Ajout d'une stratégie militaire initiale
- Ajout d'une stratégie d'exploration initiale
- Correction de cas précis dans l'algorithme de siège qui laissaient les armées bloquées, incapables d'assiéger la place forte ennemie
- Algorithme de recherche technologique amélioré. L'IA recherche les améliorations de l'arène, de la taverne et du temple
- Recrutement des unités spéciales amélioré
- Recrutement des unités militaires amélioré
- Calcul et réponse aux menaces améliorés
- Gestion des objectifs améliorée, IA plus agressive
- Système de surveillance et de contrôle des armées amélioré
- Système de retraite des armées amélioré
- Système de ravitaillement en vivres des armées amélioré
- Système de téléportation (grottes) amélioré
- Utilisation des ruines améliorée
- Système de ramassage et d'utilisation des objets amélioré
- Commerce de vivres avec les avant-postes gaulois réimplémenté
<p align="center">
    <img src="/capturas/captura_ia_items_1.png" style="width: 75%;  max-width: 768px;" alt="Système d'objets" loading="lazy">
</p>

### Place forte {#stronghold}
- Animations des paysans corrigées dans les places fortes romaines, et ajout des bâtiments manquants
- Ajout du légionnaire (Rome)/de l'archer gaulois (Gaule) aux animations des paysans
- Paramètres d'attaque des tours et des portes ajustés. Les portes tirent aussi des flèches.
- Ajout d'une notification lorsqu'une technologie finit d'être recherchée
- Les sorts des autels peuvent être lancés depuis le forum (l'autel est choisi au hasard)
<p align="center">
    <img src="/capturas/Captura_foro.png" style="width: 75%;  max-width: 768px;" alt="Sorts depuis le forum" loading="lazy">
</p>

### Taverne romaine {#tavern}
- Nouvelle technologie 'Championnats'
- Technologie 'Importer des chevaux' revue

### 'Entraînement' des unités supprimé {#training}
- Les unités de la caserne sont créées au niveau d''entraînement' déjà recherché
<p align="center">
    <img src="/capturas/captura_cuartel_1.png" style="width: 75%;  max-width: 768px;" alt="Entraînement" loading="lazy">
</p>

### Formations {#formations}
- 'Rayon' des unités en formation réduit. Les unités en formation sont plus proches les unes des autres.
- Structures des formations revues
<p align="center">
    <img src="/capturas/Captura_formaciones.png" style="width: 75%;  max-width: 768px;" alt="Formations" loading="lazy">
</p>

### Druides et magie {#magic}
- Dégâts des sorts réduits
- 'Nuage empoisonné' (prêtre) réimplémenté pour qu'il ne blesse plus les unités alliées
- Ajustements du système de recrutement des druides
- L'IA utilise les autels durant les parties aléatoires
- L'IA utilise les sorts au combat (Esprit vampire, Nuage empoisonné)
<p align="center">
    <img src="/capturas/Captura6_ia_nube.png" style="width: 75%;  max-width: 768px;" alt="Sorts de l'IA" loading="lazy">
</p>

### Teutons {#teutons}
- IA des armées teutonnes améliorée
- Les Teutons peuvent capturer les places fortes des joueurs
<p align="center">
    <img src="/capturas/Captura4.png" style="width: 75%;  max-width: 768px;" alt="La Menace Teutonne" loading="lazy">
</p>

### Catapultes {#catapults}
- Limite d'unités réduite de 10 à 5

### Villages {#villages}
- Les villages produisent automatiquement des paysans en même temps que les mules de vivres
- Correction du bug où les paysans/mules restaient bloqués pour toujours aux portes de la place forte
- Capture des villages améliorée : il n'est plus possible de capturer un village en capturant ses 'maisons'

### Avant-postes {#outposts}
- Ajout de défenseurs initiaux aux avant-postes
<p align="center">
    <img src="/capturas/captura_fortines_1.png" style="width: 75%;  max-width: 768px;" alt="Avant-postes gaulois" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_fortines_2.png" style="width: 75%;  max-width: 768px;" alt="Défenseurs de l'avant-poste" loading="lazy">
</p>

### Animaux {#animals}
- Correction du bug où les cerfs restaient bloqués aux bords de la carte

### Divers {#other}
- Messages 'Handle Leak' corrigés dans le vx.log
- Messages 'assets/interface/settlement icon' corrigés dans le vx.log
- Entrées BONUS.XML corrigées, elles restaient parfois sans effet
- Plantages aléatoires au chargement des cartes corrigés

## 8. Corrections du biome d'hiver {#sec8}
- Images des minimaps remplacées par celles de l'été
- Exposition (luminosité) des textures de terrain d'hiver réduite
<p align="center">
    <img src="/capturas/captura_mapa_invierno_1.png" style="width: 75%;  max-width: 768px;" alt="Carte d'hiver" loading="lazy">
</p>
<p align="center">
    <img src="/capturas/captura_decorados_inv_1.png" style="width: 75%;  max-width: 768px;" alt="Décors d'hiver" loading="lazy">
</p>

## 9. Couleurs des joueurs {#sec9}

Refonte des couleurs des joueurs afin de maximiser la distinction visuelle entre elles et d'éviter les confusions.

| ID | Couleur d'origine | HEX d'origine | Nouvelle couleur | Nouveau HEX |
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

## Et bien d'autres changements non documentés... {#more}
