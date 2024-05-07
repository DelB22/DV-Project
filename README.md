# DV-projet

### Table des matières

1. Introduction
2. Premier graphe
3. Deuxième graphe
4. Troisième graphe
5. Conclusion

## Introduction
**Projet data visualisation P2024**

Dans le cadre de mon master en droit, criminalité et sécurité des technologies de l'information, j'ai suivi le cours *Visualisation des données* du Professeur Pante.

N'ayant pas d'expérience précédente en la matière, j'ai utilisé la plateforme Observable (https://observablehq.com/) afin de créer des graphiques pour visualiser des données professionnelles. En effet, dans le cadre de ce cours, nous devons présenter un projet contenant trois graphes. C'est ainsi que j'ai choisi d'analyser des données liées au mandat que j'effectue pour QuidJuris. Cette association, créée en 2011, propose à toutes et tous des analyses juridiques de droit suisse à bas prix.

Je, conseillère pour QuidJuris, résous les questions juridiques des clients au nom de l'association. Dans ce cadre, je collecte également des données sur les avis de droit fournis et la clientèle. À ma connaissance, les bases de données de l'association n'ont encore jamais été utilisées à des fin de visualisation, d'où ma curiosité de pouvoir enfin avoir une vue d'ensemble.

Pour protéger les données de mon association, j'en ai modifié certaines. Néanmoins, les proportions restent inchangées.

## Premier graphe

Le premier graphes rassemble toutes les bases de données de QuidJuris. Il sert à comparer le nombre de demandes reçues depuis la création de l'association jusqu'à l'année 2023. 2024 n'est bien sûre pas prise en compte puisqu'elle n'est pas encore achevée. Néanmoins, une fois qu'elle le sera, je pourrais ajouter la base de donnée 2024 à la visualisation ci-dessous, ainsi que les années  qui suivront. 

![GitHub Logo](https://github.com/DelB22/DV-projet/raw/main/graph-annees.png)

Ce graphe n'est qu'une vue d'ensemble du nombre de demandes reçues. Il ne prend par exemple pas en compte la longueur de chaque demande, ce qui fait varier considérablement le temps nécessaire pour rédiger un avis de droit et les honoraires perçus. Le graphe ne fait non plus de distinction en fonction de la matière, ce que le graphe suivant corrige. 

## Deuxième graphe

Ce graphe représente la quantité de demandes reçues sur six ans. Contrairement au graphe précédent, y est également présent le domaine de droit concernées par les demandes.

![GitHub Logo](https://github.com/DelB22/DV-projet/blob/main/graph-matieres.png)

Pour des raisons de lisibilité, tous les domaines traités durant ces six ans ne sont pas affichés dans le graphe. Tous les avis rédigés par QuidJuris couvrent au moins vingt matières juridiques par an. De ce fait, j'ai choisi d'aborder seulement les domaines pour lesquels l'association reçoit le plus de demande. À cela, j'ai adjoint deux matières qui m'intéresse d'étudier sur le temps : 

- Covid : durant la période du *lockdown*, certains clients nous ont posé des questions sur différentes conséquences juridiques de la pandémie. Malgré la présence peristante du Covid, il semblerait que, pour nous clients, les inquiétudes sur le côté légal de la maladie aient diminuées avec la fin du *lockdown*. Il sera intéressant de savoir si un sujet qui pourra potentiellement refaire surface, notamment par rapport aux remboursements des prêts effectués par la Confédération ;
- La protection des données : en plus des d'avis juridiques sur la protection des données, QuidJuris propose également des formations sur le sujet depuis deux ans (pas inclus dans les nombres de demandes). À travers ces formations et le chiffre croissant de questions traitées sur ce domaine par QuidJuris, nous avons pu constaté que c'est un sujet devenant de plus en plus anxiogène. En effet, entre le Règlement général sur la protection des données (RGPD/UE) et l'entrée en vigueur en septembre 2023 de la nouvelle Loi fédérale sur la protection des données (LPD), ce domaine de droit est d'actualité. Nous avons remarqué que beaucoup de petites sociétés peinent souvent à savoir si ce qu'elles font est légal. Ayant consulté toutes les bases de données de QuidJuris, je peux affirmer que la protection des données n'a jamais fait partie des questions posées par nos clients avant 2021.

Au demeurant, j'ai fait face à quelques problèmes en collectant les données pour déterminer le domaine de droit. En effet, souvent, une demande ne peut pas être cantonnée à une seule matière juridique. Certaines demandes relevées concernaient plusieurs domaines présents dans le graphe. Dans ce genre de situation, j'ai attribué la demande au domaine qui semblait prépondérant. 

## Troisième graphe

![GitHub Logo](https://github.com/DelB22/DV-projet/blob/main/graph-facilit%C3%A9.png)


## Conclusion

Vous trouverez ci-dessous le lien vers le Notebook Observable :

<iframe width="100%" height="500" frameborder="0"
  src="https://observablehq.com/embed/efe83815ec470cfa@112?cell=*&api_key=4fbcd42ac1d656b2669981dc02ee5adc29e5080b"></iframe>
  
