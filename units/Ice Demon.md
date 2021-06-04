---
title: "Démone de glace"
permalink: /units/Ice Demon/
excerpt: "Era of Chaos Démone de glace. Démone de glace Unités. null. Era of Chaos La Démone de glace est une créature singulière, même pour le Plan du Conflux. Elle est semblable à de la glace qui ne fond jamais. Elle vous aveugle et vous coupe le souffle. Elle ressemble aux cadavres que l'on enterre dans des tombes glaciales."
unitID: 908
last_modified_at: 2021-06-03
locale: fr
ref: "Démone de glace"
toc: true
---
  ![Démone de glace](/images/u/ti_bingmo.jpg)

## General information
 **Description:** La Démone de glace est une créature singulière, même pour le Plan du Conflux. Elle est semblable à de la glace qui ne fond jamais. Elle vous aveugle et vous coupe le souffle. Elle ressemble aux cadavres que l'on enterre dans des tombes glaciales.

 **Classe:** [À distance](/fr/units/Unit Class Ranged/)

 **Classe Description:** Plus une unité à distance sera éloignée de sa cible, plus son attaque sera puissante.

 **Faction :** [Conflux](/fr/units/Faction Conflux/)

 **Race:** Maître des bêtes

 **Members:** [x1](/fr/units/Unit Member x1/)

 **Rang:** [Commandant](/fr/units/Unit Rank Commander/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 3/)

 **Unit Soul:** [Démone de glace](/ItemsFR/unt_269/)

 **Short description:** Contrôle un Arbalétrier. Octroie des bonus aux alliés.

 **Position :** Contrôle un Arbalétrier. Octroie des bonus aux alliés.

## Stats de base
 **Base HP: 5996.3**

 **Base ATK: 565.7**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 282.85 | 12.75 | 4497.225 |
  | Bleu | 565.7 | 25.5 | 8994.45 |
  | Bleu +1 | 848.55 | 38.25 | 13491.675 |
  | Bleu +2 | 1187.97 | 53.55 | 18888.345 |
  | Violet | 1527.39 | 68.85 | 24285.015 |
  | Violet +1 | 1866.81 | 84.15 | 29681.685 |
  | Violet +2 | 2262.8 | 102.0 | 35977.8 |
  | Violet +3 | 2658.79 | 119.85 | 42273.915 |
  | Orange | 3054.78 | 137.7 | 48570.03 |
  | Orange +1 | 3507.34 | 158.1 | 55765.59 |
  | Orange +2 | 3959.9 | 178.5 | 62961.15 |
  | Orange +3 | 4412.46 | 198.9 | 70156.71 |
  | Orange +4 | 4865.02 | 219.3 | 77352.27 |
  | Orange +5 | 5543.86 | 249.9 | 88145.61 |
  | Rouge | 6448.98 | 290.7 | 102536.73 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 79.198 | 0.5 | 6.61 | 839.482 |
  | **4x** <i class="fas fa-star"/> | 90.512 | 0.52 | 7.37 | 959.408 |
  | **5x** <i class="fas fa-star"/> | 101.826 | 0.54 | 8.12 | 1079.334 |
  | **6x** <i class="fas fa-star"/> | 113.14 | 0.56 | 8.88 | 1199.26 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Glace ancestrale](/images/e/e_9081.png) | [Glace ancestrale](/fr/equipment/Ancient Ice/) | **ATQ** | **DÉF** | 
  | ![Toucher glacial](/images/e/e_9082.png) | [Toucher glacial](/fr/equipment/Frost Touch/) | **PV** | **DÉF** | 
  | ![Heaume gelé](/images/e/e_9083.png) | [Heaume gelé](/fr/equipment/Frigid Helm/) | **ATQ** | **DÉF** | 
  | ![Trône de glace](/images/e/e_9084.png) | [Trône de glace](/fr/equipment/Throne of Ice/) | **PV** | **DÉF** | 

