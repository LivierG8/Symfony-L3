## Barème de notation du TP - LOT 2

Le projet est rendre sous forme d'un **dossier compressé** (`NOM_PRENOM.zip` ou `NOM_PRENOM.rar` ou `NOM_PRENOM.7zip`, etc), et à m'envoyer par message privé sur Teams. 

Les dossiers/fichiers du projet à inclure dans le dossier compressé à rendre sont les suivants : 
* `assets`
* `config`
* `public`  (**Sans le dossier uploads à l'intérieur**)
* `src`
* `templates`
* `.env.local`
* `composer.json`
* `package.json`
* `webpack.config.js`

**ATTENTION ! N'incluez pas les dossiers `node_modules` et `vendor` dans le dossier compressé !**

**Pensez à vérifier que le dossier compressé contient tout ce qu'il faut - Dézippez le pour être sûr qu'il contient tous les dossiers demandés, et que ces dossiers ne soient pas vides**.

___ 

Vous trouverez ci-dessous les points à remplir pour obtenir un maximum de points :

* Administration des utilisateurs
    - Liste 
    - Formulaire pour modifier un utilisateur
        - Modifier le(s) rôle(s)
        - Bloquer un utilisateur

* Connexion : On ne doit pas pouvoir se connecter avec un compte bloqué

* Inscription
    * Champs obligatoires
        * Nom
        * Prénom
        * Civilité
        * Date de naissance
        * Email
    * Champs facultatifs
        - Téléphone
        - Ville
        - Code Postal
        - Pays
        - Numéro de sécu

* Sécurisation les espaces administration/agent/client selon les rôles

* Espace administration
    - Liste des offres
        + Création / édition / suppression
        + Nombre de souscriptions pour chaque offre

* Espace public
    - Liste des offres
    - Souscrire à une offre - _Conditions à vérifier_ :
        + Être connecté
        + Vérification des informations obligatoires (pour la souscription)
        + Messages flash en cas d'erreur
        + Redirection (vers la page de connexion ou vers l'espace client)
* Édition des articles
    * Pouvoir modifier l'image de chaque article
    
* Espace agent : 
    * Liste des souscriptions
    * Modifier le statut d'une souscription
* Espace client : 
    * Formulaire d'édition des informations
    * Liste des souscriptions

* Bonus : 
    - _Inscription_ : Regex
    - _Administration_ : Afficher l'âge de chaque utilisateur dans la liste
    - Correction des bugs du lot 1
    - _Images des articles_ : Utiliser un service [FileUploader](https://symfony.com/doc/current/controller/upload_file.html#creating-an-uploader-service)
