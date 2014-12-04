Whargal.github.io
=================



PROCEDURE
=========


I/ Installer l'environnement de developpement sur xubuntu
---------------------------------------------------------

lancer serveur apache : sudo service apache2 start

relancer serveur apache : sudo service apache2 restart


Installer version normal ruby : sudo apt-get install ruby

Installer version développeur ruby : sudo apt-get install ruby ruby-dev make

Installer Git : udo apt-get install git

Installer jekyll : sudo gem install jekyll –no-rdoc –no-ri

Installer nodejs : sudo apt-get install nodejs

verifier version d'un élément : nom -v (ex : jekyll -v)

Creer un dossier site dans le repertoire xubuntu : mkdir site


II/ Github
----------

Aller sur le site www.github.com et créer un compte

Une fois connecter cliquer sur le "plus" puis sur "new respository"

nom : username.github.io

choisir public

cocher "initialize this respository with a README"


Aller dans le repertoire site: cd site

cloner github : git clone https://github.com/username/username.github.io

Aller dans le repertoir github : cd username.github.io

créer un fichier index.html : echo "Hello World" > index.html

configurer e-mail : git config --global user.email "you@example.com"

configurer nom : git config –global user.name "Your name"

ajouter fichier : git add –all

enregistrer dans le depot les modification : git commit -m "Initial commit"

envoyer les fichier modifié : git push



