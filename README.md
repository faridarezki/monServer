. [x]  Initialiser projet node 
. [x] Initialiser projet git 
. [x] Publication sur github 
. [x] Installation eslint & configuration 
. [] Installation express & mysql 
. [x] Création d'une table MySQL -> mettre les commandes de créations dans le projet (fichier .sql) : 
. [x] Articles 
		. [x] id
		. [x] title
		. [x] content
		. [x] author (INT)
		. [x] created_at (DATETIME)
. [x] Comments 
		. [x] id
		. [x] article_id (INT)
		. [x] author (INT)
		. [x] content
		. [x] created_at (DATETIME)
. [] Création d'un CRD (pas d'Update, on l'a pas vu) node : 
. []Route '/api/articles/create' -> permet de créer un article_id
. [] Route '/api/articles/delete' -> permet de supprimer un article par son id
. [] Route '/api/articles' -> permet de récuperer les 5 derniers articles créés dans un tableau
. [] Route '/api/comments/create' -> permet de créer un commentaire
. [] Route '/api/comments/delete' -> permet de supprimer un commentaire par son id
. [] Route '/api/comments' -> permet de récuperer les 5 derniers commentaires postés
. []Création de formulaires HTML pour tout tester 
. [] Articles 
. []create.html
. [] delete.html
. [] Comments 
. []create.html
. [] delete.html
