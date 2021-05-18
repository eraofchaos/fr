---
title: "Orque"
permalink: /units/Orc/
excerpt: "Era of Chaos Orque. Orque Unités. Commandant Orque. Era of Chaos Personne ne sait où les Orques cachent leurs haches, car ils semblent en avoir un nombre infini."
unitID: 403
last_modified_at: 2021-05-18
locale: fr
ref: "Orque"
toc: true
---
  ![Orque](/images/u/ti_shourentoufushou.jpg)

## General information
 **Description:** Personne ne sait où les Orques cachent leurs haches, car ils semblent en avoir un nombre infini.

 **Classe:** [À distance](/fr/units/Unit Class Ranged/)

 **Classe Description:** Plus une unité à distance sera éloignée de sa cible, plus son attaque sera puissante.

 **Faction :** [Bastion](/fr/units/Faction Stronghold/)

 **Race:** Orque

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rang:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 2/)

 **Unit Soul:** [Orque](/ItemsFR/unt_219/)

 **Unit description:** Exécution : inflige des dégâts supplémentaires aux ennemis qui ont moins de 30 % de PV.

 **Short description:** Inflige Saignement. Efficace contre les ennemis avec peu de santé.

 **Position :** Provoque Saignement en attaquant. Inflige des dégâts importants. Plus sa santé est basse, plus son attaque est puissante.

 **Recommend:** Ces créatures ont peu de santé, mais elles frappent fort. Elles seront très puissantes si vous pensez à les soigner.

## Stats de base
 **Base HP: 662.0**

 **Base ATK: 82.7**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 41.35 | 5.0 | 496.5 |
  | Bleu | 82.7 | 10.0 | 993.0 |
  | Bleu +1 | 124.05 | 15.0 | 1489.5 |
  | Bleu +2 | 173.67 | 21.0 | 2085.3 |
  | Violet | 223.29 | 27.0 | 2681.1 |
  | Violet +1 | 272.91 | 33.0 | 3276.9 |
  | Violet +2 | 330.8 | 40.0 | 3972.0 |
  | Violet +3 | 388.69 | 47.0 | 4667.1 |
  | Orange | 446.58 | 54.0 | 5362.2 |
  | Orange +1 | 512.74 | 62.0 | 6156.6 |
  | Orange +2 | 578.9 | 70.0 | 6951.0 |
  | Orange +3 | 645.06 | 78.0 | 7745.4 |
  | Orange +4 | 711.22 | 86.0 | 8539.8 |
  | Orange +5 | 810.46 | 98.0 | 9731.4 |
  | Rouge | 942.78 | 114.0 | 11320.2 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 9.924 | 0.64 | 2.6 | 79.44 |
  | **3x** <i class="fas fa-star"/> | 11.578 | 0.67 | 3.2 | 92.68 |
  | **4x** <i class="fas fa-star"/> | 13.232 | 0.7 | 3.8 | 105.92 |
  | **5x** <i class="fas fa-star"/> | 14.886 | 0.73 | 4.4 | 119.16 |
  | **6x** <i class="fas fa-star"/> | 16.54 | 0.76 | 5.0 | 132.4 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Hache de lancer](/images/e/e_4031.png) | [Hache de lancer](/fr/equipment/Throwing Axe/) | **ATQ** | **DÉF** | 
  | ![Ceinture de restriction](/images/e/e_4032.png) | [Ceinture de restriction](/fr/equipment/Belt of Constraint/) | **PV** | **DÉF** | 
  | ![Épaulières de fer](/images/e/e_4033.png) | [Épaulières de fer](/fr/equipment/Iron Pauldrons/) | **ATQ** | **DÉF** | 
  | ![Épaulières sanguinaires](/images/e/e_4034.png) | [Épaulières sanguinaires](/fr/equipment/Bloodthirsty Pauldrons/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Arc long](/fr/Exclusive/Orc Long Bow/) 

 **Is Open:** - 

 **Item to Rang supérieur:** [Jeton Arc long](/ItemsFR/con_914/)

 **Skin:** -


## Emblèmes sacrés recommandés

* [Ailes de Griffon](/fr/Emblem/Griffin Wings/) (Ordre)
* [Clé en pierre](/fr/Emblem/Stone Key to the Gates/) (Neutre)
* [Envie](/fr/Emblem/Jealousy/) (Chaos)

## Infos combinaison

