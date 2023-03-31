# journal-lepays
Création de site wordpress du journal local "Le Pays" ( avec thème personnalisé sous Gutemberg)

## Installation 
- Installer XAMP sur votre disque c:/
- Éxécuter XAMP et véfifier dans les icones réduites en bas de la barre des tâches que les voyants "Apache" et "Mysql" sont bien au vert si c 'est pas le cas cliquer sur "start" afin de les activer.
- Aller dans `C:\xampp\htdocs` et ouvrez un terminal de commande (en mode admin) et tapez la commande ` git clone https://github.com/yohann-devweb3/journal-lepays` afin de récupérer le dossier ressource du projet.
- Se rendre sur PhpMyAdmin via `http://localhost/phpmyadmin/index.php` puis cliquer sur "Nouvelle base de données" et entrer le nom `lepays` comme nom de base de données puis terminer en cliquant sur le bouton "créer".
- Toujours dans PHPMyAdmin, aller dans l'onglet "importer" > "choisir un fichier" > sélectionner le fichier 'lepays-deploy.sql'(qui est dans le repo) puis terminer avec le bouton 'importer' tout en bas".(soit à l'url suivant :`http://localhost/phpmyadmin/index.php?route=/server/import`)

- Pour terminer, ouvrez un navigateur web et visiter l'url : `http://localhost/lepays/` . Enjoy~*

### Identifiants
  ##### Wordpress (compte admin) :
    id : admin
    mdp : lepays2023!!!*
    
### Plugins installés et actifs : 
  - WPS Hide Login =>
      - url de connexion pour le panneau d'administration : `http:localhost/lepays/login`
  - Yoast SEO =>
      - url du tableau de bord : `http://localhost/lepays/wp-admin/admin.php?page=wpseo_dashboard`
### Site déployé

Actuellement le site est déployé sur infinityfree : `http://lepays.epizy.com/lepays/`
#### Pour récupérer via FTP :
- Télécharger et installer filezilla ftp client
  Connectez-vous avec ces paramètres :
      - id : epiz_33910724
      - mot de passe : SNhNejQJxS1Gln
      - serveur ftp : ftpupload.net
      - port : 21
 puis déplacer le dossier "lepays" depuis la zone "site distant" vers votre ordinateur : `C:\xampp\htdocs`

### Repo

Le repo contient aussi les maquettes en JPEG ainsi que le script sql pour charger la base de données.
