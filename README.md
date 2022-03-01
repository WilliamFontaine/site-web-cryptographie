# site-web-cryptographie

## Introduction
Le code source du site n'est pas public, cependant, bous pouvez le retrouver à l'adresse suivante : https://sancy.iut-clermont.uca.fr/~lafourcade/site-web-cryptographie/src/Enigma/.  


Le site consiste en un site ludique abordant le thème de la cryptographie. Il permet d'aborder différents thèmes de la cryptographie, en reprenant certaines énigmes du livre "25 énigmes ludiques pour s'initier à la cryptographie" de Monsieur Pascal Lafourcade.  

Le site a été réalisé dans le contexte d'un projet tutoré de 2ème année de DUT informatique (UCA). Nous étions une équipe de 5 étudiants et notre tuteur était Monsieur Pascal Lafourcade. Je me suis également vu confier le rôle de chef de projet pour ce dernier.

## Précisions sur le site
Un système de login est intégré au site pour pouvoir sauvegarder la progression et les points d'un joueur dans la réalisation des différentes énigmes.  

Le site est composé de plusieurs énigmes de cryptographie, chacune de ces énigmes possède un niveau de difficulté, représenté par les étoiles. Pour chacune de ces énigmes, on dispose de 3 niveaux de résolution. Chacune des énigmes dispose aussi de 3 indices, modifiables à tout moment par un administrateur.  

Pour pouvoir débloquer des points, vous devez donner des points en échange, on en gagne en résolvant des énigmes. Le nombre de points varie en foction du niveau de difficulté d'une énigme et de son niveau de résolution.  

Un classement est aussi disponible. Il répertorie pour toutes les énigmes et chacun de leurs niveaux, les meilleurs temps des utilisateurs.  

Un système du groupe est aussi disponible sur le site, si vous avez les droits suffisants, vous pouvez créer des groupes. Vous pouvez cependant rejoindre des groupes quel que soit votre rôle. Les groupes vous permettent de visualiser un classement des membres de ce groupe uniquement. Ces groupes sont particulièrement utiles en classe.  

Les utilisateurs, indices, groupes sont tous stockés en base de données (Sqlite).
