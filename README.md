# Activités -C1
Vous trouverez ci-dessous des suggestions d'activités pour vous aider à pratiquer :

## Activité 1 - Style guides
1. Comparez et mettez en contraste ces deux différents guides de style HTML :
  - jQuery - https://contribute.jquery.org/style-guide/html/
  - Google - https://google.github.io/styleguide/htmlcssguide.html

1.1. Sont-ils cohérents entre eux ? Y a-t-il des règles qui ne semblent pas avoir de sens ?

1.2. Pouvez-vous trouver d'autres guides de style ou normes de codage qui sont en accord ou en désaccord avec certaines des suggestions contenues dans l'un de ces guides ?

2. Consultez le vérificateur HTML du W3C http://validator.w3.org/ :

2.1. Essayez " Saisie directe " et tapez du code HTML5 avec des erreurs pour voir ce qu'il détecte.

2.2. En utilisant "Validate by URI", essayez certains sites Web populaires et voyez si vous pouvez trouver des erreurs.

## Activité 2 - Attributs

1. Trouver la liste des attributs supportés pour la balise <area>. (Astuce : utiliser la liste de référence des attributs du W3C https://www.w3.org/2009/cheatsheet/ ou du MDN https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)

2. Créez deux paragraphes avec le même identifiant et exécutez votre code dans un CodePen. Que se passe-t-il ? Nous savons que la valeur de l'attribut id doit être unique, alors pourquoi se comporte-t-il comme il le fait ? Exécutez votre code dans le W3C Markup Validator https://validator.w3.org/#validate_by_input. Est-ce qu'il lance une erreur ?

3. Est-ce qu'un attribut appelé src existe ? Quel est le but de cet attribut et quels sont les éléments auxquels il peut être appliqué ? (Conseil : reportez-vous à la spécification HTML5 du W3C, à la feuille de contrôle du W3C ou à la liste de référence des attributs MDN)

4. Créez une liste ordonnée commençant par le chiffre 11. Ensuite, inversez la liste. Donnez-lui le titre suivant (lorsque vous passez votre souris, le titre devrait s'afficher sous forme d'info-bulle) : " Liste d'activités ".

## Activité 3 - Eléments sémantiques
1. Quel est le rapport entre header et h1 ? Quelle est la différence entre eux ?

2. Créez une page HTML bien structurée en utilisant autant d'éléments sémantiques que possible.

3. Écrivez une courte page HTML qui utilise les balises div et span. Vous n'avez pas besoin de les styliser.

4. Article vs section?

## Activité 4 - Eléments images
1. Créez une page Web simple qui parle de votre journée en utilisant uniquement du texte et des images. Incluez au moins trois images et ajoutez les attributs alt et title.
2. Parcourez le Web et vos sites Web préférés et identifiez ceux qui, selon vous, utilisent beaucoup d'images décoratives.
3. Créez une page HTML et ajoutez les types d'images suivants :
- Image informative qui représente des concepts et de l'information
- Image décorative
- Images de texte
4. Utilisez l'attribut alt pour fournir un texte de remplacement pour les images ci-dessus.
5. Reportez-vous au didacticiel sur les images WAI pour obtenir un guide sur la rédaction du texte de remplacement.

## Activités 5 - Hyperliens
1. Tester l'élément d'ancrage en fournissant des liens brisés ou non valides. Comment le navigateur réagit-il ?
2. Créez une page simple " Contactez-moi " et incluez ce qui suit en utilisant des hyperliens lorsque c'est possible :
  - Une courte introduction (pas plus de trois lignes) sur vous-même
  - Informations sur les médias sociaux
  - Courriel
3. Dans la même page, ajoutez la navigation au début pour les parties de votre page comme Introduction, Médias sociaux et Courriel. Utilisez les hyperliens et l'attribut " id " pour créer un lien vers chaque section à partir de la navigation.
4. Créez une page HTML avec un lien qui utilise l'attribut download. Essayez votre code dans Internet Explorer et Google Chrome. Quelle est la différence de comportement que vous voyez ? Pourquoi cela se produit-il ?
5. Pouvez-vous imaginer différents scénarios dans lesquels vous utiliseriez les valeurs cibles '_self' et '_blank' ?

## Activités 6 - Utilise le CSS
Utilisez le CSS sur le code HTML "Activité 6 - Utilise le CSS.html". Essayez différents styles, expérimentez et amusez-vous.

## Activité 7 - Unités
Avec le HTML "Activité 7 - Unités.html", veuillez dimensionner le texte en utilisant des unités différentes :

1. Utilisez les unités px pour définir la taille de la racine du texte pour le document.
2. Utilisez les unités rem pour la taille des balises h1 et li.
3. Modifiez la taille du texte de la racine de la règle CSS. Vous devez observer que tout le texte du document s'ajuste de façon appropriée.
4. Modifiez la balise h1 pour qu'elle utilise les unités px. Lorsque la règle CSS racine est modifiée, la balise h1 ne s'ajuste plus avec le reste du document.

## Activité 8 - listes
Le HTML qui suit est pour une simple liste.  Insérez-la dans un fichier HTML correctement formé et mettez-la en forme.  Essayez de vous assurer que ce qui suit est fait :

1. Espacer les éléments de la liste d'au moins 20 pixels du bord gauche de la page
2. Espacer les éléments de la liste d'au moins 10 pixels l'un de l'autre
3. Centrer l'en-tête
4. Garder la liste à au moins 50 pixels de l'en-tête
5. Les titres des livres de la liste ne doivent pas être affichés dans une police à empattement
6. L'en-tête doit utiliser une police différente de celle de la liste
7. Le texte de l'en-tête doit être rouge foncé.
8. Diviser les règles CSS en deux fichiers .css différents. Un fichier doit contenir toutes les règles d'espacement, l'autre toutes les règles régissant les polices ou les couleurs.  
9. Reliez les deux dans votre document HTML.
10. Au lieu de numéros, faire indexer les éléments de la liste par l'alphabet.
11. Changer la balise ol en ul et donner un style aux éléments de la liste pour qu'ils aient des puces carrées.
12. Utiliser la forme triange dans le repo (my_triangle) et stylisez les éléments de la liste pour qu'ils affichenet les triangle au lieu des puces carrées.

## Activité 9 - sélecteurs CSS
En utilisant le HTML "Activité 9 - sélecteurs CSS.html" , veuillez styliser les deux listes en suivant ces instructions :

1. Les caractères féminins sont en bleu, et les caractères masculins sont en rouge
2. Dorothea Brooke et Sydney Carton sont en gras
3. Joshua Rigg et Madame Defarge sont en italique
4. La liste pour Middlemarch est énumérée avec des chiffres romains
5. La liste pour A Tale of Two Cities est énumérée avec des caractères alpha
6. Les éléments de la liste pour Middlemarch sont plus espacés
7. La liste pour Middlemarch a été déplacée vers la droite
8. La police Serif n'est utilisée nulle part sur la page

Pouvez-vous obtenir le même style sans ajouter de nouvelles balises (c'est-à-dire sans ajouter i ou b ou span) ? N'hésitez pas à modifier le HTML, mais essayez de ne pas ajouter de nouveaux attributs id, si possible.

## Activité 10 - Débogueur
1. En utilisant votre navigateur préféré, naviguez vers Wikipedia.org. En utilisant les outils de développement, changez le titre et l'en-tête de la page en "Mon Wikipedia" et changez le fond en vert clair.
  -Astuce : utilisez " Inspecter " ou " Inspecter l'élément ".
2. Dans une autre fenêtre de navigateur, ouvrez Wikipedia.org. Est-ce qu'il ressemble à celui que vous avez modifié ? Pourquoi ou pourquoi pas ? Est-ce que tu viens de briser Wikipedia pour le reste du monde ?
