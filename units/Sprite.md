---
title: "Fée"
permalink: /units/Sprite/
excerpt: "Era of Chaos Unités. Unités. Era of Chaos Une magnifique Fée qui n'existe que dans les légendes et les contes. Tout personnage qui lui manquera de respect ne sera pas apprécié des lecteurs, et ne connaîtra pas de fin heureuse."
unitID: 901
last_modified_at: 2021-03-31
locale: fr
ref: "Fée"
toc: true
---
## General information
 **Description:** Une magnifique Fée qui n'existe que dans les légendes et les contes. Tout personnage qui lui manquera de respect ne sera pas apprécié des lecteurs, et ne connaîtra pas de fin heureuse.

 **Classe:** [Assaut](/fr/units/Unit Class Charging/)

 **Classe Description:** Assaut : les unités d'assaut attaquent les ennemis situés sur la ligne arrière et augmentent les dégâts critiques infligés aux unités à distance et de Lanceurs de sorts.

 **Faction :** [Conflux](/fr/units/Faction Conflux/)

 **Race:** Maître des bêtes

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rank:** [R](/fr/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/fr/units/Star 1/)

 **Unit Soul:** [Fée](/fr/Items/unt_262/)

 **Short description:** Inflige Silence. Sort initial amélioré.

 **Position :** Explose en mourant, inflige Silence, augmente le mana de départ des Héros.

## Stats de base
 **Base HP: 993.0**

 **Base ATK: 69.5**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 34.75 | 3.75 | 744.75 |
  | Bleu | 69.5 | 7.5 | 1489.5 |
  | Bleu +1 | 104.25 | 11.25 | 2234.25 |
  | Bleu +2 | 145.95 | 15.75 | 3127.95 |
  | Violet | 187.65 | 20.25 | 4021.65 |
  | Violet +1 | 229.35 | 24.75 | 4915.35 |
  | Violet +2 | 278.0 | 30.0 | 5958.0 |
  | Violet +3 | 326.65 | 35.25 | 7000.65 |
  | Orange | 375.3 | 40.5 | 8043.3 |
  | Orange +1 | 430.9 | 46.5 | 9234.9 |
  | Orange +2 | 486.5 | 52.5 | 10426.5 |
  | Orange +3 | 542.1 | 58.5 | 11618.1 |
  | Orange +4 | 597.7 | 64.5 | 12809.7 |
  | Orange +5 | 681.1 | 73.5 | 14597.1 |
  | Rouge | 792.3 | 85.5 | 16980.3 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 6.95 | 0.48 | 1.5 | 99.3 |
  | **2x** <i class="fas fa-star"/> | 8.34 | 0.5 | 2.08 | 119.16 |
  | **3x** <i class="fas fa-star"/> | 9.73 | 0.53 | 2.65 | 139.02 |
  | **4x** <i class="fas fa-star"/> | 11.12 | 0.55 | 3.23 | 158.88 |
  | **5x** <i class="fas fa-star"/> | 12.51 | 0.58 | 3.8 | 178.74 |
  | **6x** <i class="fas fa-star"/> | 13.9 | 0.6 | 4.38 | 198.6 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Couronne parfumée](/images/e/e_9011.png) | [Couronne parfumée](/fr/equipment/Fragrant Wreath/) | **ATQ** | **DÉF** | 
  | ![Toge de lunétoile](/images/e/e_9012.png) | [Toge de lunétoile](/fr/equipment/Gown of Moon and Stars/) | **PV** | **DÉF** | 
  | ![Ailes de papillon phosphoreux](/images/e/e_9013.png) | [Ailes de papillon phosphoreux](/fr/equipment/Phosphorus Butterfly Wings/) | **ATQ** | **DÉF** | 
  | ![Bracelet en émeraude](/images/e/e_9014.png) | [Bracelet en émeraude](/fr/equipment/Emerald Arm Ring/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Pic du Chevalier](/fr/Exclusive/Sprite Knight Pike/) 

 **Is Open:** - 

 **Item to Rang supérieur:** [Jeton Pic du Chevalier](/fr/Items/con_916/)

 **Skin:** -


## Emblèmes sacrés recommandés

* [Feu ancien](/fr/Emblem/Ancient Fire/) (Ordre)
* [Secret éternel](/fr/Emblem/Everlasting Secret/) (Ordre)
* [Colère](/fr/Emblem/Anger/) (Chaos)

## Infos combinaison

