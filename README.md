# Analyse des données de l'association QuidJuris

### Table des matières

1. Références du projet
2. Introduction
3. Demandes par année
4. Demandes par matière
5. Facilité en cours vs. en pratique
6. Conclusion

## Références du projet

**Cours** : Visualisation des Données, Master DCS, UNIL

**Professeur** : Isaac Pante

**Titre** : Projet Data Visualization P2024 - Analyse des données de l'association QuidJuris

**Auteur** : Delphine Bonzon 

**Année académique** : 2023-2024

**Semestre** : printemps

## Introduction

Dans le cadre de mon master en droit, criminalité et sécurité des technologies de l'information, j'ai suivi le cours *Visualisation des données* du Professeur Pante.

N'ayant pas d'expérience précédente en la matière, j'ai utilisé la plateforme Observable (https://observablehq.com/) afin de créer des graphiques pour visualiser des données professionnelles. En effet, dans le cadre de ce cours, nous devons présenter un projet contenant trois graphes. C'est ainsi que j'ai choisi d'analyser des données liées au mandat que j'effectue pour QuidJuris. Cette association, créée en 2011, propose à toutes et tous des analyses juridiques en droit suisse à bas prix (https://qjuris.ch/). De plus, QuidJuris poursuit un deuxième objectif : en effet, elle n'engage comme madataire que des étudiants de droit, tels que moi, afin de leur offrir une première expérience en la pratique. 

Je, conseillère pour QuidJuris, résous les questions juridiques des clients au nom de l'association. Dans ce cadre, je collecte également des données sur les avis de droit fournis et la clientèle. À ma connaissance, les bases de données de l'association n'ont encore jamais été utilisées à des fin de visualisation, d'où ma curiosité de pouvoir enfin avoir une vue d'ensemble.

Pour protéger les données de mon association, j'en ai modifié certaines. Néanmoins, les proportions restent inchangées.

## Demandes par année

