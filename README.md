# custom-spotify
Ce dépot correspond à un test technique dont l'objectif est de créer une application web permettant de rechercher des albums sur Spotify.

J'ai pu y consacrer environ 15h. N'ayant pour l'instant que peu d'expérience en Java et Springboot j'ai passé beaucoup de temps à me documenter et à apprendre. 

J'ai choisi de déposer le front et le back sur deux répertoires différents afin de simplifier le développement et le déploiement.

Le front est développé en Vue.js -> https://github.com/NPoirie/custom-spotify-front.git

Le back est développé en Java SpringBoot -> https://github.com/NPoirie/custom-spotify-back.git

 
## Amélioration possible
- Je n'ai pas eu le temps de fournir une documentation suffisante pour que le projet soit facilement utilisable (il manque notamment les commentaires pour Javadoc).
- Les tests sont pour l'instant manquant. Je comptais utiliser cypress pour le front et Junit pour le back.
- J'ai rencontré un problème avec le CORS (Cross-Origin Resource Sharing). J'ai pu le corriger en utilisant l'annotation @CrossOrigin, mais je ne suis pas sûr que ce soit la meilleure façon de le corriger, notamment si il y a déploiement en production. A investiger...
- Compléter le cahier des charges
