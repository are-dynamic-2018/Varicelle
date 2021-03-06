# Varicelle
Bouziane Yanis , Djedami Sihame , Yalcin Mehmet  
La propagation de la varicelle

description du sujet :
----------------------
On a une classe de maternelle  de 25 élèves que l'on représentera sous forme de matrice.
On admet qu'un élève est en phase d'incubation, c'est-à-dire qu'il est extrêmement contagieux mais ne présente pas encore les symptômes.

Le fait qu'un autre enfant de la classe, et uniquement de la classe, attrape la varicelle est régit par plusieurs paramètres:

On distingue en premier lieu plusieurs états différents pour chaque élève : 

1) Il est sain et n'a jamais attrapé la varicelle //s
2) Il est en incubation et est donc contagieux    //inc
3) Il est malade pour la première fois            // m1
4) Il est malade pour la deuxième fois, dans ce cas on parle de zona //m2 
5) Il est guéri                                   //g1
6) Il est immunisé                                //imu

Dans le cas où l'enfant est guéri, on distingue 2 cas:

Soit l'enfant est immunisé dès la première guérison, ce qui représente environ 80 % de chance.
Soit l'enfant retombe malade, ce qui représente 20 % de risque.
Parmi ceux qui sont retombés malade, ils sont immunisés à 100% après la guérison.

On sait que la varicelle se transmet principalement par le contact physique.
Ainsi, la transmission de la varicelle dans la classe est également conditionnée par les différentes interactions qu'aura l'enfant avec ses camarades de classe.

On étudiera le système sur une durée de 48 heures, ce qui correspond à la phase d'incubation : pendant cette période, la varicelle n'est pas encore détectable et l'enfant malade va encore à l'école.

La problématique la plus simple que l'on pourrait se proposer d'étudier serait de se demander combien d'enfants attrapent la varicelle pendant ces 48 heures.

Mais si on se focalise sur le cas où l'enfant attrape une seconde fois la varicelle, on peut complexifier la problématique en  se demandant quels sont les facteurs augmentant ce risque. 
Par exemple, on peut prendre le facteur hygiène : est-ce que si l'enfant se lave plus ou moins les mains aura plus ou moins de risque de contracter une seconde fois la maladie ? 
Est-ce que le fait qu'un enfant soit élevé dans un environnement que l'on pourrait qualifier de sale (comme par exemple avoir un animal de compagnie) 
diminuerait les risques d'être contaminé à nouveau, étant donné que l'organisme de l'enfant est habitué aux bactéries ?


Compte rendu du 20/02/2018:
--------------------------------------------------------------------------------------------------------------------------
Lors de cette séance nous avons établie notre projet et clarifier celui-ci grâce à nos notes ci-dessus en prenant en compte les remarques faites par nos professeurs lors de notre présentation orale. Nous avons ensuite commencé à coder le début de notre
modèle de la manière la plus simple possible et avec des paramètres manquants que nous incluerons par la suite. 
Pour la prochaine séance nous avons pour objectif de compléter notre premier code simplifié.

Compte rendu du 27/02/2018
-------------------------------------------------------
Lors de cette séance nous avons cherché à programmer un modèle simple avec des 0 et des 1 les 0 représentant les individus sains et les 1 les malades. Après cela nous avons décidé de complexifier légèrement notre travail en ajoutant des espaces vides à notre classe de maternelle.Nous avons donc défini un nombre de case vide par rapport a la taille de notre matrice et le nombre d'élèves, les coordonnées des cases vides ont été défini au hasard dans notre matrice, il reste à introduire un enfant malade parmis les individus sain. 

Compte rendu du 06/03/2018
--------------------------------------------------
lien utile :https://interstices.info/jcms/i_56766/modeliser-la-propagation-d-une-epidemie

Lors de cette séance nous avons introduit un enfant malade dans notre système qui était jusque la illustré de 0 (cases vides) et  de 1 (enfants sains).Nous avons donc introduit aléatoirement un 2 (enfant malade) en utilisant les positions de la matrice précédente.Nous avons donc pour objectif de modeliser la propagation de la varicelle en contaminant les voisins du 2 dans la matrice et en ne faisant rien si son voisin est un 0.

Compte rendu du 13/03/2018
-----------------------------------------------------
Lors de cette séance nous nous sommes porté sur la contamination des individus dans notre matrice par rapport à un seul individu malade, mais nous n'avons pas terminé cette partie, nous continuerons donc ça pour la séance prochaine.Nous avons aussi travaillé sur la partie graphique de notre projet durant cette séance et avons produit une petite animation capable d'afficher une matrice sous forme de carrés de couleur,chaque carrés correspondant à une case de notre matrice et la couleur à un état de l'individu(malade,sains,etc...), cette animation comporte également un titre et une légende.

Compte rendu du 20/03/2018
--------------------------------------------
Lors de cette séance nous avons essayé à partir d'un seul individu d'infecter ses voisins mais les résultats n'ont pas été très concluant nous allons donc continuer d'y travailler pour la semaine prochaine. Nous avons aussi continué de travailler sour la partie graphique et avons réussi à définir le choix des couleurs pour nos élèves de maternelle.

Compte rendu du 27/03/2018
---------------------------------
Lors de cette séance nous avons continuer à programmer l'animation et continuer à essayer de contaminer les autres enfants. Nous avons désormais une animation animée où les enfants se déplace et où les individus infecter infecte les individus sains, néamoins notre fonction de contamination n'est toujours pas complètement opérationnel.Nous avons donc pour objectif de paufiner cette fonction nous allons aussi commencer à réfléchir au rapport et à la présentation final.
