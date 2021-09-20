# Bateam_test
test de développement

#Projet version Symfony 5.3.7 et php 7.3
# cloner le projet git clone git@github.com:zapo1234/Bateam_test.git
# installer les dependances en tapant  cd Batem et ensuite  avec composer install
# important : composant serializer de symfony  pour la version de symfony 5 veuillez cloner le dossier via le package
via github package serialize version git clone https://github.com/symfony/serializer.git voir lien https://github.com/symfony/serializer

# copier le dossier serializer dans le vendor de votre projet absolument
# entrer composer update.
# activer la synchronisation du serveur avec la base de données pour faire demarer normalement symfony php bin/console doctrine:database:create.
NB: just pour bien faire le serveur on utilise pas de base données ni doctrine pour ce projet.

# entrer symfony serve pour faire demarer ton server en localhost sur le port http://127.0.0.1:8000/movies

# aller sur la route du projet http://127.0.0.1:8000/movies 

# dans le dossier Src/Controller vous avez 2 controller qui traite les fonctionalités(afficher toutes la liste de tableau ) et les fonctions Ajax retour
# dans le dossier Src/Entity un modèle Movies.php 
# dans le dossier public Js vous avez des scripts javascript/jquery Ajax développés.
# le controller Action qui travaille sur les fonctionnalités et boutons 


NB : au click des boutons de statistique de pop up et recherche select par pays , pour quitter le pop up cliquer sur l'ecran noir partout  pour supprimer la pop up et continuer
Front utiliser (Jquery/javascript/ajax) et le twig de symfony.
Back Symfony 5.3.7 et Php 7.3.
