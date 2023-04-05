#session
# Session 02 - 15-04-2021

## Strong start

> C'est sous le ciel orange du soleil couchant que vous arrivez au Puy du Vieux Hibou. Hamound Korst vous acceuille, heureux de vous voir revenir à lui. Après lui avoir partagé les information precieuse que vous avez obtenus, il vous offre le gite et le couvert, assisté de ses dociles squelettes qui font office, en plus de garde personnel, de major d'homme, de serveur et meme de cuisiniers. Après le diner, le mage vous explique que le Druide que vous cherchez se nomme Reidoth, il était venu fouiner il y a une dizaire de jours  pour s'assurer que le mage n'entreprenait pas d'actions nefase. Il lui avait alors parlé de sa prochaine destination: Foudrechêne. Puis Hamound pris le temps de vous schématiser l'emplacement de ce village, abandoné depuis de nombreuses années d'après ces dires, en vous donnant les instructions basiques pour vous y rendre. Il vous explique que vous avez 2 possibilitées: soit, suivre la piste des trois sangliers ou bien "couper" par la fôret de padhiver.

### Voyage

2 chemins possibles depuis ConnyBerry:

- par la route (en repassant proche de Phandalin)
- par la foret de Padhiver


#### Distances parcourues

echelle: 1 hex = 5 miles
vitesse de base: 30 ft



| Durée   | distance      |
| ------- | ------------- |
| 1 heure | 2,5 miles (0,5 hex) |
| 1 watch | 10 miles (2 hex)   |
| 1 march | 25 miles (5 hex)    |

#TODO la distance de base parcourue en une journée est trop courte (25 miles = 8 km). Il faudrait la passer à 15 km (10 hex), c'est aussi plus facile à diviser par 2 ou par 3 en fonction des différents rythmes.



#### Rythmes

effets décrit pour 1 watch

| rythme              | effet                                                           |
| ------------------- | --------------------------------------------------------------- |
| Normal              | /                                                               |
| Rapide              | 1 heures gagnées  (+1 hex) mais Navigation DC +4                |
| Discrètement        | Danger: 1/2, Navigation DC -4 mais distance: 3/4                |
| Exploration         | Discovery: x2  mais Danger: x2 et distance: 1/2                 |
| Chasse et Cueillète | Test de Ressources, nouris le groupe pour 1j mais distance: 1/2 |


#### Hex stats


| Terrain | Danger | Navigation | Ressources | Discovery |
| ------- | ------ | ---------- | ---------- | --------- |
| Plains  | 1      | 10         | 10         | 1         |
| Forest  | 2      | 14         | 12         | 2         |

#TODO Le systeme de "etre perdu" n'est pas très interessant à utiliser avec une carte qui se revele petit à petit. Il faut tester un mecanisme ou l'echec du jet de navigation REDUIT la distance parcouru (represente le fait que les PJ tournent en rond, ou doivent retourner sur leurs pas.)

#TODO Ajouter un modificateur de distance à chaque terrain. Si les personnages se perdent, ce modificateur est appliqué plusieurs fois.

#### Mecanisme

On repete ces étapes pour chaque watch (4 heures)

Au début de chaque watch:
  - Les joeurs choisissent un rythme
  - Test de navigation vs terrain:
    - si echec: lancer 1d10
        - 1, 2, 3, 4: deviation à gauche
        - 5, 6: en face
        - 7, 8, 9, 10: deviation à droite
    - si réussite, le groupe se rapproche de l'objectif


Durant chaque watch
    - faire un jet de danger avec 1d6. si la valeur obtenue est en dessous de celle dans le tableau: rencontra aléatoire
    - faire un jet de Discovery: si en dessous, un element particulier apparait dans le decors

à la fin du watch:
    - Deplacer le marqueur du groupe
    - Faire un test de navigation pour savoir si perdu ou non (sauf si localisation evidente)

## Scenes

* [x] Hamun Kost donne un **ring of protection** pour avoir nettoyé le Rocher aux Wyverns

* [x] Petit Dejeuner macabre:
    Les squelettes de Hamound reveillent les joueurs et leur servent un petit dejeuner copieux tandis que le mage dort toujours. 

* [x] Arrivée a Foudrechene: 
    > Peu à peu, le sentier se transforme en vieille route pavée qui serpente entre des bâtiments délabrés, envahis par les vignes et les broussailles. Devant vous, au milieu du village, s’élève une colline escarpée sur laquelle se dresse une tour en pierre au toit partiellement effondré et un chalet attenant. Un chemin de terre longe la base de la colline et se faufile entre de vieilles maisons en pierre, dont beaucoup sont des ruines sans toit dont les intérieurs sont completement ouverts aux intempéries. D’autres bâtiments semblent plus ou moins intacts. L’ensemble de l’endroit est sinistrement silencieux.
    > 
    > Un panneau en bois est cloué sur un poteau à proximité. On peut y lire : « DANGER ! Monstres végétaux ET zombies ! Faites demi-tour maintenant ! »

* [ ] description d’un fléau de brindilles:
    > Un buisson marron, gris sec d’environ 40 cm de haut, semblant mort se met a vibrer. Le sol s’ouvre tandis que les racines de ce buisson s’en extirpe et s’entortillent en grandissant. 
    Les brindilles s’entre-melent toujours avec les racines ainsi que les cones de pin et lesfeuilles mortes qui se trouvaient là lorsque vous commencez a deviner une silhouette humanoïde: une tete, deux bras, et surtout deux jambes qui s’élancent vers vous. Vous en etes desormais certains, c’est un fleau de brindilles !

- [ ] Reidoth demande une faveur:
    Si les personnages interrogent Reidoth sur la grotte de l'Écho des vagues, il ne divulguera pas son emplacement mais proposera au groupe de l'y guider en échange d'une faveur : il veut qu'ils chassent le dragon de la zone 7. S'ils réussissent, Reidoth honorera sa part de l'accord mais n'accompagnera pas le groupe à l'intérieur de la mine.

## Secret and clues

* [x] Le vieux druide se trouve à FoudreChêne
* [ ]  Autrefois, c'était une communauté prospère à la périphérie de la forêt, riche du travail de ses bûcherons et trappeurs. Puis, il y a trente ans, l'éruption du Mont Hotenow, au nord, a dévasté Thundertree.
* [ ] The druid Reidoth (see area 4) visits Thundertree from time to time, keeping a wary eye on its dangers.
* [ ] Cultists have also arrived recently (see area 13) to treat with a dragon that claims Thundertree as its domain (see area 7).
* [ ]  La statue adossée mesure trois mètres de haut, socle compris. Elle représente un ancien héros de Neverwinter nommé Palien, qui aurait vaincu plusieurs monstres dans le bois de Neverwinter lors de la fondation de Thundertree. Un personnage qui étudie la statue reconnaît la représentation en réussissant un test d'Intelligence (Histoire) DC 15. 