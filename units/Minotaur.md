---
title: "Minotaure"
permalink: /units/Minotaur/
excerpt: "Era of Chaos Unités. Unités. Era of Chaos Une créature puissante qui se cache dans un labyrinthe sombre. Sa hache immense lui permet de couper en morceaux tout ennemi qui s'y égare."
unitID: 705
last_modified_at: 2021-03-18
locale: fr
ref: "Minotaure"
toc: true
---
## General information
 **Description:** Une créature puissante qui se cache dans un labyrinthe sombre. Sa hache immense lui permet de couper en morceaux tout ennemi qui s'y égare.

 **Classe:** [Défense](/fr/units/Unit Class Defense/)

 **Classe Description:** Les unités défensives peuvent résister aux attaques pendant plus longtemps et subissent moins de dégâts.

 **Faction :** [Donjon](/fr/units/Faction Dungeon/)

 **Race:** Troupes du Donjon

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rank:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 2/)

 **Unit Soul:** [Minotaure](/fr/Items/unt_248/)

 **Unit description:** Tourbillon : inflige des dégâts de zone et diminue la vitesse d'ATQ.

 **Short description:** Soutien. Sert aussi de tank.

 **Position :** Tank de soutien, le mélange parfait entre l'attaque et la défense. Saignement augmente les DPS alliés.

 **Recommend:** Ces créatures ont peu de santé, mais elles frappent fort. Elles seront très puissantes si vous pensez à les soigner.

## Stats de base
 **Base HP: 2725.0**

 **Base ATK: 108.0**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 54.0 | 13.75 | 2043.75 |
  | Bleu | 108.0 | 27.5 | 4087.5 |
  | Bleu +1 | 162.0 | 41.25 | 6131.25 |
  | Bleu +2 | 226.8 | 57.75 | 8583.75 |
  | Violet | 291.6 | 74.25 | 11036.25 |
  | Violet +1 | 356.4 | 90.75 | 13488.75 |
  | Violet +2 | 432.0 | 110.0 | 16350.0 |
  | Violet +3 | 507.6 | 129.25 | 19211.25 |
  | Orange | 583.2 | 148.5 | 22072.5 |
  | Orange +1 | 669.6 | 170.5 | 25342.5 |
  | Orange +2 | 756.0 | 192.5 | 28612.5 |
  | Orange +3 | 842.4 | 214.5 | 31882.5 |
  | Orange +4 | 928.8 | 236.5 | 35152.5 |
  | Orange +5 | 1058.4 | 269.5 | 40057.5 |
  | Rouge | 1231.2 | 313.5 | 46597.5 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 12.96 | 0.35 | 6.28 | 327.0 |
  | **3x** <i class="fas fa-star"/> | 15.12 | 0.36 | 7.05 | 381.5 |
  | **4x** <i class="fas fa-star"/> | 17.28 | 0.38 | 7.83 | 436.0 |
  | **5x** <i class="fas fa-star"/> | 19.44 | 0.4 | 8.6 | 490.5 |
  | **6x** <i class="fas fa-star"/> | 21.6 | 0.41 | 9.38 | 545.0 |

## Équipement

  |  Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Hache de Gorgone](/fr/equipment/Hache de Gorgone/) | **ATQ** | **DÉF** | 
  | [Épaulières de Gorgone](/fr/equipment/Épaulières de Gorgone/) | **PV** | **DÉF** | 
  | [Bandeaux de Gorgone](/fr/equipment/Bandeaux de Gorgone/) | **ATQ** | **DÉF** | 
  | [Ceinture de Gorgone](/fr/equipment/Ceinture de Gorgone/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Bouclier iris](/fr/Exclusive/Minotaur Iris Shield/) 

 **Is Open:** - 

 **Item to Rang supérieur:** [Jeton Bouclier iris](/fr/Items/con_913/)

 **Skin:** -


## Emblèmes sacrés recommandés

