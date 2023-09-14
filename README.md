# oh-My-food-E.G
Site de réservation dans des restaurants.

Ce site est construit en HTML et en SASS, et le sass est ensuite convertie en CSS.

Architecture du code : 
- Les fichiers HTML : (index.html, delice.html, francaise.html, note.html et palette.html)

    Ce sont les différentes pages du site, soit la page d'accueil et les pages qui affichent les menus des différents restaurants.

- Un dossier "CSS" : Avec les fichiers css compiler à partir de SASS (cependant le code n'est pas minifié).

- Un dossier "images" : Avec les différentes images présentes sur le site.

- Un dossier SASS avec :
    - Un fichier "main.scss" qui contient tous les imports des différents fichiers qui composent le code SASS.
      
    - Un dossier "base" avec un fichier qui contient les règles générales pour tout le site.
      
    - Un dossier "components" qui contient différents fichiers qui sont de petits éléments qui peuvent être réutilisés sur le site.
      
    - Un dossier "layout" qui contient de plus gros composants du site et le code pour princiipale pour le style des pages de restauration.
      Il est accompagné d'un dossier média-queries qui contient les fichiers associer aux différents éléments dans layout pour le responsiv design.
      
    - Un dossier "page" qui contient le code pour la page d'accueil.
      
    - Un dossier "utils" avec des fichiers contenant des variables, les mixins et les maps SASS ainsi qu'un fichier avec les différentes keyframes pour les animations graphiques.
      
    - Un dossier "vendors" avec un fichier qui contient le code pour normaliser le comportement des éléments sur tous les navigateurs.


