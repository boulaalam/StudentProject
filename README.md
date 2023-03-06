# StudentProject
On souhaite décrire de manière sommaire la gestion des étudiants pour l'université à travers une petite application C++. Un étudiant est caractérisé par un matricule, c'est l'identifiant de l'étudiant (auto-incrémenté).  L'identifiant du premier étudiant commence avec la valeur 23001. 
Un étudiant a aussi un nom complet. En plus chaque étudiant a une moyenne générale. 
Dans cette application C++ les services suivants sont demandés : 
	Un constructeur sans paramètres et d’initialisation ("Inconnu" pour les chaines de caractère et 0 pour les numériques) ; 
	Un constructeur avec arguments ; 
	Un constructeur de recopie ; 
	La surcharge l'operateur d’affectation ;
	Le destructeur pour libérer la mémoire ; 
	Les getters et les setters ;
	Une méthode print pour afficher l’ensemble des informations d’un étudiant ;
	Une fonction print (surchargée) pour afficher les objets constants ;
	Une fonction admis qui retourne vrai, si un étudiant est admis (moyenne > 10).
Deux étudiants sont égaux s'ils ont le même nom et la même moyenne. Proposer une fonction membre pour répondre à ce besoin. 
Un étudiant est supérieur à un autre s’il a une moyenne supérieure. Redéfinir l’operateur > pour répondre à ce besoin. 
Supposons o1 un objet de la classe, une instruction o1++ ; incrémente la moyenne de o1 de 1,5 points. Proposer une fonction membre pour répondre à ce besoin.
Note : 
	Pour bien déboguer notre application, des messages de traçage sont fortement souhaités. 
	Une fonction déclarer et non tester dans le main = 0. 
	Enrichir votre code avec des explications technique de fonctionnement (type de passage, appels, etc.)
Questions :
1.	Donner le diagramme de classe UML de la classe en question.
2.	Donner le code source de cette application. Les fichiers en-tête et les fichiers d’implémentation. 
3.	Tester tous les services de votre classe (la fonction main).
4.	Donner l'output (un écran d’exécution) du test de la question 3.
