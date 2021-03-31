---
title: "Aéronef magique"
permalink: /units/Magic Airship/
excerpt: "Era of Chaos Unités. Unités. Era of Chaos La grand-voile ronde renforce ce vaisseau solide, lui permettant de profiter d'un baptême de l'air en survolant les nuages."
unitID: 608
last_modified_at: 2021-03-31
locale: fr
ref: "Aéronef magique"
toc: true
---
## General information
 **Description:** La grand-voile ronde renforce ce vaisseau solide, lui permettant de profiter d'un baptême de l'air en survolant les nuages.

 **Classe:** [Lanceur de sorts](/fr/units/Unit Class Caster/)

 **Classe Description:** Grâce à leur maîtrise des secrets de la magie, les Lanceurs de sorts bénéficient d'une résistance à la magie plus importante.

 **Faction :** [Tour](/fr/units/Faction Tower/)

 **Race:** Humain

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rank:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 3/)

 **Unit Soul:** [Aéronef magique](/fr/Items/unt_242/)

 **Short description:** Confère des bonus de DPS en ligne arrière.

 **Position :** Soutient les Mages. Augmente la vitesse d'ATQ des Lanceurs de sorts et gèle les attaques des ennemis.

## Stats de base
 **Base HP: 1715.0**

 **Base ATK: 208.5**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 104.25 | 3.75 | 1286.25 |
  | Bleu | 208.5 | 7.5 | 2572.5 |
  | Bleu +1 | 312.75 | 11.25 | 3858.75 |
  | Bleu +2 | 437.85 | 15.75 | 5402.25 |
  | Violet | 562.95 | 20.25 | 6945.75 |
  | Violet +1 | 688.05 | 24.75 | 8489.25 |
  | Violet +2 | 834.0 | 30.0 | 10290.0 |
  | Violet +3 | 979.95 | 35.25 | 12090.75 |
  | Orange | 1125.9 | 40.5 | 13891.5 |
  | Orange +1 | 1292.7 | 46.5 | 15949.5 |
  | Orange +2 | 1459.5 | 52.5 | 18007.5 |
  | Orange +3 | 1626.3 | 58.5 | 20065.5 |
  | Orange +4 | 1793.1 | 64.5 | 22123.5 |
  | Orange +5 | 2043.3 | 73.5 | 25210.5 |
  | Rouge | 2376.9 | 85.5 | 29326.5 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 29.19 | 0.46 | 2.65 | 240.1 |
  | **4x** <i class="fas fa-star"/> | 33.36 | 0.48 | 3.23 | 274.4 |
  | **5x** <i class="fas fa-star"/> | 37.53 | 0.5 | 3.8 | 308.7 |
  | **6x** <i class="fas fa-star"/> | 41.7 | 0.53 | 4.38 | 343.0 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Système de décollage](/images/e/e_6081.png) | [Système de décollage](/fr/equipment/Lift-off System/) | **ATQ** | **DÉF** | 
  | ![Système de contrôle](/images/e/e_6082.png) | [Système de contrôle](/fr/equipment/Control System/) | **PV** | **DÉF** | 
  | ![Tour de contrôle principale](/images/e/e_6083.png) | [Tour de contrôle principale](/fr/equipment/Main Control Tower/) | **ATQ** | **DÉF** | 
  | ![Quai d'observation](/images/e/e_6084.png) | [Quai d'observation](/fr/equipment/Observation Deck/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Étoile polaire](/fr/Exclusive/Magic Airship Polaris/) 

 **Is Open:** - 

 **Item to Rang supérieur:** [Jeton Étoile polaire](/fr/Items/con_989/)

 **Skin:** [Skin spécial Étoile polaire](/fr/Items/con_657/)


## Emblèmes sacrés recommandés

* [Feu ancien](/fr/Emblem/Ancient Fire/) (Ordre)
* [Secret éternel](/fr/Emblem/Everlasting Secret/) (Ordre)
* [Colère](/fr/Emblem/Anger/) (Chaos)

## Infos combinaison

* [Gel](/combination/Gel/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Soutien énergétique
 **Description:** <span style="color: #645252;font-size:20px">Quand les PV de l'une de vos unités passent sous la barre des 30 %, restaure </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> des PV max, dissipe les affaiblissements et augmente la résistance aux dégâts de l'unité et sa résistance magique de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 15 secondes. Cet effet ne peut intervenir qu'une seule fois par bataille.</span><span style="color: black">

### Compétence normale 1 : Bombe de givre
 **Description:** <span style="color: #645252;font-size:20px">Les attaques normales ont </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de chance de </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;geler&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> la cible et les unités ennemies autour d'elle pendant 2 secondes.</span><span style="color: black">

### Compétence normale 2 : Bulle magique
 **Description:** <span style="color: #645252;font-size:20px">La résistance magique de l'Aéronef magique augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Quand le sort &lt;Éveil magique&gt; est utilisé, les Héros ennemis perdent 2 points de mana et les Héros alliés en récupèrent 3.</span><span style="color: black">

### Compétence normale 3 : Éveil magique
 **Description:** <span style="color: #645252;font-size:20px">Quand l'Aéronef magique est renforcé par un sort de Héros allié, il augmente la vitesse d'ATQ de tous les Lanceurs de sorts de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et les dégâts de l'unité de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 15 secondes. Augmente la vitesse d'ATQ de tous les Lanceurs de sorts de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant toute la durée de la bataille. Cet effet peut se cumuler jusqu'à 4 fois.</span><span style="color: black">

### Compétence spéciale de faction I : Esprit clair
 **Description:** <span style="color: #645252;font-size:20px">Difficile de faire taire les unités de la Tour. La durée du &lt;Silence&gt; qui leur est infligé diminue de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence spéciale de faction II : Dynamite énergétique
 **Description:** <span style="color: #645252;font-size:20px">Les unités de la Tour sont rompues à la conversion d'énergie, et augmentent leurs dégâts critiques de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "LEVEL*0.8+3.2"
    let str8 = "(LEVEL*2+10)"
    let str5 = "LEVEL*2+8"
    let str6 = "LEVEL*1+9"
    let str3 = "LEVEL*0.2+1.8"
    let str4 = "LEVEL*2+8"
    let str1 = "LEVEL*3+12"
    let str2 = "LEVEL*1+9"
    let str9 = "(LEVEL*1.5+4)"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
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

* **Tour**  (Groupement - Tour)
* **Lanceur de sorts**  (Groupement - Lanceur de sorts)
* **SR**  (SR)

### Bonus de héros
* [Dracon](/fr/heroes/Dracon/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Astral](/fr/heroes/Astral/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Vitesse d'attaque
* Résistance magique

 **:** [Potion de talent (Lanceur de sorts)](/fr/Items/con_790/)


## Awaking
### Awaking Détails
 **Is it possible right now?** NO

 **Awaking Name:** null

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
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **fly:** reqiqiu

 **flyspeed:** 300

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 7.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 4.0

 **Score:** 1461

 **HP Show:** 5

 **disrdcvol:** -2147483648

 **Dead Type:** 1

 **s:** 1

 **label1:** 3

 **speedmove:** 80

 **posclass:** 5

 **talk1:** Ma lance est indestructible !

 **talk2:** Seuls les morts se dressent face à moi !

 **talk3:** Je lutterai pour mon foyer et mes terres !

