
## Règles additionnelles

- En fin de combat, vous ne pouvez pas choisir de renvoyer
  des cartes unités dans votre Monde au lieu de les défausser.


## Mots clés

- **Alimenter X :**
  * Détruire X autres unités de votre armée
- **Assembler X :**
  * Ajouter au combat une unité de coût X,
    prise gratuitement dans votre Monde, et la marquer
  * L'unité pourra activer ses capacités normalement,
    mais sera détruite lorsqu'elle sera défaussée ou retirée
    du combat
- **Champion :**
  * Si cette unité doit être retirée du combat,
    elle est détruite à la place
- **Connecter :**
  * Déplacer cette unité pour la placer à gauche ou à droite
    d'une autre unité de votre armée,
    ou déplacer une unité de votre armée pour la placer à gauche
    ou à droite de celle-ci
- **Détruire une carte :**
  * Placer la carte en question dans la pile ou le Monde
    d'où elle peut être achetée
- **Discernement :**
  * Si un effet révèle cette carte, vous pouvez choisir de la
    défausser ou de la placer sous votre pioche. Si vous le
    faîtes, révélez une autre carte à la place
- **Épurer :**
  * Détruire une carte de votre main
- **Force +X :**
  * La force de cette unité dans l'armée du joueur
    est augmentée de X
- **Marquer une unité :**
  * Un effet dépend/dépendra de si cette unité a été ou non
    marquée, et il faut donc garder trace de cette information
    (par exemple en tournant la carte horizontalement
    ou en plaçant un cube dessus)
- **Neutraliser :**
  * Retirer du combat une unité de l'armée de l'adversaire
    (au choix)
- **Produire X :**
  * Ajouter X unités Bloc de Matériaux à droite de cette rangée,
    prises gratuitement dans votre Monde
    (dans la limite de leur disponibilité)
  * Les capacités immédiates des unités ainsi ajoutées
    ne peuvent pas être activées
- **Réassigner :**
  * Renvoyer dans votre Monde les unités de votre choix,
    parmi vos unités retirées du combat et celles actuellement
    dans votre armée (y compris la carte activant cette capacité)
- **Reconfigurer X :**
  * Détruire cette unité, puis la remplacer sur sa rangée
    par une combinaison d'unités de coût total inférieur ou égal
    à X, prises gratuitement dans votre Monde
  * Les capacités immédiates des unités ainsi ajoutées
    ne peuvent pas être activées
  * Si l'unité reconfigurée était marquée, la combinaison
    d'unité l'est également, et les effets correspondants
    s'appliquent à chacune d'entre elles
- **Renouvelable :**
  * Si cette carte est dans votre main, vous pouvez
    choisir de la défausser à tout moment pour piocher
    une carte
- **Révéler des cartes :**
  * Montrer à tous les joueurs des cartes du dessus
    de votre pioche, puis les replacer sur celle-ci
    dans le même ordre
- **Synergie +X :**
  * À l'exception des unités Bloc de Matériaux,
    toute unité se trouvant sur la rangée au-dessus de cette
    carte, se trouvant sur la rangée en-dessous de cette carte,
    ou étant adjacente à cette carte sur la même rangée,
    obtient Force +X


## Unités

### Bloc de Matériaux
- **Coût :** 1
- **Valeur :** 0
- **Immédiat :** Alimenter 1 pour Reconfigurer 2


### Module d'Armement
- **Coût :** 2
- **Valeur :** 2
- **Immédiat :** Alimenter 1 pour Neutraliser
- **Immédiat :** Reconfigurer 2


### Module de Recyclage
- **Coût :** 3
- **Valeur :** 3
- **Immédiat :** Épurer pour Produire 1
- **Immédiat :** Reconfigurer 3


### Module de Production
- **Coût :** 3
- **Valeur :** 3
- **Immédiat :** Produire 8
- **Immédiat :** Reconfigurer 3


### Module de Propulsion
- **Coût :** 3
- **Valeur :** 3
- **Immédiat :** Alimenter 1 pour piocher 1 carte
- **Immédiat :** Reconfigurer 3


### Module d'Optimisation
- **Coût :** 3
- **Valeur :** 3
- **Post-combat :** Réassigner
- **Immédiat :** Reconfigurer 3


### Module de Coordination
- **Coût :** 5
- **Valeur :** 1
- **Permanent :** Champion
- **Permanent :** Synergie +2
- **Immédiat :** Jusqu'à 2 fois: Alimenter 2 pour Connecter


### Module d'Assemblage
- **Coût :** 6
- **Valeur :** 1
- **Immédiat :** [Alimenter 2 pour Assembler 2] OU [Alimenter 3 pour Assembler 3]

## Exemple

- Camille joue un Module de Production
  * Elle active sa première capacité et ajoute 8 Blocs
    de Matériaux à son armée (qui ne peuvent pas activer
    de capacité)
- Elle joue un Module d'Assemblage
  * Elle active sa capacité et détruit 3 Blocs de Matériaux
    pour ajouter à son armée un Module de Propulsion
    (qu'elle tourne horizontalement pour le marquer)
  * Elle active la première capacité du Module de Propulsion,
    et détruit un Bloc de Matériaux pour piocher une carte
- Elle joue un Module de Coordination
  * Elle active sa capacité immédiate et détruit 2 Blocs
    de Matériaux pour le connecter à la droite du Module
    d'Assemblage, ainsi que 2 Blocs de Matériaux pour connecter
    le Module de Propulsion à sa droite
- Elle joue un second Module de Production
  * Elle active sa première capacité et ajoute 8 nouveaux Blocs
    de Matériaux à son armée
  * Elle active sa deuxième capacité pour reconfigurer
    le Module de Production en un Module d'Optimisation
- Elle joue un Module d'Armement
  * Elle active sa capacité et détruit un Bloc de Matériaux
    pour neutraliser le champion de son adversaire (de force 10)
- Elle joue un second Module d'Armement
  * Elle active sa capacité et détruit un Bloc de Matériaux
    pour neutraliser une autre unité de son adversaire
    (de force 3)
- La force totale de son armée est de 23, et elle a pu enlever 13
  de force à celle de son adversaire
- Avant de défausser les unités de son armée,
  Camille active la capacité post-combat de son Module
  d'Optimisation pour détruire les 6 Blocs de Matériaux restant
- Elle défausse ensuite ses unités, sauf le Module de Propulsion
  marqué, qui est détruit
