achatShop.php
>recoit les informations du formulaire de AffichageAlentours
>envoi de la requete � la BDD, message avec le solde restant

affichageAlentours.php
>permet d'afficher les trois tables Pokemons,Pokestops et Shops des alentours
>permet de selectionner ce qu'on veut faire dans chaque table

ajouterJoueur.php

capturePokemon.php
>li� au formulaire de AffichageAlentours
>permet de tenter la capture du pokemon
>enregistre le pokemon captur� dans la BDD

connexion.php
>automatise le pgconnect, la connexion � la BDD
>inclut l'enregistrement de la position GPS

controlerTriche.php
>compare les infos du joueur avec le r�glement (nb de pokestops visit�s,nb de pokemons captur�s)

deconnexion.php
>deconnecte de la base de donn�e
>ferme la session

enregistrementGPS.php
>inclut dans connexion.php
>permet d'enregistrer la position a chaque connexion
>envoie un formulaire

enregistrerGPS.php
>recoit les infos de enregistrementGPS et les enregistre dans la BDD
>eventuellement � fusionner avec enregistrementGPS

environnementTest.sql
>permet de cr�er une s�rie de INSERT pour tester la BDD avec des valeurs titi toto

identifiants.php
>stocke les identifiants de la BDD
>dans l'id�al il faudrait stocker les identifiants dans la BDD (s�curit�)

impl�mentationSQL.sql
>code de cr�ation de la BDD

index.html
>page d'accueil du site

inscription.php

inscription2.php

pokemonEstProche.php
>est appel� par affichageAlentours
>� fusionner peut etre

pokestopEstProche.php
>est appel� par affichageAlentours
>� fusionner peut etre

rechargerCompte.php
>appel� via index.html

recupererObjets.php
>appel� via affichageAlentours.php
>permet de prendre les objets d'un pokestop