* [Bénédiction de la reine](/fr/Emblem/Queen's Blessing/) (Ordre)
* [Roue du temps](/fr/Emblem/Gear of Time/) (Bonté)
* [Luxure](/fr/Emblem/Lust/) (Chaos)

## Infos combinaison

* [Saignement](/combination/Saignement/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Tourbillon
 **Description:** <span style="color: #645252;font-size:20px">Le Minotaure inflige </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> points de dégâts à 3 unités ennemies dans une large zone et diminue leur vitesse d'ATQ de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 6 secondes.</span><span style="color: black">

### Compétence normale 1 : Férocité brutale
 **Description:** <span style="color: #645252;font-size:20px">L'ATQ du Minotaure augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> </span><span style="color: black"><span style="color: #645252;font-size:20px"> supplémentaires. Son attaque normale applique un effet de <span style="color: #48b946;font-size:20px">&lt;Saignement&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> sur la cible pendant 6 secondes.</span><span style="color: black">

### Compétence normale 2 : Physique du briseur de sort
 **Description:** <span style="color: #645252;font-size:20px">Augmente la résistance magique du Minotaure et la résistance aux dégâts de l'unité de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant les 10 prochaines secondes. L'effet double chaque fois qu'un Héros ennemi lance un sort.</span><span style="color: black">

### Compétence normale 3 : Choix tactique
 **Description:** <span style="color: #645252;font-size:20px">Quand il subit des dégâts de la part d'une unité de 1 ou de 4 combattant(s), sa défense augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Quand il attaque une unité de 9 combattants, ses coups critiques augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence spéciale de faction : Conflit des ténèbres
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Donjon savent exploiter le terrain à leur avantage, augmentant de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> leurs dégâts lorsqu'elles affrontent des unités qui n'appartiennent pas au Donjon.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1+5)"
    let str5 = "LEVEL*2+8"
    let str6 = "LEVEL*40+160"
    let str3 = "LEVEL*80+320"
    let str4 = "LEVEL*1+4"
    let str1 = "((LEVEL*4+76))*0.01*ATK"
    let str2 = "LEVEL*1+4"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
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

* **Donjon**  (Groupement - Donjon)
* **Défense**  (Groupement - Défense)
* **SR**  (SR)

### Bonus de héros
* [Mephala](/fr/heroes/Mephala/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Mutare](/fr/heroes/Mutare/)  ->   Spécialité :<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Mutare (dragon)](/fr/heroes/Dragon Mutare/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Défense
* réduction des dégâts d'unité

 **:** [Potion de talent (Défensive)](/fr/Items/con_787/)


## Awaking
### Awaking Détails
 **Is it possible right now?** YES

 **Awaking Name:** Roi Minotaure

 **Awaking Description:** Les gigantesques haches de combat sont le symbole de leur pouvoir et le labyrinthe obscur qu'ils protègent est leur crédo. Le cruel Roi Minotaure est entouré par des squelettes et il n'hésitera pas à tuer tous les intrus.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Déployez 1 Minotaure et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unités du Donjon pour réussir 1 fois le niveau Champion, ou un niveau supérieur, de l'Utopie draconique. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> pièces d'équipement lors d'une aventure de guilde.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> âmes de Roi Minotaure dans les niveaux 17-2 et 17-4 du Souterrain.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Déployez 1 Minotaure et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unités du Donjon et remportez 1 combat de Duel de champions.</span>

## Awaken Skills

### 1st Skill (or 2nd): Lacération frénétique
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Tourbillon&gt; : </span><span style="color: #645252;font-size:18px">Quand le Minotaure est en état d'Exaltation, il active à coup sûr &lt;Tourbillon&gt;. Les dégâts infligés par &lt;Tourbillon&gt; sont doublés et diminuent la résistance aux dégâts de l'unité de 10 %. Cet effet dure 6 secondes et peut se cumuler jusqu'à 3 fois.</span>

### 2nd Skill (or 1st): Lacération stimulée
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Tourbillon&gt; : </span><span style="color: #645252;font-size:18px">Quand le Minotaure est en état d'Exaltation, il active à coup sûr &lt;Tourbillon&gt;. Les dégâts infligés par &lt;Tourbillon&gt; sont doublés et affectent tous les ennemis dans une large zone.</span>

### 3rd Skill (or 4th): Âme indomptable
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Physique du briseur de sort&gt; : </span><span style="color: #645252;font-size:18px">Si un Héros ennemi lance un sort, le Minotaure entre en état d'&lt;Exaltation&gt; pendant 5 secondes et regagne 5 % de ses PV max.</span>

### 4th Skill (or 3rd): Résistance à la magie
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Physique du briseur de sort&gt; : </span><span style="color: #645252;font-size:18px">Si un Héros ennemi lance un sort, le Minotaure entre en état d'&lt;Exaltation&gt; pendant 5 secondes et augmente sa résistance aux dégâts de 10 %. Cet effet peut se cumuler jusqu'à 3 fois pendant toute la durée de la bataille.</span>

### 5th Skill (or 6th): Volonté féroce
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Férocité brutale&gt; : </span><span style="color: #645252;font-size:18px">Quand il affronte des ennemis victimes de Saignement, les dégâts infligés par le Minotaure augmentent de 20 %. Si le Minotaure est victime de Saignement, sa vitesse d'attaque augmente de 20 % pendant 6 secondes.</span>

### 6th Skill (or 5th): Férocité sanglante
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Férocité brutale&gt; : </span><span style="color: #645252;font-size:18px">Quand il affronte des ennemis victimes de Saignement, les dégâts infligés par le Minotaure augmentent de 20 %. Si le Minotaure est victime de Saignement, sa résistance aux dégâts augmente de 20 % pendant 6 secondes.</span>

## Technical info
 **runart:** 1

 **summon:** 2

 **defshow:** 1.0

 **Rush:** 1

 **Speedattack:** 100

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 794

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 2

 **s:** 2

 **label1:** 7

 **speedmove:** 90

 **posclass:** 2

 **talk1:** Ma lance est indestructible !

 **talk2:** Seuls les morts se dressent face à moi !

 **talk3:** Je lutterai pour mon foyer et mes terres !

