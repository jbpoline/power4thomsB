

# Mail de Thomas: 

(see https://mail.google.com/mail/u/0/?shva=1#search/from%3Athomasb%40pasteur.fr/1584370e8c4ba1b8)

Salut JB,

Je suis en train de rédiger ma réponse pour les reviewers (pour le 14 Novembre !!) et Thomas a fait un super boulot pour une nouvelle estimation du nombre de Résilients dans la population générale et élargir aux gènes de la SFARI pas seulement les 65 gènes TADA. Dans ma réponse, je vais dissocier: Characterization of the Resilients et Identification of Modifier Genes.

## Characterization of the Resilients

Ici on a des éléments de l'équation réponses: 

- le nombre de Résilients total 
- la distribution des Resilients selon les gènes

Les questions que l'on va poser:

- Quels sont les gènes qui acceptent le plus de Résilience ?
- Y a t-il un sexe plus Resilient qu'un autre en général ?
- Y a t-il des gènes ou des pathways qui sont plus résilients dans un sexe ou dans un autre ? 
- Y at-il une région du cerveau qui accepte plus la Résilience ?

En gros pour le sexe il n'y a que 2 possibilité (en restant simple !). On peut donc j'imagine estimer quel est le pouvoir statistique de notre étude en fonction du nombre de Résilients que l'on va trouver. Pour les Pathways et pour les régions du cerveau, il a plus de catégories mais on pourrait faire l'estimation de combien de catégorie nous pouvons tester en fonction du nombre de Résilients que l'on trouve.

## Identification of Modifier Genes

Ici c'est plus compliqué car on a pas d'estimation sur

- le nombre de facteur de Resilience
- leur effect size
- leur spécificité

Il faut donc modéliser plus de situation !

Pour la spécificité, dans notre projet, nous avons inclus une population de patients mutés pour le gène SHANK3 (environ 300). Grâce à cette population on va pouvoir rechercher des facteurs modulateurs du phénotype comme pour l'épilepsie qui est retrouvée chez 20-20% des patients.

Déjà si tu pouvais nous aider sur la première partie Characterization of the Resilients après on revient vers toi pour la partie identification. Je sais que tu es super pris mais ce serait super d'avoir ton avis/expertise.

## Reponse JB 

We need to see if the proportion of say the homozygote allele is the same in the resilient group versus the non resilients. 

So, we want to test if $$ \hat{p_P} == \hat{p_R} $$ . 

### if app
If: n1 p1 > 5 and n1(1 − p1) > 5 and n2 p2 > 5 and n2(1 − p2) > 5 and independent observations,
then we can do an estimation with the normal distribution 

http://stats.stackexchange.com/questions/113602/test-if-two-binomial-distributions-are-statistically-different-from-each-other

https://en.wikipedia.org/wiki/Statistical_hypothesis_testing
(see: Two-proportion z-test, pooled for H0 : p1 = p2)  

### Difference of two binomials:

more complicated but feasible

http://math.stackexchange.com/questions/562119/difference-of-two-binomial-random-variables


## References

http://www.stat.wisc.edu/~st571-1/10-power-4.pdf
http://math.stackexchange.com/questions/562119/difference-of-two-binomial-random-variables



