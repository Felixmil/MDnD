#📍Lieu

```leaflet
id: grotte-aux-echos-de-la-mer
height: 1000px
image: ../../../../../assets/Pasted%20image%2020230208165202.jpg
```
# Général

## Rencontres aléatoires: 

`dice: [](Grotte%20aux%20Echos%20de%20la%20Mer.md#^ecounter)`

| dice:1d20 | Result                                                                    |
| --------- | ------------------------------------------------------------------------- |
| 1–16      | No Encounter                                                              |
| 17-20     | `dice: [](Grotte%20aux%20echos%20de%20la%20mer.md#^wandering-monsters)` |
^ecounter

| dice: 1d12 | Result                      |
| ---------- | --------------------------- |
| 1–3        | `encounter: 2d4: stirge`    |
| 4–5        | `encounter: 1d4: ghoul`     |
| 6          | `encounter: 1d4: gricks`    |
| 7-8        | `encounter: 1d4: bugbear`   |
| 9          | `encounter: 1d6: skeleton`  |
| 10         | `encounter: 1d6: zombie`    |
| 11-12      | `encounter: 1: ochre jelly` |
^wandering-monsters



## Echos

Partie 1 : Alors que vous traversez Wave Echo Cave, vous commencez à entendre un son qui ne ressemble à rien de ce que vous avez entendu auparavant. Le martèlement rythmique se répercute dans la caverne, devenant plus fort et plus intense à chaque pas. La source du bruit semble venir du nord-est, et vous ne pouvez vous empêcher de penser que quelque chose de vraiment extraordinaire vous attend.

Partie 2 : Le rugissement de l'inconnu s'amplifie, remplissant l'air d'un sentiment de puissance et de mystère. Vous commencez à vous demander ce qui peut bien être à l'origine de ce son impressionnant. Votre cœur s'emballe alors que vous vous approchez de la source du bruit, vous préparant à ce que vous pourriez trouver.

Partie 3 : Vous atteignez finalement la source du son, et vos yeux s'élargissent d'étonnement. Devant vous se trouve un lac souterrain, dont les vagues s'écrasent sur le rivage avec la puissance d'une tempête. Le spectacle est à couper le souffle, et vous ne pouvez qu'être impressionné par la puissance et la beauté de la nature. Le martèlement rythmique des vagues emplit l'air, créant une symphonie de sons qui vous laisse un sentiment d'humilité et d'inspiration. Malgré le relâchement de la tension, le mystère de la grotte de l'écho des vagues reste entier, vous laissant désireux de découvrir davantage de ses secrets.

# Sections

## 1 - Entrée de la Grotte

> [!QUOTE] Description
> Le tunnel d'entrée mène à une grande caverne soutenue par un pilier naturel de roche et contenant trois stalagmites. Dans la partie ouest de la caverne, derrière la colonne de roche, se trouvent trois sacs de couchage et un tas de fournitures ordinaires - sacs de farine, sacs de sel, tonneaux de viande salée, lanternes, flacons d'huile à lampe, pioches, pelles et autres équipements.
> 
> La section nord-est de la caverne s'est effondrée, formant une fosse de dix pieds de large et de vingt pieds de profondeur. Une solide corde de chanvre est attachée à une stalagmite voisine et pend sur le côté du puits, au fond duquel se trouve un tunnel grossièrement taillé qui se dirige vers le nord-ouest et l'est.

>[!DANGER] Gouffre #🎲Epreuve/⚡Environnement 
> - Profond de 6m
> - Test de Force (Athletisme) DC 14.
>	- Si échoué de 5: chute de 3m (`dice: 1d6` dgts)
>	- Si échoué de 10 +: chute de 6m (`dice: 2d6` dgts)


