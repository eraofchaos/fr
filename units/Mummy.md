---
title: "Momie"
permalink: /units/Mummy/
excerpt: "Era of Chaos Unités. Unités. Era of Chaos Les Non-Morts se reposent dans leur mausolée antique. Ceux qui oseront y pénétrer seront maudits."
unitID: 308
last_modified_at: 2021-04-21
locale: fr
ref: "Momie"
toc: true
---
  ![Momie](/images/u/ti_munaiyi.jpg)

## General information
 **Description:** Les Non-Morts se reposent dans leur mausolée antique. Ceux qui oseront y pénétrer seront maudits.

 **Classe:** [Défense](/fr/units/Unit Class Defense/)

 **Classe Description:** Les unités défensives peuvent résister aux attaques pendant plus longtemps et subissent moins de dégâts.

 **Faction :** [Nécropole](/fr/units/Faction Necropolis/)

 **Race:** Non-Morts

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rank:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 3/)

 **Unit Soul:** [Momie](/fr/Items/unt_215/)

 **Unit description:** Malédiction putride : réduit grandement l'efficacité des soins ennemis.

 **Short description:** Maladie réduit les PV et les soins.

 **Position :** Porteur de maladie. Réduit les soins de toutes les unités ennemies.

## Stats de base
 **Base HP: 2691.0**

 **Base ATK: 141.0**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 70.5 | 12.5 | 2018.25 |
  | Bleu | 141.0 | 25.0 | 4036.5 |
  | Bleu +1 | 211.5 | 37.5 | 6054.75 |
  | Bleu +2 | 296.1 | 52.5 | 8476.65 |
  | Violet | 380.7 | 67.5 | 10898.55 |
  | Violet +1 | 465.3 | 82.5 | 13320.45 |
  | Violet +2 | 564.0 | 100.0 | 16146.0 |
  | Violet +3 | 662.7 | 117.5 | 18971.55 |
  | Orange | 761.4 | 135.0 | 21797.1 |
  | Orange +1 | 874.2 | 155.0 | 25026.3 |
  | Orange +2 | 987.0 | 175.0 | 28255.5 |
  | Orange +3 | 1099.8 | 195.0 | 31484.7 |
  | Orange +4 | 1212.6 | 215.0 | 34713.9 |
  | Orange +5 | 1381.8 | 245.0 | 39557.7 |
  | Rouge | 1607.4 | 285.0 | 46016.1 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 19.74 | 0.33 | 6.5 | 376.74 |
  | **4x** <i class="fas fa-star"/> | 22.56 | 0.35 | 7.25 | 430.56 |
  | **5x** <i class="fas fa-star"/> | 25.38 | 0.36 | 8.0 | 484.38 |
  | **6x** <i class="fas fa-star"/> | 28.2 | 0.38 | 8.75 | 538.2 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Toucher immortel](/images/e/e_3081.png) | [Toucher immortel](/fr/equipment/Immortal Touch/) | **ATQ** | **DÉF** | 
  | ![Bandage antique](/images/e/e_3082.png) | [Bandage antique](/fr/equipment/Ancient Bandage/) | **PV** | **DÉF** | 
  | ![Pupille du défunt](/images/e/e_3083.png) | [Pupille du défunt](/fr/equipment/Pupil of the Departed/) | **ATQ** | **DÉF** | 
  | ![Souffle de la mort](/images/e/e_3084.png) | [Souffle de la mort](/fr/equipment/Breath of Death/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Bandage](/fr/Exclusive/Mummy Gauze/) 

 **Is Open:** - 

 **Item to Rang supérieur:** [Jeton Bandage](/fr/Items/con_981/)

 **Skin:** [Skin spécial Bandage](/fr/Items/con_649/)


## Emblèmes sacrés recommandés

