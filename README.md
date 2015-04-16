#Dico Québécois style Wiki

###Objectifs
- Votre objectif est de recréer de toutes pièces le site www.wikebec.org, et de l'améliorer.
- Vous avez 4.5 jours
- Vous travaillez en binômes. 
- Vous ne pouvez réutiliser aucun code provenant de wikebec.org (il est pitoyable de toutes façons).
- Les consignes suivantes sont volontairement imprécises : vous devrez réfléchir. 

###Technologies
Voici les solutions techniques retenues.

- Framework serveur : Symfony2
- ORM : Doctrine
- SGBD : MySql
- Moteur de template : Twig
- Framework CSS : Bootstrap recommandé
- Framework JS : libres
- Gestion de version : git

###Données
Un fichier OpenDocument vous a été fourni: il contient les données du dico (les termes, leurs définitions, etc.). 

Les données ne sont pas intègres : faites un maximum pour les améliorer. 

Vous noterez que plusieurs données ont été supprimées par rapport au site original, c'est normal, et vous n'aurez pas à les ajouter plus tard. 

###Fonctionnalités à implémenter
Voici la règle directrice : toutes les fonctionnalités présentes sur wikebec.org doivent être implémentées par vos soins, ET vous pouvez améliorer tout ce qui ne vous semble pas optimal. 

####Fonctionnalités à retirer
- Google Adsense
- Partage sur les réseaux sociaux

####Nouvelles fonctionnalités
- Ajouter un captcha sur tous les formulaires (ajout, modification, suppression des termes), et faites le maximum pour limiter les dégats que pourraient réaliser un robot.
- Demander l'adresse email de l'utilisateur dans tous ces formulaires, et la garder en mémoire pour simplifier le remplissage des formulaires suivants. 
- Envoyer un email à l'administrateur du site à chaque modification au dictionnaire, et incluez-y beaucoup de détails.
- Conserver l'historique détaillé de chaque modification au dictionnaire (backup).

####Notes sur les fonctionnalités
- Il n'est pas nécessaire de réaliser de requêtes AJAX (comme les formulaires sur wikebec.org), mais c'est tout de même recommandé pour le bouton de "vote"
- Notez que le dictionnaire (la liste des termes) est présent sur toutes les pages. 
- Le "mot du jour" doit changer à chaque 24h, et doit être un mot de qualité.
- Le maximum doit être fait pour empêcher un même utilisateur de voter plusieurs fois pour le même terme.
- Le référencement naturel est très important pour ce site. 
- Google Analytics partout SVP.
- Dans le cas où vous auriez terminé avant la fin des jours octroyés, vous pouvez réaliser un back-office, permettant par exemple de consulter l'historique des modifications, et de restaurer un terme à une version précédente.   

###Design
- Vous êtes libre, mais essayez de purifier/simplifier le design actuel, pour qu'on y voit quelque chose !
- N'utilisez aucune des images présentes sur le site actuel, ce look est dépassé.
- La disposition des éléments devrait toutefois rester sensiblement la même. 

###Évaluation
Vous serez évalués sur 3 critères : 
- Implication/motivation/recherche de la perfection (/8, individuel)
- Qualité du code/bonnes pratiques (/8, équipe)
- Quantité de travail réalisé (/4, équipe)

Vous aurez environ 25 minutes pour me présenter votre code. 

####Précision importante
La quantité de travail fourni n'est donc pas un facteur marquant dans l'évaluation. Prenez votre temps pour réaliser un code SF2 dans les règles de l'art, que vous serez fiers de présenter, en utilisant à fond ce qu'il vous offre : services, migrations, fixtures, commandes de console, tests fonctionnels, validations, héritage twig, etc. ! Ce n'est pas un problème de ne pas avoir terminé le site. 

