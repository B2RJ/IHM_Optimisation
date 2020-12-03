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

Le Log Likelihood est à -660 pour CK contre -780 pour random, ce qui veut dire que le modèle CK s'approche plus du comportement de l'utilisateur. Pour le BIC, CK obtient à nouveau un meilleur score avec 1340 contre 1560 pour le random. Pour le score BIC cela implique que même avec un paramètre supplémentaire (ce qui implique une pénalité), CK est meilleur que Random. Nous pouvons en déduire que le meilleur modèle entre les deux est CK. 

Pour l'analyse des techniques, la technique audio obtiens de meilleurs résultats avec le modèle random, mais c'est la technique traditionnelle qui est plus concluante avec le modèle CK. 

Dans les deux valeurs, Log Likelihood et BIC, il est nécessaire que la barre soit basse. En effet, pour le Log Likelihood la légende est négative, la barre la plus petite représente donc la valeur la plus grande. Pour le BIC, la légende est positive mais c'est la plus petite valeur qui rapporte le meilleur score. 

Q4 : Comment à évoluer la vraisemblance ? de manière absolu et relative ? Quel est maintenant le meilleur modèle ? pour quels utilisateurs ? pour quelles techniques ?

On constate aisément que l'écart s'est accentué entre le modèle Random et le modèle CK. L'ensemble des valeurs s'est rapproché de 0. Le meilleure modèle reste CK. En revanche, la tendance est différente au sein des techniques. En effet, la technique traditionnel obtient des meilleurs statistiques que la technique audio et ceux, peu importe le modèle. 

Maintenant : 

- Log Likelihood Moyen Random : 560
- Log Likelihood Traditionnel Random : 480
- Log Likelihood Audio Random : 640

- Log Likelihood Moyen CK : 180
- Log Likelihood Traditionnel CK : 70
- Log Likelihood Audio CK : 275

- BIC Moyen Random : 1150
- BIC Traditionnel Random : 970
- BIC Audio Random : 1300

- BIC Moyen CK : 340
- BIC Traditionnel CK : 150
- BIC Audio CK : 550

Avant : 

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

Q5 Quel est le « meilleur modèle » ?

Explication de la légende: 
Couleur = technique
Pointillé ou non = méthode

Nous constatons ici que le meilleur modèle est le modèle random. En effet, les valeurs issues de ce modèle sont plus proches des valeurs issues des observations. 

Q6 Est-ce que les modèles vous semblent bons dans l’absolu ?

Dans l'absolue, aucun des deux modèles colle complètement aux observations. Les observations ont logiquement une tendance fortement croissante alors que les modèle sont plutôt constants. 

Partie 6 q6 je pense qu'il voulait dire q7
Du point de vu, du score BIC et likelihood le modèle Rescola-Wagner est ressemblant au modèle CK. Mais en observant la simulation et les observation on constate que le modèle RW ce rapproche plus du comportement utilisateur qui a utilisé la technique audio
Le modèle RW n'est pas bon pour prédire le comportement avec la technique traditionnel, il propose une prédiction similaire à la technique audio alors que les observations montrent que les utilisateurs  avec la technique traditionnel ne font beaucoup moins de raccourcie clavier.

Partie 7 
q8 ou q7
La combinaison des deux modèle CK et RW permet d'amélioré les résultat, cela permet de prendre la qualité de prédiction pour la techinque traditionnel de CK et la qualité de prédiction du modèle RW pour la technique audio.