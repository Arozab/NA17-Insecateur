index.php
>à include sur chaque fichier après la balise </head>
>affiche le menu et le le titre "Pokemon GO" en haut de la page

achatShop.php
>recoit les informations du formulaire de AffichageAlentours
>envoi de la requete � la BDD, message avec le solde restant

affichageAlentours.php
>permet d'afficher les trois tables Pokemons,Pokestops et Shops des alentours
>permet de selectionner ce qu'on veut faire dans chaque table

ajouterJoueur.php

capturePokemonResultat.php
>li� au formulaire de AffichageAlentours
>permet de tenter la capture du pokemon
>enregistre le pokemon captur� dans la BDD

connexionBDD.php
>automatise le pgconnect, la connexion � la BDD
>inclut l'enregistrement de la position GPS

controlerTriche.php
>compare les infos du joueur avec le r�glement (nb de pokestops visit�s,nb de pokemons captur�s)

deconnexionBDD.php
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

function.sql
>fonctions SQL de la BDD

index.php
>page d'accueil du site

accessJoueur.php
>Acc��s des joueurs

inscription.php
>sert �� l'inscription des joueurs

inscription2.php
>sert �� l'inscription des joueurs

capturePokemonFormulaire.php
>est appel� par affichageAlentours
>� fusionner peut etre

visitePokestopFormulaire.php
>est appel� par affichageAlentours
>� fusionner peut etre

rechargerCompte.php
>appel� via index.php

visitePokestopResultat.php
>appel� via affichageAlentours.php
>permet de prendre les objets d'un pokestop

administration.php
>permet de cr�er des pok�mons, des ar�nes, shops, de modifier les pok�mons et de visualiser le profil de chaque utilisateur
>(sera sous divis� en diff�rentes pages php, deviendra surement une page .html)