* [Silence](/combination/Silence/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Bris d'énergie
 **Description:** <span style="color: #645252;font-size:20px">Quand une Fée est tuée, elle inflige une quantité de dégâts égale à </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> des PV max de la cible (jusqu'à 1 000 % de l'ATQ de la cible).</span><span style="color: black">

### Compétence normale 1 : Bénédiction de la Fée
 **Description:** <span style="color: #645252;font-size:20px">Lorsque le combat commence, la Fée augmente la résistance magique de toutes les unités alliées sur son chemin de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Cet effet est également doublé pour la Fée.</span><span style="color: black">

### Compétence normale 2 : Inspiration
 **Description:** <span style="color: #645252;font-size:20px">Quand une Fée est sur le champ de bataille, elle augmente les points de mana des Héros alliés de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence normale 3 : Dévouement
 **Description:** <span style="color: #645252;font-size:20px">Quand une Fée est tuée, elle inflige </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Silence&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> à la cible pendant </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> secondes.</span><span style="color: black">

### Compétence spéciale de faction I : Affinité élémentaire
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Conflux sont connues pour leur maîtrise des arcanes magiques du Conflux, et augmentent la résistance magique des Héros de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence spéciale de faction II : Conflit élémentaire
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Conflux maîtrisent particulièrement bien les dégâts du Conflux. Lorsqu'elles affrontent des unités qui n'appartiennent pas au Conflux, leurs dégâts augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*3+15)"
    let str6 = "(LEVEL*1+5)"
    let str3 = "LEVEL*1.5+0.2"
    let str4 = "LEVEL*0.15+1.85"
    let str1 = "LEVEL*0.25+2.75"
    let str2 = "(LEVEL*0.5+2.5)"
    let res="ERR";
    try {
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
    } catch (e) { log.textContent = "Issue with calculation!";}
    if (event!=null)
      event.preventDefault();
  }
  const form = document.getElementById('form');
  const log = document.getElementById('log');
  form.addEventListener('submit', skillCalc);
  window.onload = skillCalc;
  </script>
## Pertinence
### Connexion de groupement

* **Conflux**  (Groupement - Conflux)
* **Assaut**  (Groupement - Assaut)
* **R**  (R)

### Bonus de héros
* [Mullich](/fr/heroes/Mullich/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Ciele](/fr/heroes/Ciele/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* dégâts d'unité
* Résistance magique

 **:** [Potion de talent (Assaut)](/fr/Items/con_788/)


## Awaking
### Awaking Détails
 **Is it possible right now?** NO

 **Awaking Name:** 

 **Awaking Description:** null

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Déployez des Lanciers et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unités du Château pour éliminer </span><span style="color: #1ca216;font-size:18px">1 000</span><span style="color: #3c2a1e;font-size:18px"> Nains en une seule attaque du Trésor des Nains. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Éliminez </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> monstres lors d'une aventure de guilde.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> âmes de Hallebardier dans les niveaux 14-2 et 14-4 du Souterrain.</span>

 4. null

## Awaken Skills

### 1st Skill (or 2nd): Nuée de lances étendue
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Nuée de lances&gt; : </span><span style="color: #645252;font-size:18px">Cible des unités ennemies plus grandes.</span>

### 2nd Skill (or 1st): Nuée de lances furtive
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Nuée de lances&gt; : </span><span style="color: #645252;font-size:18px">Inflige 150 % de dégâts et étourdit la cible pendant 4,5 secondes.</span>

### 3rd Skill (or 4th): Matrice physique
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Charisme&gt; : </span><span style="color: #645252;font-size:18px">En cas d'&lt;Exaltation&gt; au combat, augmente la résistance aux dégâts de 30 % pendant 10 secondes.</span>

### 4th Skill (or 3rd): Matrice magique
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Charisme&gt; : </span><span style="color: #645252;font-size:18px">En cas d'&lt;Exaltation&gt; au combat, augmente la résistance magique de 30 % pendant 10 secondes.</span>

### 5th Skill (or 6th): Stratégie d'infiltration
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Chasse au dragon&gt; : </span><span style="color: #645252;font-size:18px">Face aux unités de 1 ou de 4 combattants, inflige &lt;Découragement&gt; à la cible, ce qui réduit ses coups critiques de 300 points.</span>

### 6th Skill (or 5th): Exténuation
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Chasse au dragon&gt; : </span><span style="color: #645252;font-size:18px">Face aux unités de 1 ou de 4 combattants, réduit l'esquive de la cible de 300 points.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 2

 **Speedattack:** 160

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 546

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 11

 **speedmove:** 120

 **posclass:** 3

 **talk1:** Ma lance est indestructible !

 **talk2:** Seuls les morts se dressent face à moi !

 **talk3:** Je lutterai pour mon foyer et mes terres !

