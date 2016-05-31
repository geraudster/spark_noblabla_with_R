## Atelier Spark NoBlabla - Version R

Ce projet contient les notebooks Jupyter réimplémentant l'Atelier Spark du TDS.

Pour l'instant, seul l'exercice 5 (05 Using Spark-CSV and exploring data) est implémenté entièrement.
Les principales différentes par rapport à l'API Python:

* l'API RDD n'est pas publique sous R, c'est pour cette raison que les exercices avant le 5 ne sont pas implémentés
* la fonction _pivot_ n'est pas encore implémentée (d'où l'implémentation partielle de l'exo 6)

À part ces quelques points, les API Python et R restent très similaires.

## Exécution du notebook

Le notebook a été réalisé sur une image docker, accessible là: https://hub.docker.com/r/geraudster/rjupyter-spark/ 
