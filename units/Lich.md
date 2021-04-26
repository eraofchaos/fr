---
title: "Liche"
permalink: /units/Lich/
excerpt: "Era of Chaos Liche. Liche Unités. Grande Liche. Era of Chaos Les corps des Liches sont flétris, tordus et pourris. Elles haïssent tous les êtres vivants et ne rêvent que de mort et de destruction."
unitID: 305
last_modified_at: 2021-04-26
locale: fr
ref: "Liche"
toc: true
---
  ![Liche](/images/u/ti_wuyao.jpg)

## General information
 **Description:** Les corps des Liches sont flétris, tordus et pourris. Elles haïssent tous les êtres vivants et ne rêvent que de mort et de destruction.

 **Classe:** [Lanceur de sorts](/fr/units/Unit Class Caster/)

 **Classe Description:** Grâce à leur maîtrise des secrets de la magie, les Lanceurs de sorts bénéficient d'une résistance à la magie plus importante.

 **Faction :** [Nécropole](/fr/units/Faction Necropolis/)

 **Race:** Non-Morts

 **Members:** [x4](/fr/units/Unit Member x4/)

 **Rang:** [SR](/fr/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/fr/units/Star 3/)

 **Unit Soul:** [Liche](/ItemsFR/unt_212/)

 **Unit description:** Sacrifice : invoque une horde de Squelettes.

 **Short description:** Fait appel à des squelettes. Magie squelettique améliorée.

 **Position :** Peut invoquer et améliorer des Squelettes. La base de toute stratégie d'invocation de Morts-vivants.

 **Recommend:** Ces créatures ont peu de santé, mais elles frappent fort. Elles seront très puissantes si vous pensez à les soigner.

## Stats de base
 **Base HP: 1581.0**

 **Base ATK: 228.7**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Vert | 114.35 | 4.0 | 1185.75 |
  | Bleu | 228.7 | 8.0 | 2371.5 |
  | Bleu +1 | 343.05 | 12.0 | 3557.25 |
  | Bleu +2 | 480.27 | 16.8 | 4980.15 |
  | Violet | 617.49 | 21.6 | 6403.05 |
  | Violet +1 | 754.71 | 26.4 | 7825.95 |
  | Violet +2 | 914.8 | 32.0 | 9486.0 |
  | Violet +3 | 1074.89 | 37.6 | 11146.05 |
  | Orange | 1234.98 | 43.2 | 12806.1 |
  | Orange +1 | 1417.94 | 49.6 | 14703.3 |
  | Orange +2 | 1600.9 | 56.0 | 16600.5 |
  | Orange +3 | 1783.86 | 62.4 | 18497.7 |
  | Orange +4 | 1966.82 | 68.8 | 20394.9 |
  | Orange +5 | 2241.26 | 78.4 | 23240.7 |
  | Rouge | 2607.18 | 91.2 | 27035.1 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 32.018 | 0.44 | 2.76 | 221.34 |
  | **4x** <i class="fas fa-star"/> | 36.592 | 0.46 | 3.34 | 252.96 |
  | **5x** <i class="fas fa-star"/> | 41.166 | 0.48 | 3.92 | 284.58 |
  | **6x** <i class="fas fa-star"/> | 45.74 | 0.5 | 4.5 | 316.2 |

## Équipement

  | I | Équipement  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Bâton des limbes](/images/e/e_3051.png) | [Bâton des limbes](/fr/equipment/Nether Staff/) | **ATQ** | **DÉF** | 
  | ![Couronne noire](/images/e/e_3052.png) | [Couronne noire](/fr/equipment/Carrion Crown/) | **PV** | **DÉF** | 
  | ![Ceinture spirituelle](/images/e/e_3053.png) | [Ceinture spirituelle](/fr/equipment/Soul Belt/) | **ATQ** | **DÉF** | 
  | ![Armure légère des limbes](/images/e/e_3054.png) | [Armure légère des limbes](/fr/equipment/Light Armor of the Netherworld/) | **PV** | **DÉF** | 

## Exclusif

 **Nom:** [Hommage mortel](/fr/Exclusive/Lich Death Tribute/) 

 **Is Open:** + 

 **Item to Rang supérieur:** [Jeton Hommage mortel](/ItemsFR/con_978/)

 **Skin:** [Peau spéciale Hommage mortel](/ItemsFR/con_646/)


## Emblèmes sacrés recommandés

* [Secret éternel](/fr/Emblem/Everlasting Secret/) (Ordre)
* [Clé en pierre](/fr/Emblem/Stone Key to the Gates/) (Neutre)
* [Autonyme oublié](/fr/Emblem/Forgotten Autonym/) (Mauvais)

## Infos combinaison

