# Reverse Proxy with HTTPS

##Devilbox 


Imaginez que vous ayez démarré une application dans le conteneur PHP qui crée un port d'écoute (ex : NodeJS). Ce port n'écoutera que sur le conteneur PHP et vous devrez ajuster la définition de docker-compose.yml afin d'avoir ce port disponible en dehors de votre système d'exploitation hôte.

Alternativement, il y a un moyen simple de faire un reverse proxy vers le serveur web déjà en place et même d'utiliser la fonctionnalité HTTPS disponible.