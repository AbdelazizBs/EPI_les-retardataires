# EPI_les-retardataires
Automatisation et création d'unee stack à partir des outils et des concepts utilisés par les DevOps


1. [Plan](#plan)

## Plan
***

* install Vagrant,Virual Box VM, Jenkins in local machine.
* vérifier l'addresse ip dans le vagrant file ( il faute ètre plus que le ip de votre addresse locale ipv4 de réseaux sans fil.
* Exécutez la commande « vagrant up » avec la configurration « Vagrantfile » qui existe.
* tapez la commande « vagrant ssh » pour connecter.
* lancez l'outil jenkins avec la commande « sudo systemctl start jenkins.service ».
* verifiez avec la commande « sudo systemctl status jenkins.service ».
* ouvrez l'interface jenkins avec l ip de vagrant file et le port 8080.
* configurez la pipeline avec le script dans le fichier existant jenkinsfile.