* [Héritage des Ironfist](/fr/Emblem/Ironfist's Legacy/) (Ordre)
* [Secret éternel](/fr/Emblem/Everlasting Secret/) (Ordre)
* [Luxure](/fr/Emblem/Lust/) (Chaos)

## Infos combinaison

* [Maladie](/combination/Maladie/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Malédiction putride
 **Description:** <span style="color: #645252;font-size:20px">La Momie inflige </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> points de dégâts aux unités ennemies dans une certaine zone autour d'elle toutes les 20 secondes et leur applique </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Maladie&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 12 secondes.</span><span style="color: black">

### Compétence normale 1 : Linceul
 **Description:** <span style="color: #645252;font-size:20px">Quand le sort &lt;Malédiction putride&gt; est lancé, restaure une quantité de PV égale à </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de vos PV max et augmente la résistance aux dégâts de l'unité de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 10 secondes.</span><span style="color: black">

### Compétence normale 2 : Source de maladie
 **Description:** <span style="color: #645252;font-size:20px">La Momie est immunisée contre </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Maladie&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">. La résistance aux dégâts de la Momie augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Lorsque la Momie est sur le champ de bataille, tous les soins reçus par les unités ennemies sont réduits de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence normale 3 : Dieu de la peste
 **Description:** <span style="color: #645252;font-size:20px">La DÉF de la Momie augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Si l'ennemi qui attaque la Momie souffre de </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Maladie&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, l'effet double.</span><span style="color: black">

### Compétence spéciale de faction I : Défense sinistre
 **Description:** <span style="color: #645252;font-size:20px">Les unités de la Nécropole connaissent bien les environnements sinistres. Leurs dégâts augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> lorsqu'elles affrontent des unités &lt;démotivées&gt;.</span><span style="color: black">

### Compétence spéciale de faction II : Harmonie du sortilège
 **Description:** <span style="color: #645252;font-size:20px">Les unités de la Nécropole savent inhiber la magie. Sur le champ de bataille, la résistance magique de toutes les unités ennemies diminue de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span> %.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1+10)"
    let str8 = "(LEVEL*0.5+2.5)"
    let str5 = "LEVEL*2+8"
    let str6 = "LEVEL*3+12"
    let str3 = "LEVEL*1+9"
    let str4 = "LEVEL*1+5"
    let str1 = "(LEVEL*10+190)*0.01*ATK"
    let str2 = "LEVEL*0.5+4.5"
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

* **Nécropole**  (Groupement - Nécropole)
* **Défense**  (Groupement - Défense)
* **SR**  (SR)

### Bonus de héros
* [Mephala](/fr/heroes/Mephala/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Sandro (humain)](/fr/heroes/Human Sandro/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Sandro](/fr/heroes/Sandro/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Défense
* réduction des dégâts d'unité

 **:** [Potion de talent (Défensive)](/fr/Items/con_787/)


## Awaking

  ![Roi Momie](/images/u/tia_munaiyi.jpg)

### Awaking Détails
 **Is it possible right now?** YES

 **Awaking Name:** Roi Momie

 **Awaking Description:** Déjà mort, quiconque fixe l'âme d'un corps immortel risque de se transformer en momie. Après des millénaires de silence, Pharaon voue une haine farouche envers tous les êtres vivants. Le Roi Momie lance une malédiction à tous ceux qu'il croise pour les transformer en monstre non mort.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Déployez 1 Momie et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unités de la Nécropole pour réussir 1 fois le niveau Impitoyable, ou un niveau supérieur, de l'Utopie draconique. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> pièces d'équipement lors d'une aventure de guilde.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> âmes de Roi Momie dans les niveaux 15-2 et 15-4 du Souterrain.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Déployez 1 Momie et remportez </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> combat de Duel de champions.</span>

## Awaken Skills

### 1st Skill (or 2nd): Putréfaction maudite
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Malédiction putride&gt; : </span><span style="color: #645252;font-size:18px">Peut être déclenchée une fois toutes les 18 secondes. Les dégâts infligés augmentent à 150 % de sa valeur précédente. \"Maladie\" réduit de 10 % supplémentaires la résistance aux dégâts de l'ennemi. Cet effet supplémentaire double si la cible appartient au Rempart. La portée de &lt;Malédiction Putride&gt; augmente considérablement.</span>

### 2nd Skill (or 1st): Volonté de la mort
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Malédiction putride&gt; : </span><span style="color: #645252;font-size:18px">Peut être déclenchée une fois toutes les 18 secondes. Les dégâts infligés augmentent à 150 % de sa valeur précédente. \"Maladie\" réduit de 10 % supplémentaires la résistance aux dégâts de l'ennemi. L'effet de \"Maladie\" ne peut pas être dissipé. La portée de &lt;Malédiction Putride&gt; augmente considérablement.</span>

### 3rd Skill (or 4th): Croisé en armure
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Linceul&gt; : </span><span style="color: #645252;font-size:18px">La résistance aux dégâts de la Momie augmente de 20 %. La durée du bonus de &lt;Linceul&gt; augmente de 5 secondes. La résistance aux dégâts des alliés à portée augmente de 20 %, et leurs PV sont restaurés à hauteur de 5 % de leurs PV max.</span>

### 4th Skill (or 3rd): Linceul renforcé
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Linceul&gt; : </span><span style="color: #645252;font-size:18px">La résistance aux dégâts de la Momie augmente de 20%. La durée du bonus de &lt;Linceul&gt; augmente de 5 secondes. La résistance aux dégâts de l'unité augmente de 20 % supplémentaires pour chaque unité de la Nécropole, et leurs PV sont restaurés à hauteur de 5 % de leurs PV max.</span>

### 5th Skill (or 6th): Mutation de la maladie
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Source de maladie&gt; : </span><span style="color: #645252;font-size:18px">Réduit les soins des ennemis de 20 %. L'effet s'applique à tous les ennemis.</span>

### 6th Skill (or 5th): Infection de la maladie
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Source de maladie&gt; : </span><span style="color: #645252;font-size:18px">Diminue la résistance aux dégâts de tous les ennemis de 10 %.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 5.0

 **Rush:** 1

 **Speedattack:** 100

 **Attack Show:** 8.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 5.0

 **Score:** 1405

 **HP Show:** 8

 **disrdcvol:** 40

 **Dead Type:** 3

 **s:** 2

 **label1:** 10

 **speedmove:** 90

 **posclass:** 2

 **talk1:** Ma lance est indestructible !

 **talk2:** Seuls les morts se dressent face à moi !

 **talk3:** Je lutterai pour mon foyer et mes terres !

