# Varicelle
Bouziane Yanis , Djedami Sihame , Yalcin Mehmet  
La propagation de la varicelle

description du sujet :

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
---------------------------------------------------------------------------------------------------------------------------------

Compte rendu du 20/02/2018:

Lors de cette séance nous avons établie notre projet et clarifier celui-ci grâce à nos notes ci-dessus en prenant en compte les remarques faites par nos professeurs lors de notre présentation orale. Nous avons ensuite commencé à coder le début de notre
modèle de la manière la plus simple possible et avec des paramètres manquants que nous incluerons par la suite. 
Pour la prochaine séance nous avons pour objectif de compléter notre premier code simplifié.

