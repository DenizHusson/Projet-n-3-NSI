# Projet-n-3-NSI

Projet scolaire de Terminale en lien avec la matière Numérique et Science de l'Informatique.


Contexte : 
Le joueur est un enquêteur et dois résoudre une affaire criminel. L'histoire se déroule à Puteaux dans la richissime demeure des Mercury. Hervé, le doyen de la famille et propriétaire d'une grande entreprise d'huile d'olive basée à Cassis, est retrouvé inanimé dans baignoire. C'est Margaux, l'infirmière qui était à sa charge qui a découvert le corps à environ 19h30 en l'appelant pour diner. Hervé a 3 enfants, une fille Julie et deux fils, Thomas et Deniz. Toute la famille était réuni pour la semaine de Noël. 

Première partie : l'interrogatoire 

Question 1 : Désirez-vous vous rendre sur les lieux du crime ? 
oui --> la mission continue 
non --> le chef de la police vous remplace sur cette mission et vous partez en vacances 

Question 2 : Une fois sur les lieux du crime, souhaitez vous interroger Thomas l'ainé de la fraterie ? 
Oui --> Thomas vous révèle qu'au moment du crime il était avec Julie dans le salon en train de ranger des livres dans la bibliothèque
Non --> Vous pouvez interroger quelqu'un d'autre 

Question 3A(découle du oui à la Q2) : Désirez vous interroger Julie pour confirmer les dires de Thomas ?
Oui --> Julie vous confirme les faits 
Non --> Vous pouvez interroger quelqu'un d'autre 

Question 3B(découle du non à la Q2) : Souhaitez vous interroger Julie ?
Oui --> Julie vous révèle qu'au moment du crime elle était avec Thomas dans le salon en train de ranger des livres dans la bibliothèque
Non --> Vous pouvez interroger quelqu'un d'autre

Question 4A(découle du oui à la Q3A) : Souhaitez vous inerroger Deniz ?
Oui --> Deniz vous dévoile qu'il était seul dans sa chambre en train de réviser ses partiels 
Non --> Vous pouvez interroger quelqu'un d'autre (il ne reste que Margaux)

Question 4B(découle du non à la Q3A) : Souhaitez vous interroger Deniz ? 
Oui --> Deniz vous dévoile qu'il était seul dans sa chambre en train de réviser ses partiels 
Non --> Vous pouvez interroger quelqu'un d'autre (il ne reste que Margaux)

Question 4C(découle du oui à la Q3B) : Souhaitez vous interroger Deniz ?
Oui --> Deniz vous dévoile qu'il était seul dans sa chambre en train de réviser ses partiels 
Non --> Vous pouvez interroger quelqu'un d'autre (il ne reste que Margaux)

Question 4D(découle du non à la Q3B): Souhaitez vous interroger Deniz ?
Oui --> Deniz vous dévoile qu'il était seul dans sa chambre en train de réviser ses partiels 
Non --> Vous pouvez interroger quelqu'un d'autre (il ne reste que Margaux)

Question 5A(découle de oui à la Q4A): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Question 5C(découle de non à la Q4A): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Question 5C(découle de oui à la Q4B): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire

Question 5D(découle de non à la Q4A): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Question 5E(découle de oui à la Q4C): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Question 5F(découle de non à la Q4C): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Question 5G(découle de oui à la Q4D): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Question 5H(découle de non à la Q4D): Souhaitez vous interroger Margaux ? 
Oui --> Margaux vous explique qu'après avoir préparer la piqure habituelle d'Hervé, elle découvre son corps inanimé dans la baignoire avec un liquide violet mélangé à l'eau
Non --> Vous n'avez plus personne à interroger c'est la fin de l'interrogatoire 

Fin de la première étape



Deuxième partie : inspection des pièces

Question 1 : Maintenant que vous avez fini d'inerroger tout le monde, souhaitez faire une inspection des chambres pour vérifier les alibis de chacun 

#Première Partie :
dico[1] = {"Désirez-vous vous rendre sur les lieux du crime ? ","la mission continue","le chef de la police vous remplace sur cette mission et vous partez en vacances "} 
dico[2] = {"Une fois sur les lieux du crime, souhaitez vous interroger Thomas l'ainé de la fraterie ?","Thomas vous révèle qu'au moment du crime il était avec Julie dans le salon en train de ranger des livres dans la bibliothèque","Vous pouvez interroger quelqu'un d'autre "}
dico[3] = {"Désirez vous interroger Julie pour confirmer les dires de Thomas ?","Julie vous confirme les faits",""}
dico[4] = {"","",""}
dico[5] = {"","",""}
dico[6] = {"","",""}
dico[7] = {"","",""}
dico[8] = {"","",""}
dico[9] = {"","",""}
dico[10] = {"","",""}
dico[11] = {"","",""}
dico[12] = {"","",""}
dico[13] = {"","",""}
dico[14] = {"","",""}
dico[15] = {"","",""}
