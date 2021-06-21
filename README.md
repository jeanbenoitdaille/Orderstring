# Orderstring
Ordonner une chaine de caractère
Tout d'abord, il faut séparer les différents prénoms de la chaîne de caractère pour les mettre dans une liste.

En effet, on ne peut pas trier une chaîne de caractère, il va donc falloir passer par une liste.

Pour séparer les différents prénoms, on utilise la fonction split, qui permet de séparer la chaîne de caractère en plusieurs éléments, en opérant la séparation sur la virgule. Vous noterez qu'on a ajouté un espace après la virgule pour ne pas récupérer l'espace dans les prénoms de notre liste.

À ce stade-ci, nous avons donc la liste suivante :

['Pierre', 'Julien', 'Anne', 'Marie', 'Lucien'] 

Il faut maintenant ordonner cette liste, ce que nous faisons à la ligne suivante avec la fonction sort.

chaine_liste.sort() 

Il ne reste plus qu'à joindre de nouveaux les prénoms de la liste avec le caractère que nous avons utilisé précédemment pour réaliser la séparation (une virgule suivie d'un espace). Pour cela, nous utilisons la méthode join.

chaine_en_ordre = ", ".join(chaine_liste) 