## Exclusif


## Emblèmes sacrés recommandés

* [Feu ancien](/fr/Emblem/Ancient Fire/) (Ordre)
* [Ailes de Griffon](/fr/Emblem/Griffin Wings/) (Ordre)
* [Orgueil](/fr/Emblem/Arrogance/) (Chaos)

## Infos combinaison

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Épine glaciale
 **Description:** <span style="color: #645252;font-size:20px">La Démone de glace lance &lt;Épine glaciale&gt; toutes les 11 secondes et inflige des dégâts équivalents à </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de l'ATQ à l'unité ciblée 3 fois. Si &lt;Épine glaciale&gt; réalise un coup critique, elle inflige des dégâts supplémentaires équivalents à </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de l'ATQ à 3 unités ennemies dans un vaste périmètre et inflige </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gelure</span><span style="color: black"><span style="color: #645252;font-size:20px"> pendant 6 secondes.</span><span style="color: black">

### Compétence normale 1 : Triomphe de givre
 **Description:** <span style="color: #645252;font-size:20px">Augmente les dégâts d'unité de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et octroie</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de drain de vie.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Augmente la vitesse d'attaque de la Démone de glace de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et ses coups critiques de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> points pour chaque unité du Conflux déployée.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Augmente les dégâts de la Démone de glace de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et sa pénétration de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> points pour chaque unité à distance et Lanceurs de sorts déployés.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Les attaques normales de la Démone de glace ont </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de chance d'infliger </span><span style="color: black"><span style="color: #48b946;font-size:20px">Lenteur</span><span style="color: black"><span style="color: #645252;font-size:20px"> à l'unité ciblée pendant </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str10"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> secondes.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Les attaques normales de la Démone de glace ont </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str11"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de chance d'infliger </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gel</span><span style="color: black"><span style="color: #645252;font-size:20px"> à l'unité ciblée. Cet effet ne peut pas être dissipé et dure 4 secondes. Le temps de recharge est de 8 secondes.</span><span style="color: black">

### Compétence normale 2 : Zéro absolu
 **Description:** <span style="color: #645252;font-size:20px">Lorsque la Démone de glace est sur le champ de bataille, les unités défensives ennemies qui ont des PV supérieurs à 50 % subiront des dégâts équivalents à </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str12"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> des PV max toutes les 3 secondes. Cet effet augmente de 30 % pour les unités touchées par </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gelure</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Lorsque la Démone de glace se bat contre des unités ennemies touchées par </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gel</span><span style="color: black"><span style="color: #645252;font-size:20px">, </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gelure</span><span style="color: black"><span style="color: #645252;font-size:20px">, ou </span><span style="color: black"><span style="color: #48b946;font-size:20px">Arrêt du temps</span><span style="color: black"><span style="color: #645252;font-size:20px">, inflige des dégâts supplémentaires équivalents à </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str13"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de l'ATQ de la Démone de glace toutes les 3 secondes.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Lorsque la Démone de glace est sur le champ de bataille, un jugement sera émis toutes les 3 secondes, après quoi la vitesse d'attaque de toutes les unités ennemies dont les PV sont inférieurs à 50 % sera réduite de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str14"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Ces unités auront également 10 % de chance d'être touchées par </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gelure</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence normale 3 : Maîtresse de la glace
 **Description:** <span style="color: #645252;font-size:20px">La Démone de glace et les unités (hors Forteresse) situées dans un vaste périmètre autour de la Démone de glace sont immunisées contre </span><span style="color: black"><span style="color: #48b946;font-size:20px">Gel</span><span style="color: black"><span style="color: #645252;font-size:20px"> et </span><span style="color: black"><span style="color: #48b946;font-size:20px">Arrêt du temps</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Toutes les 13 secondes, la Démone de glace octroie </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Armure de cristal&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> aux unités à distance et de Lanceurs de sorts alliées, augmentant leur résistance aux dégâts d'unité de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str15"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et leur renvoi de dégâts de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str16"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Cet effet ne peut pas être dissipé ni cumulé. Il dure 6 secondes et disparaît après que l'unité a subi 5 fois des dégâts. Ce chiffre est doublé pour la Démone de glace.</span><span style="color: black">

