# Changelog

Important : en cas de mise à jour disponible pour laquelle il n'y a pas d'information dans cette section, c'est qu'elle n'intègre aucune nouveauté majeure. Cela peut être un ajout de documentation, une correction de documentation, des traductions ou bien de la correction de bugs mineurs.

## 15 janvier 2022##

- Correction du layout v4
- Rétablissement du fonctionnement des horaires de marées.
3 nouvelles commandes sont créées. Marée précédente, Marée suivante et Tableau des marées. Elles nécessitent que l'équipement soit resauvegardé pour être créées. Une compatibilité partielle avec les numéros de port de maree.info a été préservée. Les numéros de port sont dans une liste déroulante. Certains ports pour lesquels je n'ai pas trouvé de correspondance exacte ne sont plus sélectionnables. Voir le fichier core/config/PortsMareeInfo.json pour la correspondance. Les champs latitude et longitude sont nécessaires. Merci de communiquer vos corrections éventuelles.

## 29 mai 2020

Changement des noms des templates utilisateur de xxxx_user.html en custom.xxxx.html 
La mise à jour du plugin sur une version de Jeedom à partir de la 4.0.56 nécessite la copie des fichiers xxxx_user.html en custom.xxxx.html

## Février 2020

Ajout des alertes de GDACS

## Janvier 2020

Possibilité d'utiliser la configuration géographique de Jeedom directement (nécessite le core en 4.0.36 minimum)

Suppression du type Seisme comme l'API n'est plus disponible

## 30 Juin 2018

Correction météo des plages

## 15 Mai 2018

Ajout d'une commande refresh

## Mars 2018

Refonte de la doc
