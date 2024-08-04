
## Règles additionnelles

N/A

## Mots clés

- **Champion :**
  * Si cette unité doit être retirée du combat,
    elle est détruite à la place
- **Charge de X :**
  * Déplacer la ou les unités concernées pour les placer à gauche ou à droite de la rangée du haut.
  * Une unité ne peut pas charger si elle est déjà en première ligne,
    ou si elle a effectué un repli ce tour-ci.
- **Détruire une carte :**
  * Placer la carte en question dans la pile ou le Monde
    d'où elle peut être achetée
- **Discernement :**
  * Si un effet révèle cette carte, vous pouvez choisir de la
    défausser ou de la placer sous votre pioche. Si vous le
    faîtes, révélez une autre carte à la place
- **En première/dernière ligne :**
  * Une unité est en première ligne si elle est sur la rangée
    du haut, et en dernière ligne si elle est sur la rangée du bas
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
- **Renouvelable :**
  * Si cette carte est dans votre main, vous pouvez
    choisir de la défausser à tout moment pour piocher
    une carte
- **Repli de X :**
  * Déplacer la ou les unités concernées depuis la rangée du haut pour les placer sur une nouvelle rangée,
    en-dessous de l'actuelle rangée du bas.
  * Une unité ne peut pas se replier si elle est déjà en dernière ligne, ou si elle a effectué une charge ce tour-ci.
- **Révéler des cartes :**
  * Montrer à tous les joueurs des cartes du dessus
    de votre pioche, puis les replacer sur celle-ci
    dans le même ordre


## Unités

### Grunt
- **Coût :** 1
- **Valeur :** 1
- **Permanent :** Force +2 si en première ligne


### Chevaucheur de Loup
- **Coût :** 2
- **Valeur :** 1
- **Permanent :** Force +1 si en première ligne
- **Réaction (Événement : cette unité charge ou est retirée du combat) :** Neutraliser


### Chef de Clan
- **Coût :** 3
- **Valeur :** 2
- **Permanent :** Force +1 si en première ligne
- **Immédiat :** Épurer pour Repli d'une unité au choix


### Meneur
- **Coût :** 3
- **Valeur :** 2
- **Permanent :** Force +1 si en première ligne
- **Immédiat :** Repli d'une unité au choix
- **Réaction (Événement : il charge) :** Charge d'une unité au choix
- **Immédiat :** Charge de cette unité ou de la prochaine unité que vous jouez


### Rameuteur
- **Coût :** 3
- **Valeur :** 2
- **Permanent :** Force +1 si en première ligne
- **Réaction (Événement : se replie ou est retiré du combat) :** Piocher une carte
- **Immédiat :** S'il y a un Rameuteur sur la rangée au-dessus : piocher une carte puis Charge de tous les Rameuteurs


### Tête Brûlée
- **Coût :** 3
- **Valeur :** 2
- **Permanent :** Force +2 si en première ligne
- **Immédiat :** Charge de cette unité et de tous les Grunts


### Grosse Brute
- **Coût :** 5
- **Valeur :** 5
- **Permanent :** Champion
- **Permanent :** Force +4 si en première ligne


### Chef de Guerre
- **Coût :** 6
- **Valeur :** 3
- **Permanent :** Force +1 si en première ligne
- **Immédiat :** Repli d'une unité au choix
- **Immédiat :** Placer à droite de cette unité [une unité au choix OU tous les Meneurs], puis Charge des unités de cette rangée


## Exemple

- Roger joue un Rameuteur
- Il joue un Chevaucheur de Loup
- Il joue un Meneur
  * Il active sa deuxième capacité immédiate pour charger
  * Il active sa capacité de réaction pour faire charger le Chevaucheur de Loup
    (toutes les unités sont donc en première ligne)
  * Il active la capacité de réaction du Chevaucheur de Loup pour neutraliser
    une unité de son adversaire (de force 3)
  * Il active la première capacité immédiate du Meneur pour faire se replier le Rameuteur
  * Il active la capacité de réaction du Rameuteur et pioche une carte
- Il joue un deuxième Meneur
  * Il active sa deuxième capacité immédiate pour charger
  * Il active sa capacité de réaction pour faire charger le Rameuteur
  * Il active sa première capacité immédiate pour faire se replier le Chevaucheur de Loup
- Il joue une Grosse Brute
- Il joue un Chef de Guerre
  * Il active sa deuxième capacité immédiate pour placer les deux Meneurs
    à droite du Chef de Guerre puis charger avec ceux-ci
  * Il active la capacité de réaction du premier Meneur pour faire charger la Grosse Brute
  * Il active la capacité de réaction du second Meneur pour faire charger le Chevaucheur de Loup
  * Il active la capacité de réaction du Chevaucheur de Loup pour neutraliser
    le champion de son adversaire (de force 10)
  * Il active la première capacité immédiate du Chef de Guerre pour faire se replier le Rameuteur
  * Il active la capacité de réaction du Rameuteur et pioche une carte
- Il joue un Rameuteur
  * Il active sa capacité immédiate pour piocher une carte et charger avec l'autre Rameuteur
- Il joue un Chevaucheur de Loup
- Il arrête d'ajouter des unités
- La force totale de son armée est de 31, et il a pu enlever 13
  de force à celle de son adversaire
