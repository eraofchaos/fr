---
title: "Ogre"
permalink: /units/Ogre/
excerpt: "Era of Chaos Ogre. Ogre Unités. Ogre Mage. Era of Chaos Les Ogres ressemblent un peu à des gros singes, mais en bien plus dangereux. Ils sont même capables de lancer des sorts sanguinaires en combat."
unitID: 404
last_modified_at: 2021-04-25
locale: fr
ref: "Ogre"
toc: true
---
  ![Ogre](/images/u/ti_shirenmo.jpg)

## General information
 **Description:** Les Ogres ressemblent un peu à des gros singes, mais en bien plus dangereux. Ils sont même capables de lancer des sorts sanguinaires en combat.

 **Classe:** [Défense](/fr/units/Unit Class Defense/)

 **Classe Description:** Les unités défensives peuvent résister aux attaques pendant plus longtemps et subissent moins de dégâts.

 **Faction :** [Bastion](/fr/units/Faction Stronghold/)

 **Race:** Barbare

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rang:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 2/)

 **Unit Soul:** [Ogre](/ItemsFR/unt_220/)

 **Unit description:** Mare de sang : améliore le drain de vie de vos unités à proximité.

 **Short description:** Dispose d'un bouclier et d'une aura de soin.

 **Position :** Un puissant bouclier corporel qui améliore l'efficacité de toutes vos troupes de mêlée.

 **Recommend:** Ces créatures ont peu de santé, mais elles frappent fort. Elles seront très puissantes si vous pensez à les soigner.

## Stats de base
 **Base HP: 2523.0**

 **Base ATK: 107.6**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 53.8 | 15.0 | 1892.25 |
  | Bleu | 107.6 | 30.0 | 3784.5 |
  | Bleu +1 | 161.4 | 45.0 | 5676.75 |
  | Bleu +2 | 225.96 | 63.0 | 7947.45 |
  | Violet | 290.52 | 81.0 | 10218.15 |
  | Violet +1 | 355.08 | 99.0 | 12488.85 |
  | Violet +2 | 430.4 | 120.0 | 15138.0 |
  | Violet +3 | 505.72 | 141.0 | 17787.15 |
  | Orange | 581.04 | 162.0 | 20436.3 |
  | Orange +1 | 667.12 | 186.0 | 23463.9 |
  | Orange +2 | 753.2 | 210.0 | 26491.5 |
  | Orange +3 | 839.28 | 234.0 | 29519.1 |
  | Orange +4 | 925.36 | 258.0 | 32546.7 |
  | Orange +5 | 1054.48 | 294.0 | 37088.1 |
  | Rouge | 1226.64 | 342.0 | 43143.3 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 12.912 | 0.36 | 6.8 | 302.76 |
  | **3x** <i class="fas fa-star"/> | 15.064 | 0.37 | 7.6 | 353.22 |
  | **4x** <i class="fas fa-star"/> | 17.216 | 0.39 | 8.4 | 403.68 |
  | **5x** <i class="fas fa-star"/> | 19.368 | 0.41 | 9.2 | 454.14 |
  | **6x** <i class="fas fa-star"/> | 21.52 | 0.43 | 10.0 | 504.6 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Bâton bélier](/images/e/e_4041.png) | [Bâton bélier](/fr/equipment/Rams-head Staff/) | **ATQ** | **DÉF** | 
  | ![Ceinture du rituel](/images/e/e_4042.png) | [Ceinture du rituel](/fr/equipment/Belt of Ritual/) | **PV** | **DÉF** | 
  | ![Talisman tribal](/images/e/e_4043.png) | [Talisman tribal](/fr/equipment/Tribal Talisman/) | **ATQ** | **DÉF** | 
  | ![Épaulières du rituel](/images/e/e_4044.png) | [Épaulières du rituel](/fr/equipment/Pauldrons of Ritual/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Bouclier iris](/fr/Exclusive/Ogre Iris Shield/) 

 **Is Open:** + 

 **Item to Rang supérieur:** [Jeton Bouclier iris](/ItemsFR/con_913/)

 **Skin:** -


## Emblèmes sacrés recommandés

