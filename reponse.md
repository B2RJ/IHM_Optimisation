Q0 : Quel est le rôle de la technique d’interaction sur les stratégies utilisées ?

Le rôle de la technique est de faire apprendre des raccourcis clavier aux utilisateurs.

Q1 : Quel est le problème avec cette visualisation ?

Cette visualisation ne nous permet pas de connaitre l'action que l'utilisateur réalise. De ce fait, nous ne savons si il apprends à chaque fois le même raccourcis clavier (car il est peu évident) ou si il en apprend de nouveaux. 
On ne voit pas non plus la fréquence d'utilisation des raccourcis. Du coup, nous ne pouvons pas analyser si l'apprentissage à lieu avec des raccourcis peu fréquent ou si le retour à l'utilisation du menu est sur une commande fréquente. 
Enfin, on ne connait pas le nombre de touches, ni la position des touches pour effectuer le raccourci, facteur qui a sont importance lors de l'apprentissage.

Q2 : Est-ce que les utilisateurs utilisent davantage les raccourcis claviers pour les
commandes fréquentes ?

Pour les utilisateurs avec la technique audio, nous constatons que plus la commande est  utilisé, plus les raccourcis clavier sont utilisé (exemple avec la commande 3, la commande 8 et la commande 11). 
Pour les utilisateurs avec la technique traditionnel, nous constatons qu'il y a peu d'apprentissage, même si la commande est fréquente. 

Q3 : Quel est le meilleur modèle ? pour quels utilisateurs ? pour quelles techniques ? Faut-il que la barre soit haute ou basse ? (bien regarder l’intitulé de l’axe y et le signe de la likelihood)

Faire un tableau des valeurs ci-dessous

Comparatif des modèles :  
Log Likelihood random traditional : -820
Log Likelihood random audio : -730
Moyenne : -775

Log Likelihood CK traditional : -650
Log Likelihood CK audio : -675
Moyenne : -662,5

BIC random traditional : 1650
bic random audio : 1475
Moyenne : 1562,5

bic CK traditional : 1300
bic CK audio : 1370
Moyenne : 1335


Log Likelihood : Plus c'est haut, mieux c'est
BIC : Plus c'est haut, moins c'est bien. 

D'un point de vue général, le modèle CK semble être le meilleur, mais nous allons analyser technique par technique. 

Pour la technique traditionnelle, aucune idée ce que je dois en tirer

Pour la technique audio, idem 

Faut-il que la barre soit haute ou basse ? 
(Si il parle de la barre en extrémité de graphe :)
Pour Log Likelihood, il faut que la barre soit basse, en effet, c'est une valeur négative et plus le Log Likelihood est grand, mieux c'est. 

Pour le BIC, elle doit egalement est basse, car plus le BIC est petit mieux c'est. 