![GitHub Logo](https://github.com/DelB22/DV-projet/raw/main/graph-annees.png)

**Hypothèse et orientation de recherche**

De quelle façon le nombre totale de demandes reçues par QuidJuris a changé à travers les années ? Est-ce que les chiffres de l'association sont en augmentation ?

**Choix**

Ainsi, ma première visualisation est une vue d'ensemble du nombre de la quantité de travail effectuée par QuidJuris. Pour ce faire, j'ai rassemblé toutes les bases de données de l'association pour comparer le nombre de demandes reçues par an depuis sa création jusqu'à l'année 2023. 2024 n'est bien sûre pas prise en compte puisqu'elle n'est pas encore achevée. Un diagramme d'aires me semble approprié pour représenter l'évolution de cette valeur au fil du temps. J'y ai ajouté une graphique linéaire et un dégradé pour mettre plus en évidence l'ampleur ou l'absence de changement.

**Lecture**

Durant les dix ans d'existance de QuidJuris, l'assocation a connu un pique de nombre total de demandes en 2012 et 2013, avant de redescendre brusquement jusqu'en 2018. Depuis 2019, QuidJuris bénéficie d'une croissance modeste. Nous pouvons constater que les années 2012-2013 sont les seules dont la part de la ligne est de couleur rouge.

**Interprétation**

Cette visualisation permet d'avoir une vue d'ensemble de l'évolution de QuidJuris depuis sa création. S'agissant du pique en 2012-2013, il est important de savoir, qu'à l'époque, l'association avait joui de publicité puisque sa création avait suscité quelques articles de journaux. Depuis, à ma connaissance, QuidJuris est plutôt une association connue de bouche-à-oreille, cette dernière n'ayant pas fait de publicité particulière à propos de ses services. Néamoins, ce graphe est insuffisant pour déduire que la publicité était la cause certaine de la nette augmentation de l'activité de QuidJuris. Cette hypothèse pourrait cependant être étoffée si l'association promouvait encore une fois ses services : en effet, nous pourrions étudier l'effet de cette nouvelle publicité sur le nombre de demandes.

Ce graphe n'étant qu'une vue d'ensemble du nombre de demandes reçues, il prend par exemple pas en compte la complexité de chaque demande, ce qui fait varier considérablement le temps nécessaire pour rédiger un avis de droit et les honoraires perçus. Le graphe ne fait non plus de distinction en fonction de la matière, ce que le graphe suivant corrige. 

## Demandes par matière

![GitHub Logo](https://github.com/DelB22/DV-projet/blob/main/graph-matieres.png)

**Hypothèse et orientation de recherche**

Quels sont les types de demandes reçues par QuidJuris et en quelle quantité ? Quelle est la matière la plus traitée par QuidJuris ? Est-ce que le nombre de demandes rédigées pour une matière reste proportionnelle par rapport aux autres domaines de droit d'une année à l'autre ? Est-il possible de remarquer certaines tendances et évolutions juridiques en lien avec les changements de notre société ?

**Choix**

Ce graphe représente la quantité de demandes reçues sur six ans. Contrairement au graphe précédent, y est également présent le domaine de droit concernées par les demandes. Un diagramme d'aires a été choisi pour séparer par couleur les différentes matières et pour analyser leur évolution dans le temps, ainsi que la divergence entre les branches. 

Pour des raisons de lisibilité, tous les domaines traités durant ces six ans ne sont pas affichés dans le graphe. Tous les avis rédigés par QuidJuris couvrent au moins vingt matières juridiques par an. De ce fait, j'ai choisi d'aborder seulement les domaines pour lesquels l'association reçoit le plus de demande. À cela, j'ai adjoint deux matières qui m'intéressent d'étudier plus en profondeur sur le temps

**Lecture**

Le nombre total de demandes par année est représenté par matière :

- *Bail* : noir
- *Travail* : jaune clair
- *Droit matrimonial* : mauve
- *Successions* : jaune
- *Sociétés et et associations* : orange
- *Protectiond des données* : orange foncé
- *Droits réels et constructions* : violet
- *Poursuite et faillite* : bordeau
- *Covid* : bleu foncé


**Interprétation**
 
Nous pouvons déduire de la visualisation que le nombre de demandes par matière ne reste pas dans les mêmes proportions chaque année. Le droit du travail et le droit de bail sont clairement les deux domaines de droit les plus recherchés par nos clients. De plus, nous pouvons noter l'apparition de certaines "nouveautés" en fonction de l'évolution de notre société, telles que la protection des données et les questions juridiques liées au Covid.

Nous pouvons également formuler une hypothèse sur le type de clients que notre association attire. En effet, les domaines les plus prisés sont le droit du bail, du travail (nous sommes plutôt contactés par des employés que par des employeurs) et le droit matrimonial. Nous pouvons ainsi arguer que notre client moyen est une personne physique (donc pas morale, c'est-à-dire les sociétés) nous contactant pour des problèmes impactant sa vie privée (famille, logement et emploi).

Certains domaines inclus dans le graphe mérite des explications supplémentaires :

- Covid : durant la période du *lockdown*, certains clients nous ont posé des questions sur différentes conséquences juridiques de la pandémie. Malgré la présence peristante du Covid, il semblerait que, pour nos clients, les inquiétudes sur le côté légal de la maladie aient diminuées avec la fin du *lockdown*. Il sera intéressant de savoir si un sujet qui pourra potentiellement refaire surface, notamment par rapport aux remboursements des prêts effectués par la Confédération ;
- La protection des données : en plus de la rédaction d'avis juridiques sur la protection des données, QuidJuris propose également des formations sur le sujet depuis deux ans (pas inclus dans les nombres de demandes). À travers ces formations et le chiffre croissant de questions traitées sur ce domaine par QuidJuris, nous avons pu constaté que c'est un sujet devenant de plus en plus anxiogène. En effet, entre le Règlement général sur la protection des données (RGPD/UE) et l'entrée en vigueur en septembre 2023 de la nouvelle Loi fédérale sur la protection des données (LPD), ce domaine de droit est d'actualité. Nous avons remarqué que beaucoup de petites sociétés peinent souvent à savoir si ce qu'elles font est légal. Ayant consulté toutes les bases de données de QuidJuris, je peux affirmer que la protection des données n'a jamais fait partie des questions posées par nos clients avant 2021.

Au demeurant, j'ai fait face à quelques problèmes en collectant les données pour déterminer le domaine de droit. En effet, souvent, une demande ne peut pas être cantonnée à une seule matière juridique. Certaines demandes relevées concernaient plusieurs domaines présents dans le graphe. Dans ce genre de situation, j'ai attribué la demande au domaine qui semblait prépondérant. 

## Facilité en cours vs. en pratique 

![GitHub Logo](https://github.com/DelB22/DV-projet/blob/main/graph-facilit%C3%A9.png)

**Hypothèse et orientation de recherche**

Quelle est la différence de facilité ressentie entre une branche étudiée à l'Univerité et cette même branche, mais en pratique ? Existe-t-il un écart entre les deux ? Si oui, dans quel ordre de grandeur ?

**Choix**

Cette visualisation cherche à quantifier la différence de facilité entre un domaine de droit étudié dans un cadre académéque et pratiqué dans le cadre d'un métier. Le graphe ne traite, bien évidemment, que des matières vues dans les deux environnemments. Par exemple, le cours de droit romain de deuxième année de Bachelor de droit, bien que très apprécié, ne peut pas figurer sur ce graphe. Il y a également des questions soulevées par des clients que l'Université n'a pas couvertes, comme beaucoup des conséquences juridiques liées au Covid, ainsi que la rédaction de contrats ou de lettres pour les clients. Pour ce faire, une représentation par nuage de points semble adéquate pour exposer la différence entre deux variable. Pour comparer les matières entre elles, ou plutôt leur divergence entre les deux environnements, j'ai inséré à la visualisation des lignes pour relier le point *cours* à son point *QuidJuris* correspondant. 

L'effet ombré n'est que purement artistique.

**Lecture**

Le dernier graphe est plus personnel puisqu'il compare la différence entre le niveau de facilité que j'ai ressenti en étudiant un domaine de droit à l'Université et celui en le pratiquant dans le cadre de mon mandat pour QuidJuris.

- *QuidJuris* : violet
- *Cours* : rose

**Interprétation**

L'écart de la facilité ressentie en cours et celle dans la pratique dépend lourdement de la matière. En effet, en droit administraitf, droit du bail, du travail, des obligations (autres) et en poursuite pour des dettes et faillite, nous constatons que la différence entre les facilités est minimes, alors par exemple la variation en droit matrimminal, des successions et de la protection des données est conséquente. 

Certains domaines inclus dans le graphe mérite des explications supplémentaires :

- Le droit matrimonial et des successions : en cours, j'ai trouvé ces deux branches très compliquées, alors qu'en pratique, les questions des clients sont relativement aisément résolues. À mon avis, cela pourrait être lié aux types de questions posées. En effet, j'imagine que pour le droit matrimonial, qui est le plus couramment une question de divroce ou d'entretien chez QuidJuris, les clients ne posent que des questions préliminaires puisque ce sont des problèmes juridiques où ils doivent souvent saisir la justice de toute façon. Quant au droit des successions, les notaires sont spécialisés en la matière et d'après moi, les clients se tourneront plutôt vers eux pour régler en détail leurs problèmes à ce sujet. L'écart important pourrait aussi être preuve d'un bon enseignement d'une matière difficile, devenue plus simple par les connaissances partagées. 
- Le droit du bail : cette matière n'est pas une branche à elle seule à l'Université, contrairement au droit du travail qui, chaque année, concerne un peu moins de demandes que le bail (*cf*. graphe - matières). En effet, le bail est un chapitre du cours *Contrats spéciaux* de troisième année de droit. Pourtant, ce type de contrat soulève le plus de questions pour nos clients, comme le démontre le deuxième graphe ;
- Protection des données : comme mentionné plus haut, la protection des données est un domaine du droit en grand développement. De ce fait, il n'y a que peu de jurisprudence et de pratique, surtout adaptée aux petites et moyennes entreprises. D'où la grande différence quant au niveau de facilité entre QuidJuris et les cours. Nos clients nous demandent, dans le cadre des formations et des demandes, comment, par exemple, concrétement organiser leur base de données, quels logiciels/boîte mail utiliser pour garantir la sécurité des données, etc. Le cours aide à aiguiller les réponses, mais cela reste compliqué de fournir un conseil alors que le domaine est en grande expansion et présente, ainsi, beaucoup d'incertitudes quant à la concrétisation des règles légales. 

Je tiens également à préciser que ce dernier graphe poursuit plus un objectif artistique et ludique qu'une sérieuse et profonde analyse des difficultés rencontrées. Du reste, nous pouvons noter que la pratique chez QuidJuris, même si ayant des points communs, est différente de la pratique dans un cabinet d'avocat ou dans une entreprise. *Ergo*, ce graphe ne vaut que pour mon expérience propre chez QuidJuris et les résultats d'un graphe que je pourrais réaliser après avoir travaillé ailleurs sera, en toute vraisemblance, divergent du présent.


## Conclusion

Ce projet m'a permis, pour la première depuis que je travaille pour QuidJuris, d'avoir une vue d'ensemble sur les années d'activité de l'association. En effet, comment mentionné auparavant, aucun graphe n'avait été réalisé par le passé avec les bases de données à disposition.

Il est également très intéressant d'observer l'évolution du nombre de demandes par domaine de droit puisque cela permet d'avoir une idée sur ce qui préoccupe nos clients et donc ce qui les poussent à nous contacter.

Vous trouverez ci-dessous le lien vers le Notebook Observable :

<iframe width="100%" height="500" frameborder="0"
  src="https://observablehq.com/embed/efe83815ec470cfa@115?cell=*&api_key=eaeac29348547bed8f0bca5bb98370bad10f76d4"></iframe>rame>
  
