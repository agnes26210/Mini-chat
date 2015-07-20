# Mini-chat
TP Openclassrooms - Développement d'un mini-chat

Le mini-chat se veut très simple. Dans ce TP j'utilise PDO pour me connecter à une base de donnée MySQL.

Grâce à PDO, le code est utilisable avec d'autres bases de données.

Pour mettre en forme le formulaire et la liste des messages, j'utilise bootstrap minifié (maxcdn en version 3.3.5).

Les requêtes SQL sont des requêtes préparées.
J'utilise diférentes méthodes pour préparés les requêtes.

##Résumé du TP :
Utilisation de :
- SELECT
- INSERT
- Requêtes préparées
- Transmission de données par formulaire et $_POST

##Ajout de fonctions supplémentaires :
- Mise en place d'un cookie pour retenir le pseudo du rédacteur
- Rafraîchir la liste des messages
- Développer une pagination - prendre en compte la mise en forme avec bootstrap - gestion dynamique avec PHP 

##Attention
Je sais que l'on ne doit pas mettre en ligne de fichier config. Mais dans ce cas précis, l'exercice est uniquement développé en local.
Aucune donnée sensible ne transite dans ce fichier. Dans le cas d'un développement avec des données sensibles, j'utilise .gitignore.