* [Saignement](/combination/Saignement/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label>Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Capacité ultime: Sacrifice
 **Description:** <span style="color: #645252;font-size:20px">Quand sa cible meurt, la Liche a une chance d'invoquer un Squelette avec </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> en ATQ et </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> PV qui perdure pendant tout le combat.</span><span style="color: black">

### Compétence normale 1 : Nuage acide
 **Description:** <span style="color: #645252;font-size:20px">L'attaque normale de la Liche a une chance d'infliger </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> de dégâts à 3 ennemis. Les dégâts infligés aux cibles victimes de </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Saignement&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> augmentent de 30 %.</span><span style="color: black">

### Compétence normale 2 : Bonus de ténèbres
 **Description:** <span style="color: #645252;font-size:20px">L'ATQ de la Liche augmente de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. La portée d'attaque de la Liche augmente de 50 pour chaque unité de la Nécropole présente sur le champ de bataille.</span><span style="color: black">

### Compétence normale 3 : Sacrifice squelettique
 **Description:** <span style="color: #645252;font-size:20px">Quand la Liche est sur le champ de bataille, les PV et l'ATQ des Squelettes et des Dragons squelettes augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Compétence spéciale de faction I : Défense sinistre
 **Description:** <span style="color: #645252;font-size:20px">Les unités de la Nécropole connaissent bien les environnements sinistres. Leurs dégâts augmentent de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> lorsqu'elles affrontent des unités &lt;démotivées&gt;.</span><span style="color: black">

### Compétence spéciale de faction II : Harmonie du sortilège
 **Description:** <span style="color: #645252;font-size:20px">Les unités de la Nécropole savent inhiber la magie. Sur le champ de bataille, la résistance magique de toutes les unités ennemies diminue de </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*0.5+2.5)"
    let str5 = "LEVEL*2+13"
    let str6 = "(LEVEL*1+10)"
    let str3 = "LEVEL*10+90"
    let str4 = "LEVEL*4+16"
    let str1 = "(LEVEL*1.5+10.5)*(TLEVEL+9)"
    let str2 = "(LEVEL*30+220)*(TLEVEL+9)"
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

* **Nécropole**  (Groupement - Nécropole)
* **Lanceur de sorts**  (Groupement - Lanceur de sorts)
* **SR**  (SR)

### Bonus de héros
* [Vidomina](/fr/heroes/Vidomina/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Sandro](/fr/heroes/Sandro/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Sandro (humain)](/fr/heroes/Human Sandro/)  ->   Spécialité :<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Attaque
* PV
* Vitesse d'attaque
* Coup critique d'unité

 **:** [Potion de talent (Lanceur de sorts)](/ItemsFR/con_790/)


## Awaking

  ![Grande Liche](/images/u/tia_wuyao.jpg)

### Awaking Détails
 **Is it possible right now?** YES

 **Awaking Name:** Grande Liche

 **Awaking Description:** Pour découvrir le véritable sens de la mort et le mystère de la vie éternelle, ces explorateurs mystiques n'hésiteront pas à sacrifier des vies humaines. Après cette grande cérémonie, les Sorciers immortels renaîtront à nouveau.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Déployez 1 Liche et au moins </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unités de la Nécropole pour réussir </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> fois le niveau Champion, ou un niveau supérieur, de l'Utopie draconique. (Les raids ne comptent pas pour la mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Éliminez </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> monstres lors d'une aventure de guilde.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Récupérez </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> âmes de Grande Liche dans les niveaux 17-2 et 17-4 du Souterrain.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Déployez Vidomina et 1 Liche pour remporter </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> combat de Duel de champions.</span>

## Awaken Skills

### 1st Skill (or 2nd): Invocation de Squelettes
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Sacrifice&gt; : </span><span style="color: #645252;font-size:18px">Invoque 2 Squelettes en même temps.</span>

### 2nd Skill (or 1st): Invocation de Non-Morts
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Sacrifice&gt; : </span><span style="color: #645252;font-size:18px">Le Squelette invoqué se change en Squelette armé dont les attaques normales ont 8 % de chance d'étourdir leur cible.</span>

### 3rd Skill (or 4th): Sacrifice macabre
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Sacrifice squelettique&gt; : </span><span style="color: #645252;font-size:18px">Augmente la vitesse d'ATQ de la Liche de 20 % et ses coups critiques de 200 points pendant 20 secondes. Ce bonus double pour chaque unité abattue.</span>

### 4th Skill (or 3rd): Baiser de la Mort
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Sacrifice squelettique&gt; : </span><span style="color: #645252;font-size:18px">Augmente la DÉF et le drain de vie pour les unités de la Nécropole de 20 % pendant 20 secondes. Ce bonus double pour chaque unité ennemie abattue.</span>

### 5th Skill (or 6th): Contrat magique
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Bonus de ténèbres&gt; : </span><span style="color: #645252;font-size:18px">La Liche inflige 5 % de dégâts supplémentaires pour chaque unité de Lanceurs de sorts présente sur le champ de bataille.</span>

### 6th Skill (or 5th): Contrat des morts
 **Description:** <span style="color: #48b946;font-size:18px">&lt;Incinération&gt; : </span><span style="color: #645252;font-size:18px">La Liche inflige 5 % de dégâts supplémentaires pour chaque unité de la Nécropole présente sur le champ de bataille.</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **fly:** guihunlan

 **flyspeed:** 300

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 8.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 4.0

 **Score:** 1405

 **HP Show:** 7

 **disrdcvol:** 70

 **Dead Type:** 3

 **s:** 1

 **label1:** 1

 **speedmove:** 80

 **posclass:** 5

 **talk1:** Ma lance est indestructible !

 **talk2:** Seuls les morts se dressent face à moi !

 **talk3:** Je lutterai pour mon foyer et mes terres !

