# README

## Description du Projet

Devoir à la maison sur un hébergement en ligne de page statique  
Dépot sur https://github.com/teddyfresnes/LPW_2023/tree/main/NOLLET/DM%20Service%20Public  
Site sur [dmbootstrap-teddyk.netlify.app  ](https://dmbootstrap-teddyk.netlify.app/)


## Structure du Code

Le code de ce projet est organisé de la manière suivante :  

- Une page web html  
- Un répertoire contenant les images locales /img  
- Un fichier CSS style.css  
- Un fichier CSS bootstrap 5  
- Un fichier CSS récuperé du TP colonne bootstrap  


## Layout

La mise en page de ce projet est gérée comme suit :  
On garde la structure HTML actuelle et on modifie le visuel de haut en bas la page avec CSS  
Disposition par défaut en block, quand nécessaire en flex  
Layout essentiellement gérer par bootstrap  


## Utilisation de Bootstrap

#### Utilisation bootstrap pour la navbar

- Classe bootstrap essentiel pour faire la navbar  
`navbar-expand-lg` : pour étendre la barre de navigation lorsque l'écran est large  
`nav-item` : élément de nav qui s'aligne dans la navbar  
`mx-auto` : centrer (appliquer sur chaque colonne)  
`dropdown` : pour faire un menu déroulant  
`dropdown-menu` : menu contenant les éléments déroulants  
`dropdown-item` : élément déroulant d'un menu  
- Chaque élément de menu pour posséder des attributs personnalisables tel que  
`data-bs-toggle="dropdown"` : active le menu déroulant au survol ou au clic  
`aria-haspopup="true"` : indique qu'il y a un sous-menu  
`aria-expanded="false"` : initiallement, le menu déroulant est fermé  
- Pour personnaliser les menus (bordures, fond) j'ai ajouté des sections pour supprimé les marges entre les nav-item  

#### Utilisation bootstrap pour le reste de la page

- Récupération code TP colonne et modification  
- Footer en bootstrap en row/colonne  


## Auteur

KOEHREN Teddy  
