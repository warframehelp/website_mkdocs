
# Modding


## Infos de base

Dans votre arsenal, vous pouvez modifier/améliorer votre équipement.
Une fois une frame ou une arme sélectionnée vous pouvez choisir d'éditer leurs caractéristiques par l'ajout de mods.
Sur l'écran d'édition, vous pouvez voir la capacité en haut à gauche, indiquant le "poids" des mods que vous pouvez équiper (ex : capacité 10 = 2 mods à 5 de capacité).
   - Tous les objets équipables (frames, arme, compagnon, archwing etc) occupent un emplacement** limité. Vous pouvez en acheter plus, mais cela coûtera des [platinum](farm.md/#plats)
   - La capacité de base augmente avec votre niveau de [maîtrise](mastery-rank.md) de compte, jouer avec un objet donné augmente sa maîtrise et sa capacité aussi
   - On peut augmenter rapidement la capacité d'une frame ou d'une arme en équipant respectivement une aura (ex : [Dreamer's Bond]()) et une posture (ex : [Swooping Falcon](https://wiki.warframe.com/w/Swooping_Falcon) pour Skana)
   - Le coût en crédits et endo pour monter les mods est exponentiel, il dépend de :
     - la "rareté / qualité" du mod, plus elle est haute, plus c'est cher : bronze, argent, doré, primed/galvanisé/archonte
     - le nombre de rangs : le coût est exponentiel. Pour un mod rang 10, éviter d'investir le max directement pour équilibrer l'investissement et le retour en stats quand on a peu de ressources (ex : avoir 3 mods rang 7 est mieux qu'un seul mod rang 10)


## Loadouts

La première ligne en haut à gauche de l'arsenal correspond aux présets/loadouts : vous pouvez enregistrer un setup correspondant à un équipement donné (une frame, 3 armes, un pet avec des mods spécifiques).
Vous pourrez faire différents loadouts, par exemple :
  - un pour Volt orienté arme de mêlée et vite finir les missions
  - un autre pour Volt orienté nuke en faisant plein de dégâts avec le 4ème sort
  - un autre avec Rhino pour tanker sur les missions plus difficiles
  - etc...

## Mods

Les mods vous rendent plus fort.
Fusionner (monter de rang) vos mods rend vos mods encore plus efficaces : il vaut mieux 2 mods montés qui prennent 15 de capacité et beaucoup de stats que 6 mods qui en occupent autant en ne donnant quasi rien.
Il vous faudra de l'endo et des crédits pour monter vos mods, voir [Farm](farm.md) pour plus d'infos.

Plus les mods sont "brillants" (bronze > silver > gold > primed/galvanisé/archonte) plus cela coûtera cher à monter.

En parallèle le coût d'upgrade est aussi exponentiel (plus on avance de rangs, plus le coût d'upgrade par rang est cher) : il vaudra mieux dans un premier temps éviter les rangs maximum et monter plusieurs mods à un rang intermédiaire pour atteindre un bon compromis. Ex : Monter 3 mods au rang 7/10 au lieu d'un seul à 10/10.

Les emplacements de mods peuvent être polarisés : ils ont un signe de mod spécifique ("V" "D" "-" par ex) indiquant qu'ils sont spécialisés pour une polarité/famille de mods :
  - mettre un mod de la même polarité que le l'emplacement divisera par 2 le coût en capacité (vert)
  - mettre un mod ne correspondant pas à la polarité augmentera le coût en capacité (rouge)

### Mods : Warframe

2 utilités principales :
- les stats de base : surtout la survivabilité
- les pouvoirs, capacités :
  - améliorés : boost de puissance pour de meilleurs buffs /nuke, meilleure portée, etc...
  - modifiés : [mods augment]() qui changeront le comportement de certaines capacité. Ex : le mod []() pour Frost lui permet de bien mieux tanker.


Pensez à survoler avec votre curseur les différente stats à gauche, cela vous donnera un détail sur leur impact réel.
Pensez aussi à survoler les icones de passif et de compétences en dessous des stats pour voir l'impact de vos mods sur ces dernières.

#### Mods Warframe : stats de base

- Vie / Armure : combo de base, augmenter la vie augmente votre survie et l'armure réduit les dégat subits par les points de vie
- Boucliers : barre de "tanking" supplémentaire. 50% de réduction de dégats innés, se recharge automatiquement après un certain temps. Lorsque les boucliers arrivent à 0, vous donne une période d'invulnérabilité appelée "shield-gating"
- Energie : le carburant de toutes vos capacités. Monter le pool maximum vous donnera plus de comfort.
- Vitesse de course : pas grand chose à dire, vous vous déplacerez rapidement via les [manoeuvres]() comme la roulade et le bullet-jump qui bénéficient d'une autre stat : la vélocité.

#### Mods Warframe : pouvoirs

- Durée : pour les contrôles (plus longs) et les buffs (longue durée = moins d'énergie dépensée et du comfort)
- Efficacité : réduit le coût des compétences, gros comfort de jeu
- Portée : utile surtout aux contrôles ou nuke de zone (AoE), peu utile si vous vous focalisez sur les buffs de dégâts d'arme
- Puissance : en général pour taper plus fort, parfois pour augmenter des buffs et soins

### Mods Armes : généralités
Ces stats sont communes à toutes les armes et synergisent entre elles, investir dedans dans l'ordre indiqué : 

**"dégats de base x dégats élementaires x crit chance x crit damage"**

Pensez à passer le curseur sur les différentes stats à gauche pour comprendre leurs détail, spécialement les stats avec une icone qui correspondent aux statuts infligés.

- **dégâts de base** : augmente tous les dégâts de l'arme (Dentelure, Nuée de dards, Points de Pression), stat qui sera multipliée par plein d'autres mods. Obligatoire.

- <details><summary><b>dégâts élémentaires</b> (cliquer)</summary>
  
   - multiplient les dégâts de base
   - mettre deux statuts ensemble les fusionnent pour donner un statut combiné
   - le jeu lit les cases de mods de gauche à droite et de haut en bas comme un livre : arranger les mods dans cet ordre pour avoir les combinaisons voulues
      - exemple 1 : l'ordre "toxine + électricité + feu" donnera "**corrosif (tox + elec) + feu**"
      - exemple 2 : l'ordre "feu + toxine + électricité" donnera "**gas (feu + tox) + électricité**"
   - les ennemis ont [différentes résistances](https://wiki.warframe.com/w/Damage#Overview_Table) positives / négatives au dégats, ex :
     - le [corrosif](https://wiki.warframe.com/w/Damage/Corrosive_Damage) (toxine + électricité) inflige +50% de dmg sur les grineers
     - la [toxine](https://wiki.warframe.com/w/Damage/Toxin_Damage) ignore les boucliers et attaque directement la vie. Très efficace sur les corpus qui ont peu de vie et plein de boucliers.
   - donnent accès à des éléments ayant parfois des effets importants pour les dégats :
      - [viral](https://wiki.warframe.com/w/Damage/Viral_Damage) (toxine + froid) : augmente de 100 à 325% les dégats sur les points de vie (10 stacks max par cible pour effet max)
      - [magnetique](https://wiki.warframe.com/w/Damage/Magnetic_Damage) (froid + électricité) : augmente de 100 à 325% les dégats sur les boucliers et l'overguard (eximus, thrax), 10 stacks
      - [corrosif](https://wiki.warframe.com/w/Damage/Corrosive_Damage) (toxine + électricité) : réduit l'armure ennemie de 26 à 80% à 10 stacks. Possibilité plus tard d'augmenter les stacks via [archon shards](https://wiki.warframe.com/w/Archon_Shard)
      - [feu](https://wiki.warframe.com/w/Damage/Heat_Damage) : inflige des dégats sur le temps par stack + réduit l'armure de 15 à 50% (effet max après 5s de brûlure). Pas de maximum de stacks, augmente tant qu'on en applique
  
- <details><summary><b>chances de critique</b> (cliquer)</summary>

   - augmente les chances de [coup critique](https://wiki.warframe.com/w/Critical_Hit) multipliant dégats de base et élémentaires
   - peut dépasser les 100% pour des gros crits (orange) voire super crits (rouge+). On parle de "tiers" de crits.
   - les mods augmentent les stats de crit de base de l'arme. Une arme avec peu de crit (moins de 20% environ) bénéficie peu des mods de crit
  
- **dégats critiques** : multiplicateur appliqué aux critiques pour qu'ils soient encore plus massifs

</details></details>
  
Parfois les armes ont beaucoup de chances de statut et/ou peu de critiques, on peut alors se focaliser sur une autre stat :
- **chances de statut** :
  - augmente les chances de statut. Peut dépasser les 100% (donne des procs supplémentaires)
  - différents types d'[effets de statuts](https://wiki.warframe.com/w/Status_Effect) :
     - debuff :
       - debuff dégats reçus : viral, magnétique
       - debuff stats (armure, autre) : corrosif, feu, froid, puncture
       - debuff CC (crowd control) : froid, radiation, feu, électricité, impact, blast
     - statut de dégats sur le temps (DoT): feu, électricité, toxine, gas, blast, slash

### Mods Armes : primaires / secondaires

Certaines stats sont exclusives aux armes primaires/secondaires :
- [multishot](https://wiki.warframe.com/w/Multishot) : augmente le nombre de balles tirées par coup. Multiplie toutes les autres stats de dégats
  - Primaires : [Split Chamber](https://wiki.warframe.com/w/Split_Chamber)
  - Secondaires : [Barrel Diffusion](https://wiki.warframe.com/w/Barrel_Diffusion) + [Lethal Torrent](https://wiki.warframe.com/w/Lethal_Torrent)
- firerate : cadence de tir, permet d'augmenter le DPS au prix d'une moins bonne économie de munitions



### Mods Armes : mêlée
On retrouve la logique de base "dégats de base x dégats élementaires x crit chance x crit damage".
Quelques spécificités :
- mods scaling par combo : [Weeping Wounds]("dégats de base x dégats élementaires x crit chance x crit damage"), [Blood Rush](https://wiki.warframe.com/w/Blood_Rush), le [set Gladiator](https://wiki.warframe.com/w/Gladiator_Set) (surtout [Gladiator Might](https://wiki.warframe.com/w/Gladiator_Might))
- posture : 
  - rajoute de la capacité comme les auras de warframes
  - permet de varier les attaques et combos ainsi que les dégats infligés par combos (certaines postures sont plus agréables à jouer et/ou tapent plus fort, par exemple [Sovereign Outcast](https://wiki.warframe.com/w/Sovereign_Outcast) qui domine les tonfas)
- [vitesse d'attaque](https://wiki.warframe.com/w/Attack_Speed) : [Fury](https://wiki.warframe.com/w/Fury), [Quickening](https://wiki.warframe.com/w/Quickening) & [Berserker Fury](https://wiki.warframe.com/w/Berserker_Fury) sont abordables
- portée/range : ([Primed](https://wiki.warframe.com/w/Primed_Reach)) [Reach](https://wiki.warframe.com/w/Reach), permet de toucher les ennemis de plus loin / plus d'ennemis à la fois

### Mods Armes : glaives
Les [glaives](https://wiki.warframe.com/w/Category:Glaive) sont des armes de mêlée très particulières.
On les lance avec une attaque longue et on peut les faire exploser à distance avec un coup lourd/secondaire.

Dès le rang de maîtrise 4 vous pouvez obtenir un Xoris qui est un excellent glaive.

Les mods qu'on utilise dessus sont assez particuliers :
- gain de combo via [Corrupt Charge](https://wiki.warframe.com/w/Corrupt_Charge) pour augmenter les dégâts de l'explosion
- mods spécifiques pour l'explosion :
   - [Volatile Quick Return](https://wiki.warframe.com/w/Volatile_Quick_Return) pour avoir une seule explosion à grande portée (très commun)
   - [Volatile Rebound](https://wiki.warframe.com/w/Volatile_Rebound) pour avoir une explosion à chaque rebond (surtout pour le glaive Falcor)
   - mods qui n'influencent pas l'explosion : portée, vitesse d'attaque
