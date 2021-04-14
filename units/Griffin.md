---
title: "Griffon"
permalink: /units/Griffin/
excerpt: "Era of Chaos Unités. Unités. Era of Chaos Les Griffons, symboles d'Erathia, dominent le ciel du royaume. Ces bêtes féroces sont fidèles et courageuses, et se battront jusqu'à leur dernier souffle."
unitID: 103
last_modified_at: 2021-04-14
locale: fr
ref: "Griffon"
toc: true
---
## General information
 **Description:** Les Griffons, symboles d'Erathia, dominent le ciel du royaume. Ces bêtes féroces sont fidèles et courageuses, et se battront jusqu'à leur dernier souffle.

 **Classe:** [Assaut](/fr/units/Unit Class Charging/)

 **Classe Description:** Assaut : les unités d'assaut attaquent les ennemis situés sur la ligne arrière et augmentent les dégâts critiques infligés aux unités à distance et de Lanceurs de sorts.

 **Faction :** [Château](/fr/units/Faction Castle/)

 **Race:** Bête

 **Members:** [x9](/fr/units/Unit Member x9/)

 **Rank:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 2/)

 **Unit Soul:** [Griffon](/fr/Items/unt_192/)

 **Unit description:** Plongeon : inflige des dégâts à 3 unités ennemies.

 **Short description:** Unité aérienne. Contre-attaques illimitées.

 **Position :** Inflige des dégâts directs en début de combat. Contre-attaque souvent et inflige des dégâts de zone.

 **Recommend:** En augmentant votre vitesse de déplacement, vous renforcez grandement l'efficacité de votre armée.