>[!SUCCESS] Bottes de Rebond #✨Objet 
>**Investigation DD 14** Dans le campement abandonné, on peu trouver un paire de [Bottes de Rebond](https://www.dndbeyond.com/magic-items/4590-boots-of-striding-and-springing) au fond d'un duvet.


## 2 - Tunnels

> [!QUOTE] Description
> Cette zone est constituée de nombreux passages qui se croisent. Les plafonds n'ont que 2m de haut et plusieurs passages se terminent par des parois rocheuses partiellement excavées.

>[!DANGER] Gelée Ochre #🎲Epreuve/⚔️Combat  
>```encounter
>creatures:
>  - 1: Ochre Jelly
>```


## 3 - Ancienne Entrée

> [!QUOTE] Description
> De nombreux tunnels se croisent dans cette caverne naturelle de trente pieds de haut. Les murs sont sculptés de simples reliefs représentant des mineurs nains et gnomes au travail. En dessous d'eux, près de deux douzaines de squelettes portant des débris d'armures rouillées sont éparpillés sur le sol de la caverne. Certains sont des squelettes de nains, d'autres des restes d'orcs. Une demi-douzaine de grandes lanternes en cuivre se trouvent dans des niches ou sur des rebords autour de la caverne, mais aucune n'est allumée.

>[!WARNING] Stirges Cachées
>**Perception DD 16**: Surprise des PJ


>[!DANGER] Stirges #🎲Epreuve/⚔️Combat  
>```encounter
>creatures:
>  - 10: Stirge
>```





## 4 - Salle des Gardes

> [!QUOTE] Description
>  Des bancs de pierre éclatés et des tas de gravats provenant d'un plafond partiellement effondré remplissent cette pièce. Les ossements de plusieurs nains et orcs se trouvent parmi les lits de pierre en ruine et les supports d'armes renversés.


>[!DANGER] Squelettes #🎲Epreuve   
>```encounter
>creatures:
>  - 9: Skeleton
>```

## 5 - Bureau des intendant de la mine

> [!QUOTE] Description
> Cette pièce était autrefois un bureau ou un entrepôt. Un grand comptoir en pierre divise la pièce en deux, avec trois balances poussiéreuses en fer. Des renfoncements creusés dans le mur nord sont remplis de bouts de papier poussiéreux. Plusieurs cadavres morts depuis longtemps -gnomes et orcs d'après leur apparence- sont étalés sur le sol.

>[!SUCCESS] Trésor 
> Derrière le comptoir se trouve un coffre-fort en fer verrouillé, nécessitant des outils de voleur et un test de Dextérité DC 20 réussi pour l'ouvrir. Ce coffre a été oublié pendant le combat et contient 600 cp, 180 sp, 90 ep, et 60 gp.

## 6 - Baraquements Suds

> [!WARNING] Ecouter à la porte #🎲Epreuve/⚡Environnement 
> Tout personnage qui écoute à la porte partiellement ouverte entend de faibles bruits de craquement et d'éclatement en réussissant un test de Sagesse (Perception) DC 10.

> [!QUOTE] Description
> De vieilles couchettes en pierre disposées en rangs ordonnés bordent les murs de cette chambre, et un brasero en fer corrodé rempli de vieux charbons se trouve près du milieu de la pièce. Les os d'une demi-douzaine de nains et d'orcs sont éparpillés, vêtus de débris d'armure. Trois silhouettes grises et voûtées sont accroupies parmi les restes, tripotant les restes et rongeant les os.

>[!DANGER] Ghoules #🎲Epreuve/⚔️Combat  
> ```encounter
> creatures:
>   - 3: Ghoul
> ```
### 

## 7 - Entrepôt en ruine

> [!QUOTE] Description
> Le mur est de cette chambre s'est effondré en un amas de gravats. Au nord, une porte est entrouverte et mène à une réserve de bonne taille. Des fûts poussiéreux sont soigneusement rangés contre les murs, tous fendus et ouverts par l'âge.

>[!TIP] Possibilité de repos
>Ce n'est pas confortable, mais la réserve est un lieu de repos sûr. Aucun monstre ne passe par ici. De plus, la porte de la réserve est en bon état et peut facilement être bloquée ou barrée de l'intérieur.


## 8 - Caverne aux Champignons

> [!QUOTE] Description
> Des tapis denses de champignons étranges couvrent de grandes sections du sol de cette caverne. On y trouve des boules d'un pied de diamètre, d'étranges champignons d'étagère poussant sur les stalagmites, ainsi que de grandes tiges et des chapeaux d'un bon mètre cinquante de haut. Certaines de ces boules brillent d'une étrange phosphorescence verte.


>[!DANGER] Gaz Empoisonné #🎲Epreuve/⚡Environnement   
> Chaque fois qu'une créature tente de traverser la caverne, les tapis de champignons qui recouvrent la majeure partie du sol libèrent un gaz toxique dans l'air. Chaque créature dans la caverne doit réussir un jet de sauvegarde de **Constitution DC 11** ou subir** 3d6 dégâts de poison** et être [Empoisonné [Poisoned]](../../../Règles/Etats.md#Empoisonné%20[Poisoned]) pendant 10 minutes. Le gaz se disperse après 1 minute, mais d'ici là, toute créature vivante qui termine son tour dans la caverne doit répéter le jet de sauvegarde.

## 9 - Grande Caverne

> [!QUOTE] Description
> Des escarpements abrupts divisent cette grande caverne en trois sections - des corniches élevées à chaque extrémité, et une section plus basse au milieu. Des escaliers en pierre sculptée montent jusqu'aux corniches. Deux grandes tables se trouvent dans la section centrale, ainsi qu'une paire de vieux braseros. Une table plus petite se trouve sur le rebord oriental. Les restes squelettiques de dizaines de guerriers morts - nains, gnomes, orcs et ogres - témoignent de la férocité des combats qui ont eu lieu ici il y a longtemps.


>[!DANGER] Goules #🎲Epreuve/⚔️Combat   
> ```encounter
> creatures:
>   - 7: Ghoul
> ```

>[!WARNING] Restanques
> Les escarpements font 3 mètres de haut et il faut réussir un test de **Force (athlétisme) DC 12** pour les escalader. Une créature qui tombe ou est renversée du haut d'une corniche subit **1d6 points de dégâts** de contendants et tombe à plat ventre.

## 10 - Le Bassin sombre

> [!QUOTE] Description
> A still pool fills much of this cavern. The water is dark, revealing little of what might lie within. The shore of the pool consists of a thin layer of broken shells from strange, pale mussels, and a fishy odor hangs in the air.
> 
> A passage leads south from this area, and a set of steps climbs up to the east. A sluggish stream flows out of the cave to the northeast.

> [!HINT] Passage vers [18 - La Caverne Effondrée](#18%20-%20La%20Caverne%20Effondrée)  
> Le bassin est profond de 20 pieds au milieu. Le ruisseau au nord-est est profond de 3 pieds, et le plafond du passage est à 2 ou 3 pieds au-dessus de l'eau. Les personnages peuvent facilement traverser le ruisseau jusqu'à la zone 18.

>[!SUCCESS] Trésor #✨Objet 
Un personnage qui explore le bassin trouve un vieux squelette couché au fond, à trois mètres du rivage et sous trois mètres d'eau. Il s'agit des restes d'un sorcier humain de l'ancienne Phandalin qui est mort en défendant les mines contre les attaquants orcs. Plusieurs flèches orques sont encore logées dans la cage thoracique du squelette.
Le squelette porte deux anneaux de platine (75 gp chacun) et serre une [baguette de missiles magiques](https://www.dndbeyond.com/magic-items/4794-wand-of-magic-missiles) dans ses doigts osseux.


## 11 - Baraquements Nords

>[!WARNING] Porte Est barricadée #🎲Epreuve/⚡Environnement 
>La porte Est est barricadée de l'intérieur de la pièce et nécessite un test de **Force DC 20** réussi pour la forcer. Un personnage qui écoute à l'une ou l'autre des portes et qui réussit un test de **Sagesse (Perception) DC 10** entend des voix bourrues parlant le gobelin et disant à quel point ils ont faim.

> [!QUOTE] Description
> De vieilles couchettes en pierre bordent les murs de cette caserne, qui est éclairée et chauffée par un brasero en fer rougeoyant au milieu de la pièce.
> 
> Si personnages arrivent du couloir: De l'autre côté de la pièce se trouve une autre porte, celle-ci étant bloquée par une barricade faite des restes d'une table en bois.

>[!DANGER] Gobelours #🎲Epreuve 
> ```encounter
> creatures:
>   - 5: Bugbear
> ```
> 

>[!SUCCESS] Trésor #✨Objet 
> Le plus grand bugbear porte une pochette contenant 15 cp. 13ep, et une [potion de vitalité](https://www.dndbeyond.com/magic-items/5360-potion-of-vitality).

## 12 - La Fonderie


> [!QUOTE] Description
> Un haut fourneau et un soufflet mécanique actionné par une roue à eau dominent cette grande salle. Le fourneau est froid et sombre, mais des tas de charbon sont empilés à proximité, ainsi que des chariots remplis de minerai non raffiné. La roue à eau se trouve dans un canal de trois mètres de large creusé dans le sol de la pièce, mais le canal est sec. Des passages sortent à l'ouest, au sud et à l'est. Le canal vide sort au nord et à l'est.
> 
> Plus d'une douzaine de cadavres desséchés sont éparpillés dans la pièce. Ces nains et orcs tués portent encore les restes de leur armure. Au-dessus d'eux flotte un crâne englouti dans des flammes vertes.


>[!DANGER] Zombies & Flameskull #🎲Epreuve 
>```encounter
>creatures:
>  - 8: Zombie
>  - 1: Flameskull
>```
> 


### Passage vers [18 - La Caverne Effondrée](#18%20-%20La%20Caverne%20Effondrée)
Le fond du canal est à 1,5 m sous le niveau du sol, et aucun test d'aptitude n'est nécessaire pour y entrer ou en sortir. Les personnages dans le canal peuvent le suivre hors de cette pièce au nord ou à l'est, bien que le plafond ne soit plus qu'à 1,5 m de hauteur après la sortie du canal de cette pièce.

## 13 - Caverne Etoilée


> [!QUOTE] Description
> Les minéraux scintillants au plafond de cette grande caverne captent la lumière et la renvoient pour créer l'impression d'un ciel nocturne étoilé. Des dizaines de squelettes, dont beaucoup sont écrasés sous des débris, sont éparpillés sur le sol.
> 
> La grotte est suffisamment grande pour contenir deux structures autoportantes. Chacun de ces bâtiments en pierre est proportionné pour un usage humain, contrairement aux portes et aux meubles de taille naine que vous avez vus ailleurs dans les mines. Les deux structures ont des murs de maçonnerie abîmés et noircis, leurs doubles portes sont fissurées et brûlées. La caverne est divisée par un escarpement, dans lequel une volée d'escaliers a été taillée.
> 
> Des passages mènent de cette zone vers le nord, le sud et l'ouest.

### Les cristaux #🔎Découverte 
Les bâtiments endommagés sont décrits dans les zones 14 et 15. Les minéraux dans le plafond sont jolis, mais ils ne sont ni magiques ni précieux.

Tout personnage **compétent en Arcane** peut sentir une subtile aura de magie dans cette caverne. (Un sort de détection de la magie révèle la même chose.) L'aura devient plus forte à mesure que l'on s'approche du bâtiment nord (zone 15).

## 14 - Quartiers des Magiciens

### Porte verouillée #🎲Epreuve 
Les portes menant à cette zone sont fissurées, leurs charnières en fer ayant partiellement fondu. Pour ouvrir les portes, il faut réussir un test de Force DC 15.

> [!QUOTE] Description
> La poussière, la cendre, les murs noircis par le feu et les amas de débris sous le plafond affaissé montrent que cette pièce a été endommagée par une explosion destructrice. Le mobilier - tables, chaises, étagères, lits - est carbonisé ou éclaté, mais bien conservé. Un coffre en fer brûlé se trouve près du pied de l'un des lits.

### Mormesk le spectre #🎲Epreuve 
- Sort du sol lorsque les PJ entrent dans la pièce
> [!QUOTE] Mormesk
> Un spectre d'humain mais en décomposition, portant une longue robe déchirée et un baton.
> "Votre présence est une offense, votre vie est compromise. Mes trésors sont à moi seul, n'imaginez meme pas pouvoir me piller !"
- Plusieurs réactions:
	- Si les PJ ne réagissent pas: il attaque.
	- Si les PJ parlent, il écoute ce qu'ils ont à dire et leur suggèrent une offrande. Il accepte les objets magiques et en particulier les parchemin avec test de Charisme (Persuasion) DC 10 pour convaincre le spectre de sa valeur.
	- Si les PJ volent ses biens: il attaque

>[!SUCCESS] Trésor #✨Objet 
> Le coffre brûlé est déverrouillé et contient 1 100 cp, 160 sp, 50 ep, trois diamants (100 gp chacun) et une pipe en bois ornée de filigrane de platine (150 gp).
> Une poignée de tomes magiquement préservés restent sur les étagères. La plupart ne sont que des histoires, mais l'un d'entre eux comporte une carte cousue dans sa couverture. La présence de la carte peut être discernée en réussissant un test d'Intelligence (Investigation) DC 12. La carte indique l'emplacement d'un donjon de votre création. Lorsque les personnages auront terminé leurs explorations ici, cette vieille carte pourra les mener à leur prochaine aventure.

## 15 - La Forge aux Sortilèges

C'est ici que les sorciers alliés aux nains et aux gnomes du Pacte de Phandelver ont canalisé la magie de ces cavernes pour enchanter les armes des nains et les gadgets des gnomes.

>[!WARNING] Porte Est barricadée #🎲Epreuve/⚡Environnement 
> La porte la plus au nord est brûlée et fissurée, ses gonds en fer partiellement fondus ; la forcer à s'ouvrir nécessite un test de Force DC 15 réussi. Les doubles portes de l'ouest sont tout aussi endommagées mais restent légèrement entrouvertes.

> [!QUOTE] Description 
> Ce grand atelier a été gravement endommagé par l'ancienne bataille de sortilèges qui a ravagé la mine. Les tables de travail qui occupent deux coins de la pièce sont roussies, et le plâtre a été brûlé sur les murs en maçonnerie. Au milieu de la pièce, un piédestal de pierre supporte un petit brasero dans lequel danse et crépite une flamme d'un vert inquiétant. Le brasero et son socle semblent avoir été épargnés par les forces qui ont détruit cette région.
> Derrière le brasero de flammes vertes flotte une créature sphérique mesurant environ un mètre cinquante de diamètre. Quatre yeux sortent de sa masse centrale, deux de chaque côté. Au centre du corps se trouve un grand œil qui vous fixe. "Bonjour", dit une voix épaisse et bouillonnante à l'intérieur de votre tête.


>[!DANGER] Spectateur #🎲Epreuve 
> ```encounter
> creatures:
>   - 1: Spectator
> ```
> Si le groupe tente de retirer quoi que ce soit de cette zone, le spectateur attaque. 
> 
> Si le spectateur est aveuglé d'une manière ou d'une autre, il disparaît dans son plan d'origine, convaincu qu'il ne peut plus accomplir la tâche pour laquelle il a été convoqué.
> 
> En réussissant un test de Charisme (Tromperie) DC 15, le personnage peut faire croire au spectateur qu'un ou plusieurs membres du groupe sont des sorciers ou des mineurs travaillant pour les propriétaires de la Grotte de l'Écho des Vagues, envoyés pour mettre fin à l'emploi du spectateur. Si la tromperie réussit, le spectateur croit être libéré de ses obligations, et il disparaît pour retourner dans son plan d'origine.

>[!TIP] Brasero de flammes vertes #🔎Découverte 
>Un test d'Intelligence (Arcanes) DC 15 réussi permet d'identifier le brasero comme la source de la magie qui imprègne les cavernes environnantes. Cette magie s'est affaiblie au fil des ans, au point qu'elle ne peut plus être exploitée pour enchanter des objets magiques de façon permanente. Cependant, toute arme ou armure non magique baignant dans la flamme verte pendant au moins 1 minute devient une arme +1 ou une armure +1, respectivement, pendant 1d12 heures. Le brasero ne peut être retiré de la Forge des sorts.

>[!TIP] Salle du Nord
>Cette petite pièce est un espace de travail séparé, où les objets préparés pour l'enchantement étaient polis, laqués et finis. Comme l'atelier principal, elle a été presque entièrement détruite.

>[!SUCCESS] Trésor #✨Objet 
> Sur la table de travail dans le coin sud-est de la pièce se trouvent les derniers objets que le spectateur a été chargé de protéger : [Porteuse de Lumière](https://5e.tools/items.html#lightbringer_lmop) et [Garde Dragon](https://5e.tools/items.html#dragonguard_lmop).

## 16 - La Caverne aux Echos

C'est à cette caverne remplie d'eau que l'on doit le bruit du ressac qui a donné son nom à la grotte de l'Écho des vagues.
Le rebord qui épouse le mur sud se trouve à 15 pieds au-dessus du niveau de l'eau. Cependant, lorsque l'eau pénètre dans la grotte toutes les deux minutes, elle fait monter le niveau de l'eau de 3 m. Après une minute, le niveau de l'eau redescend. Au bout d'une minute, le niveau de l'eau revient à sa profondeur normale de 10 mètres.

> [!QUOTE] Description 
> Une étroite corniche surplombe une grande caverne qui abrite une masse d'eau bouillonnante. Le grondement rythmique que l'on entend dans toutes les mines est plus fort ici. À intervalles réguliers, une nouvelle vague d'eau s'engouffre dans cette chambre et se heurte au mur juste en dessous de la corniche. L'écho suggère que cette grotte pourrait être un bras d'une caverne beaucoup plus grande au nord-est.

## 17 - Ancien lit de ruisseau

Le ruisseau qui s'écoulait de la zone 10 à la zone 18 traversait ce passage bas pour se déverser dans la zone 16.

> [!QUOTE] Description 
> Ce passage mesure à peine un mètre de haut et est obstrué par des blocs arrondis et des cailloux. Il aurait pu être le lit d'un ruisseau, mais l'eau n'y coule plus.

Les nains ont détourné le cours d'eau dans le canal menant à la zone 12 pour faire tourner la roue à aubes de la fonderie. Puis les tremblements de terre qui ont secoué la grotte de l'Écho des vagues lors de la dernière bataille de sorts de l'invasion orque ont fait s'effondrer le sol de la zone 18, détournant une fois de plus le cours d'eau. L'ancien lit du ruisseau reste un passage utilisable pour contourner les morts-vivants de la zone 12, bien que Nezznar ne l'ait pas encore découvert.

## 18 - La Caverne Effondrée

Les serviteurs de Nezznar occupent cette caverne, veillant sur les incursions de morts-vivants et fouillant soigneusement les décombres. Les divinations de l'Araignée noire suggèrent qu'un précieux trésor est caché au fond de la faille créée lors de la destruction de cette zone.

> [!QUOTE] Description 
> Une large faille remplit la moitié est de cette caverne. Un ruisseau s'écoule de la paroi ouest, puis dégringole dans la faille avant de ressortir au nord. Plusieurs cordes sont attachées à des piquets de fer le long du bord ouest de la faille, menant au fond du gouffre.

>[!DANGER] Gobelours #🎲Epreuve 
>```encounter
>creatures:
>  - 3: Bugbear
>```
>  Deux d'entre eux déblayent la roche au fond de la brèche, tandis qu'un autre monte la garde dans la moitié ouest de la caverne. Un double nommé Vhalak supervise les opérations sous l'apparence d'un drow. Si un combat éclate dans la caverne principale, les deux bugbears de la faille grimpent le long des cordes pour se joindre à la mêlée.

## 19 - Le Temple de Dumathoin

## 20 - Les Quartiers des Prêtres