* [Bénédiction de la reine](/fr/Emblem/Queen's Blessing/) (Ordre)
* [Roue du temps](/fr/Emblem/Gear of Time/) (Bonté)
* [Luxure](/fr/Emblem/Lust/) (Chaos)

## Infos combinaison

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label>Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Mare de sang
 **Description:** <span style="color: #645252;font-size:20px">L'Ogre invoque une mare de sang pour augmenter le drain de vie des unités alliées de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> dans une large zone. La mare de sang dure 15 secondes.</span><span style="color: black">

### Compétence normale 1 : Peau du Sorcier
 **Description:** <span style="color: #645252;font-size:20px">La DÉF de l'Ogre augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">, sa régénération de PV de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> et les dégâts de l'unité de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %.</span><span style="color: black">

### Compétence normale 2 : Carnage
 **Description:** <span style="color: #645252;font-size:20px">Quand les PV de l'Ogre tombent sous la barre des 35 %, l'ATQ de toutes les unités alliées augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant toute la durée du combat.</span><span style="color: black">

### Compétence normale 3 : Détox
 **Description:** <span style="color: #645252;font-size:20px">Quand un Ogre est sur le champ de bataille, les soins prodigués à toutes les unités alliées augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

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
    let str5 = "LEVEL*1+9"
    let str6 = "(LEVEL*3+12)"
    let str3 = "LEVEL*160+640"
    let str4 = "LEVEL*0.5+2.5"
    let str1 = "LEVEL*3+27"
    let str2 = "(LEVEL*0.3+0.7)*(TLEVEL+9)"
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
* **Défense**  (Groupement - Défense)
* **SR**  (SR)

### Bonus de héros
* [Mephala](/fr/heroes/Mephala/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Crag Hack](/fr/heroes/Crag Hack/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Kilgor](/fr/heroes/Kilgor/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Défense
* réduction des dégâts d'unité

 **:** [Potion de talent (Défensive)](/ItemsFR/con_787/)


## Awaking

  ![Ogre Mage](/images/u/tia_shirenmo.jpg)

### Awaking Détails
 **Is it possible right now?** YES

 **Awaking Name:** Ogre Mage

 **Awaking Description:** Les chefs dirigent leurs tribus d'une main de fer. Le drapeau terrifiant représentant des os d'animaux symbolise à merveille leur identité. Courte est la vie des inconscients qui se lancent dans un défi dépassant leurs aptitudes ; ils viennent grossir les rangs des sacrifiés offerts au drapeau.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Déployez 1 Ogre et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unités du Bastion pour réussir </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> fois le niveau Maître, ou un niveau supérieur, de l'Utopie draconique. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> ressources lors d'une aventure de guilde.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> âmes d'Ogre Mage dans les niveaux 16-2 et 16-4 du Souterrain.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Déployez Crag Hack et 1 Ogre pour remporter </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> combat de Duel de champions.</span>

## Awaken Skills

### 1st Skill (or 2nd): Fontaine de Jouvence
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Mare de sang&gt; : </span><span style="color: #645252;font-size:18px">L'effet augmente à 150 % de sa valeur précédente. La durée est prolongée de 10 secondes.</span>

### 2nd Skill (or 1st): Source sauvage
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Mare de sang&gt; : </span><span style="color: #645252;font-size:18px">L'effet augmente de 50 % et sa portée est accrue.</span>

### 3rd Skill (or 4th): Cœur sauvage
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Carnage&gt; : </span><span style="color: #645252;font-size:18px">Augmente la résistance aux dégâts de l'Ogre de 20 %. L'effet double quand l'unité est déchaînée.</span>

### 4th Skill (or 3rd): Chant de guerre exaltant
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Carnage&gt; : </span><span style="color: #645252;font-size:18px">Augmente la résistance aux dégâts de l'Ogre de 20 %. Augmente l'ATQ à hauteur de 200 % de l'ATQ de la compétence précédente quand l'unité est déchaînée.</span>

### 5th Skill (or 6th): Afflux ancestral
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Détox&gt; : </span><span style="color: #645252;font-size:18px">L'effet augmente à 150 % de sa valeur précédente.</span>

### 6th Skill (or 5th): Protection du patriarche
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Détox&gt; : </span><span style="color: #645252;font-size:18px">L'effet est maintenu même après la mort de l'Ogre.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 9.0

 **Rush:** 1

 **Speedattack:** 100

 **Attack Show:** 3.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 4.0

 **Defense Show:** 9.0

 **Score:** 794

 **HP Show:** 8

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 2

 **label1:** 5

 **speedmove:** 90

 **posclass:** 2

 **talk1:** Les ogres ne se disputent jamais. Ferme-la, toi ! Je t'ai dit de la fermer !

 **talk2:** Alors comme ça, vous comptez vous enfuir ? Vous croyez y parvenir ?

 **talk3:** Vous allez voir, je vais tous vous écraser !