## Stats de base
 **Base HP: 1850.0**

 **Base ATK: 151.4**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 75.7 | 6.25 | 1387.5 |
  | Bleu | 151.4 | 12.5 | 2775.0 |
  | Bleu +1 | 227.1 | 18.75 | 4162.5 |
  | Bleu +2 | 317.94 | 26.25 | 5827.5 |
  | Violet | 408.78 | 33.75 | 7492.5 |
  | Violet +1 | 499.62 | 41.25 | 9157.5 |
  | Violet +2 | 605.6 | 50.0 | 11100.0 |
  | Violet +3 | 711.58 | 58.75 | 13042.5 |
  | Orange | 817.56 | 67.5 | 14985.0 |
  | Orange +1 | 938.68 | 77.5 | 17205.0 |
  | Orange +2 | 1059.8 | 87.5 | 19425.0 |
  | Orange +3 | 1180.92 | 97.5 | 21645.0 |
  | Orange +4 | 1302.04 | 107.5 | 23865.0 |
  | Orange +5 | 1483.72 | 122.5 | 27195.0 |
  | Rouge | 1725.96 | 142.5 | 31635.0 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 18.168 | 0.5 | 3.13 | 222.0 |
  | **3x** <i class="fas fa-star"/> | 21.196 | 0.53 | 3.75 | 259.0 |
  | **4x** <i class="fas fa-star"/> | 24.224 | 0.55 | 4.38 | 296.0 |
  | **5x** <i class="fas fa-star"/> | 27.252 | 0.58 | 5.0 | 333.0 |
  | **6x** <i class="fas fa-star"/> | 30.28 | 0.6 | 5.63 | 370.0 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Griffes dentelées](/images/e/e_1031.png) | [Griffes dentelées](/fr/equipment/Serrated Claws/) | **ATQ** | **DÉF** | 
  | ![Plaque de célérité](/images/e/e_1032.png) | [Plaque de célérité](/fr/equipment/Headplate of Speed/) | **PV** | **DÉF** | 
  | ![Plume d'Archgriffon](/images/e/e_1033.png) | [Plume d'Archgriffon](/fr/equipment/Archgriffin Feather/) | **ATQ** | **DÉF** | 
  | ![Armoiries de l'Empire](/images/e/e_1034.png) | [Armoiries de l'Empire](/fr/equipment/Empire's Crest/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Pic du Chevalier](/fr/Exclusive/Griffin Knight Pike/) 

 **Is Open:** - 

 **Item to Rang supérieur:** [Jeton Pic du Chevalier](/fr/Items/con_916/)

 **Skin:** -


## Emblèmes sacrés recommandés

* [Feu ancien](/fr/Emblem/Ancient Fire/) (Ordre)
* [Secret éternel](/fr/Emblem/Everlasting Secret/) (Ordre)
* [Témoin](/fr/Emblem/Witness/) (Bonté)

## Infos combinaison

* [Exaltation](/combination/Exaltation/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Contre-attaque en piqué
 **Description:** <span style="color: #645252;font-size:20px">Quand les Griffons se font attaquer, ils ont une chance d'infliger </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de dégâts à 3 unités (les attaques normales ont également une chance de déclencher Plongeon).</span><span style="color: black">

### Compétence normale 1 : Tour de commandement
 **Description:** <span style="color: #645252;font-size:20px">Quand les Griffons sont sur le champ de bataille, l'ATQ de toutes vos autres unités volantes augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et leur vitesse d'attaque de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence normale 2 : Charge glorieuse
 **Description:** <span style="color: #645252;font-size:20px">Quand les Griffons sont en </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Exaltation&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, ils gagnent 30 en vitesse de déplacement. Les dégâts de l'unité augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et les coups critiques de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 15 secondes.</span><span style="color: black">

### Compétence normale 3 : Archange
 **Description:** <span style="color: #645252;font-size:20px">Les PV du Griffon augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Octroie au Griffon 10 % de PV supplémentaires pour chaque unité alliée volante sur le champ de bataille.</span><span style="color: black">

### Compétence spéciale de faction I : Combat de siège
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Château sont rompues au combat contre les Dragons. Lorsqu'elles affrontent une unité à 1 combattant, leurs dégâts augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> </span><span style="color: black">

### Compétence spéciale de faction II : Résonance défensive
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Château sont rompues à la défense concertée. La DÉF augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> par unité survivante.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1.5+2.5)"
    let str8 = "(LEVEL*0.5+2.5)"
    let str5 = "LEVEL*10+50"
    let str6 = "LEVEL*5+25"
    let str3 = "LEVEL*0.5+2.5"
    let str4 = "LEVEL*1+5"
    let str1 = "LEVEL*6+94"
    let str2 = "LEVEL*1+9"
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

* **Château**  (Groupement - Château)
* **Assaut**  (Groupement - Assaut)
* **SR**  (SR)

### Bonus de héros
* [Mullich](/fr/heroes/Mullich/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Roland](/fr/heroes/Roland/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* dégâts d'unité
* réduction des dégâts d'unité

 **:** [Potion de talent (Assaut)](/fr/Items/con_788/)


## Awaking
### Awaking Détails
 **Is it possible right now?** YES

 **Awaking Name:** Griffon royal

 **Awaking Description:** Les Griffons dressés par la famille Edric servent désormais de gardiens à Erathia. De jour comme de nuit, ils arpentent le ciel au-dessus du château. Les envahisseurs assez imprudents pour s'approcher du château sont mis en lambeaux par les griffes acérées des Griffons.

### Awaking Tasks
 1. <span style="color: #876741;font-size:18px">Déployez un Griffon et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #876741;font-size:18px"> unités du Château pour réussir le niveau Impitoyable ou un niveau supérieur de l'Utopie draconique. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #876741;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #876741;font-size:18px"> ressources pendant une aventure de guilde.</span>

 3. <span style="color: #876741;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #876741;font-size:18px"> âmes de Griffon royal dans les niveaux 15-2 et 15-4 du souterrain.</span>

 4. <span style="color: #876741;font-size:18px">Déployez un Griffon et </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #876741;font-size:18px"> unités du Château pour remporter 3 combats dans la campagne. (Les raids ne comptent pas pour la mission.)</span>

## Awaken Skills

### 1st Skill (or 2nd): Turbulences
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Contre-attaque en piqué&gt; :</span><span style="color: #645252;font-size:18px"> Réduit la vitesse d'attaque de l'unité cible de 40 % pendant 5 secondes.</span>

### 2nd Skill (or 1st): Embuscade en piqué
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Contre-attaque en piqué&gt; :</span><span style="color: #645252;font-size:18px"> Augmente la vitesse d'attaque de 40 % pendant 5 secondes.</span>

### 3rd Skill (or 4th): Seigneur sanctifié
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Tour de commandement&gt; :</span><span style="color: #645252;font-size:18px"> Le Griffon libère toute la puissance des aigles. Au début de la bataille, augmente les dégâts des unités volantes alliées de 40 % pendant 20 secondes.</span>

### 4th Skill (or 3rd): Gardien sanctifié
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Tour de commandement&gt; :</span><span style="color: #645252;font-size:18px"> Le Griffon libère toute la puissance des lions. Au début de la bataille, augmente la résistance aux dégâts des unités de mêlée alliées de 40 % pendant 20 secondes.</span>

### 5th Skill (or 6th): Soutien aérien
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Archange&gt; :</span><span style="color: #645252;font-size:18px"> La DÉF du Griffon augmente de 5 % pour chaque unité volante alliée déployée sur le champ de bataille.</span>

### 6th Skill (or 5th): Impact de Trembleterre
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Archange&gt; :</span><span style="color: #645252;font-size:18px"> Augmente les dégâts du Griffon de 50 % face à des unités au sol.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 4.0

 **Rush:** 2

 **Speedattack:** 160

 **Attack Show:** 6.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 4.0

 **Score:** 761

 **HP Show:** 7

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 2

 **speedmove:** 120

 **posclass:** 3

 **talk1:** Nul n'échappe à mon étreinte !

 **talk2:** Envie de vous frotter à ces griffes ?

 **talk3:** Vous ne m'attraperez jamais !

