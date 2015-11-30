# AppTwitter
Web Project - LP SIL IDSE

-

### Installer NodeJS (npm)
+ Allez sur <https://nodejs.org/en/> pour télécharger et installer NodeJS

### Installer Ionic Framework
+ Executez la commande suivante : `sudo npm install -g cordova ionic`
+ Pour voir la doc : <http://ionicframework.com/docs/>

### Installer Bower
+ Executez la commande suivante : `sudo npm install -g bower`
+ Pour voir la doc : <http://bower.io>

### Installer Gulp
+ Executez la commande suivante : `sudo npm install -g gulp`
+ Pour voir la doc : <http://gulpjs.com>

-

### Préparation du projet

Tout d'abord, clonez le projet:
+ Dans le dossier de votre choix : `git clone https://github.com/Wainbot/AppTwitter.git`

Puis, installez les outils :
+ Entrez en ligne de commande à la racine du projet AppTwitter/
+ Executez la commande : `npm install`


Ensuite, toujours à la racine du projet, installez les librairies :
+ Executez la commande : `bower install`


Une fois terminé, il faut lancer le serveur pour voir le projet.
Dans un premier temps, on pourra utiliser le serveur par defaut de Ionic Framework.
+ Il suffit d'executer la commande suivante : `ionic serve`

### Pr�paration de la base de donn�es

apt-get install postgres
apt-get install php5-pgsql //pdo adapter

Apr�s mettez vous en root :
su postgres
psql //racine postgres 
psql twitter //direct dans la base une fois cr�er

Maintenant vous �tes dans la console de postgres :
ouvrez le ficher postgres.sql et faites des copier-coller �tape par �tape.

Commande utile :
/q quitter
/d description de tout les tables ou \d nom_table description une table
/l � la racine de postgres pour lister les BDD

PS : Pour voir l'aperçu avec IOS et Android executez avec -l : `ionic serve -l`