### Compétence spéciale de faction I : Affinité élémentaire
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Conflux sont connues pour leur maîtrise des arcanes magiques du Conflux, et augmentent la résistance magique des Héros de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str17"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence spéciale de faction II : Conflit élémentaire
 **Description:** <span style="color: #645252;font-size:20px">Les unités du Conflux maîtrisent particulièrement bien les dégâts du Conflux. Lorsqu'elles affrontent des unités qui n'appartiennent pas au Conflux, leurs dégâts augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str18"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence normale 6 : Domaine de givre
 **Description:** <span style="color: #645252;font-size:20px">Augmente les dégâts d'unité de la Démone de glace de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str19"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> et la vitesse d'attaque de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str20"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> lorsque 3 unités du Conflux sont déployées.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">8 secondes après le début du combat, </span><span style="color: black"><span style="color: #F0F000;font-size:20px">&lt;Domaine de givre&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"></span><span style="color: black"><span style="color: #645252;font-size:20px"> se forme, puis s'étend avec l'augmentation du niveau de la compétence. Ce domaine existe pendant 15 secondes, après quoi il est déclenché une fois toutes les 30 secondes.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str20 = "LEVEL*2+5"
    let str7 = "LEVEL*0.7+4.5"
    let str8 = "LEVEL*5+25"
    let str5 = "LEVEL*0.7+4.5"
    let str18 = "(LEVEL*1+5)"
    let str6 = "LEVEL*5+25"
    let str19 = "LEVEL*2+4"
    let str3 = "LEVEL*1+15"
    let str4 = "LEVEL*0.5+12.5"
    let str1 = "LEVEL*5+45"
    let str2 = "LEVEL*4+10"
    let str12 = "LEVEL*0.2+4"
    let str13 = "LEVEL*3+10"
    let str10 = "LEVEL*0.2+1.8"
    let str11 = "LEVEL*0.5+23.5"
    let str16 = "LEVEL*2+2"
    let str17 = "(LEVEL*3+15)"
    let str9 = "LEVEL*1.5+22.5"
    let str14 = "LEVEL*1+10"
    let str15 = "LEVEL*5+25"
    let res="ERR";
    try {
     res = eval(str20); document.getElementById('str20').textContent = res;
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str18); document.getElementById('str18').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str19); document.getElementById('str19').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
     res = eval(str12); document.getElementById('str12').textContent = res;
     res = eval(str13); document.getElementById('str13').textContent = res;
     res = eval(str10); document.getElementById('str10').textContent = res;
     res = eval(str11); document.getElementById('str11').textContent = res;
     res = eval(str16); document.getElementById('str16').textContent = res;
     res = eval(str17); document.getElementById('str17').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
     res = eval(str14); document.getElementById('str14').textContent = res;
     res = eval(str15); document.getElementById('str15').textContent = res;
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
* **À distance**  (Groupement - À distance)
* **Commandant**  (Commandant)

### Bonus de héros
* [Gelu](/fr/heroes/Gelu/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Ciele](/fr/heroes/Ciele/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Vitesse d'attaque
* dégâts d'unité

 **:** [Potion de talent (Arbalétrier)](/ItemsFR/con_789/)


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

 **defshow:** 1.0

 **fly:** bingmodandao

 **flyspeed:** 700

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 80

 **Attack Show:** 1.0

 **Attack Area:** 370

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 1349

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 11

 **speedmove:** 90

 **posclass:** 4

 **talk1:** Ma lance est indestructible !

 **talk2:** Seuls les morts se dressent face à moi !

 **talk3:** Je lutterai pour mon foyer et mes terres !

