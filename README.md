## Mon portfolio est composé de 5 catégories :
- Accueil.html
- Contact.html
- Experiences.html
- Projets.html
- Veille.html

## Langages utilisés
- HTML


Prochaine barre de navigation head en css :

html,
body {
  background-color: rgb(196, 194, 194) !important;
} /* Obligatoire pour mon navigateur, sinon il ne prend met pas de fond */





/* Style général du menu */
.menu {
  list-style-type: none;
  background-color: #333;
  margin: 0;
  padding: 0;
  display: flex;
}

.menu li {
  position: relative;
}

.menu a {
  display: block;
  color: white;
  padding: 15px 20px;
  text-decoration: none;
}

.menu a:hover {
  background-color: #111;
}

/* Masquer le sous-menu par défaut */
.sous-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #333;
  list-style-type: none;
  min-width: 150px;
  padding: 0;
  box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.2);
}

.sous-menu li {
  width: 100%;
}

/* Afficher le sous-menu au survol */
.deroulant:hover .sous-menu {
  display: block;
}
