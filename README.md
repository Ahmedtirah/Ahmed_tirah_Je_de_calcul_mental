Nom: Jeu de Calcul Mental
Description du projet: Ce projet est un petit jeu de calcul mental réalisé en HTML, CSS et JavaScript. Le joueur doit résoudre des opérations aléatoires dans un temps limité. Le score augmente à chaque bonne réponse et se réinitialise en cas d’erreur. Le meilleur score est sauvegardé grâce au localStorage
Technologies utilisées: HTML pour la structure de la page, Css pour la mise en forme,les animations de feedback visuel et js pour la génération des opérations,la gestion du score et le timer
Fonctionnalités principales: 
1- Génération aléatoire d'opérations (+, −, ×, ÷)
2-Timer de 10 secondes par calcul
3-Feedback visuel :fond vert pour une bonne réponse et fond rouge pour une mauvaise réponse
4-Sauvegarde du meilleur score via localStorage
5-Entrée au clavier supportée (validations via touche Entrée)
Lien vers la page GitHub Pages: https://ahmedtirah.github.io/Ahmed_tirah_Je_de_calcul_mental/
Nouveautés explorées: Pendant le développement, j'ai appris et expérimenté plusieurs concepts :
1-Utilisation de localStorage pour sauvegarder des données persistantes (le meilleur score)
2-Utilisation de setInterval et gestion du timer avec réinitialisation propre
Difficultés rencontrées:
1-Gérer les divisions pour obtenir des résultats entiers (sinon opération impossible à résoudre rapidement)
2-Stockage et récupération du meilleur score à partir du localStorage
3-En JavaScript, il n'existe pas de fonction pour obtenir un entier aléatoire entre deux entier
4-Gestion du timer
Solutions apportées: j'ai resolu ces defficultes aves la recherche 
1-Pour les divisions, modification automatique de a en a*b pour garantir un résultat entier
2-Mise en place de localStorage.setItem() et localStorage.getItem() pour sauvegarder le best score
3-Créer une fonction avec Math.random() qui génère un nombre entre 0 et 1
4-Utilisation de setinterval et clearinterval