* [Saignement](/combination/Saignement/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Exécution experte
 **Description:** <span style="color: #645252;font-size:20px">Quand un Orque combat une unité qui a moins de 30 % de PV, son ATQ augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et ses coups critiques augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence normale 1 : Couper
 **Description:** <span style="color: #645252;font-size:20px">L'attaque supplémentaire de l'Orque est augmentée de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> et les dégâts de l'unité augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Son attaque normale inflige </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Saignement&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> sur la cible pendant 6 secondes.</span><span style="color: black">

### Compétence normale 2 : Carnage
 **Description:** <span style="color: #645252;font-size:20px">Les coups critiques de l'Orque augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">. L'effet double quand ses PV tombent sous la barre des 35 % et perdure même si l'unité regagne des PV.</span><span style="color: black">

### Compétence normale 3 : Furie sanguinaire
 **Description:** <span style="color: #645252;font-size:20px">Les PV de l'Orque augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Il récupère 2 % de ses PV chaque fois qu'il réussit un coup critique.</span><span style="color: black">

### Compétence spéciale de faction I : Zélote combattant
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Bastion sont connues pour mener des batailles de longue haleine. Leur vitesse d'ATQ augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> tous les 15 % PV perdus.</span><span style="color: black">

### Compétence spéciale de faction II : Essor de vitalité
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Bastion sont rompues aux soins sur les champs de bataille, et augmentent leur régénération de PV (restaurant </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> PV toutes les 3 secondes) et reçoivent </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de drain de vie.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*0.3+0.5)"
    let str8 = "(LEVEL*300+1200)"
    let str5 = "LEVEL*40+160"
    let str6 = "LEVEL*3+12"
    let str3 = "LEVEL*60+240"
    let str4 = "LEVEL*0.5+2.5"
    let str1 = "LEVEL*5+45"
    let str2 = "LEVEL*1+15"
    let str9 = "(LEVEL*0.3+1)"
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

* **Bastion**  (Groupement - Bastion)
* **À distance**  (Groupement - À distance)
* **SR**  (SR)

### Bonus de héros
* [Gelu](/fr/heroes/Gelu/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Crag Hack](/fr/heroes/Crag Hack/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Kilgor](/fr/heroes/Kilgor/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Vitesse d'attaque
* Résistance magique

 **:** [Potion de talent (Arbalétrier)](/ItemsFR/con_789/)


## Awaking

  ![Commandant Orque](/images/u/tia_banshouren.jpg)

### Awaking Détails
 **Is it possible right now?** YES

 **Awaking Name:** Commandant Orque

 **Awaking Description:** Après d'innombrables exécutions, les compétences de découpe des Orques se sont améliorées. Ils ne cachent plus la soif de sang qui brille dans leurs yeux. Ils ne massacrent plus sans but, mais sont devenus de redoutables tueurs sur le champ de bataille.

### Awaking Tasks
 1. <span style="color: #876741;font-size:18px">Déployez un Orque et au moins </span><span style="color: #1ca216;font-size:18px">4</span><span style="color: #876741;font-size:18px"> unités à distance pour venir à bout de </span><span style="color: #1ca216;font-size:18px">14</span><span style="color: #876741;font-size:18px"> vagues de Trépassés dans la crypte en une fois. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #876741;font-size:18px">Éliminez </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #876741;font-size:18px"> monstres lors d'une aventure de guilde.</span>

 3. <span style="color: #876741;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #876741;font-size:18px"> âmes d'Orque dans les niveaux 14-2 et 14-4 du souterrain.</span>

 4. <span style="color: #876741;font-size:18px">Déployez un Orque et </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #876741;font-size:18px"> unités du Bastion pour remporter 3 batailles dans la campagne. (Les raids ne comptent pas pour la mission.)</span>

## Awaken Skills

### 1st Skill (or 2nd): Exécution perforante
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Exécution experte&gt; :</span><span style="color: #645252;font-size:18px"> Augmente la pénétration de 300 face à des unités qui ont moins de 50 % de leurs PV.</span>

### 2nd Skill (or 1st): Exécution instantanée
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Exécution experte&gt; :</span><span style="color: #645252;font-size:18px"> Augmente les coups critiques de 300 face à des unités qui ont moins de 50 % de leurs PV.</span>

### 3rd Skill (or 4th): Découpe rapide
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Découpe&gt; :</span><span style="color: #645252;font-size:18px"> Augmente la vitesse d'attaque de 15 %. L'effet est doublé face à des ennemis étourdis.</span>

### 4th Skill (or 3rd): Découpe mortelle
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Découpe&gt; :</span><span style="color: #645252;font-size:18px"> Augmente les dégâts d'unité de 15 %. L'effet est doublé face à des ennemis étourdis.</span>

### 5th Skill (or 6th): Assaut sanguinaire
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Furie sanguinaire&gt; :</span><span style="color: #645252;font-size:18px"> Chaque coup critique augmente les coups critiques de 2 %. Cet effet peut être cumulé jusqu'à 20 fois.</span>

### 6th Skill (or 5th): Frappe sanguinaire
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Furie sanguinaire&gt; :</span><span style="color: #645252;font-size:18px"> Après chaque coup critique, octroie 50 % de chance d'infliger des dégâts équivalents à 40 % de l'ATQ à une unité ennemie aléatoire.</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 5.0

 **fly:** feifu

 **flyspeed:** 300

 **atkfly:** 5

 **Rush:** 3

 **Speedattack:** 80

 **Attack Show:** 6.0

 **Attack Area:** 350

 **Attack Range:** 300

 **Attack Speed Show:** 8.0

 **Defense Show:** 5.0

 **Score:** 794

 **HP Show:** 5

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 5

 **speedmove:** 90

 **posclass:** 4

 **talk1:** Rien n'est plus jouissif que le carnage des batailles !

 **talk2:** Les Orques n'ont peur de rien !

 **talk3:** Ah, à manger ! Quel dommage qu'il y ait ces armures sur leur chair. Elles se coincent entre les dents.

