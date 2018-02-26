#Séance du 18 décembre 2017


Nous avons décidé avec mon binôme Roxane Lestrez de faire un brain-storming pour trouver un projet convenant à nous deux.
Nous avons finis par avoir l'idée de faire un Self-Balancing-Robot avec Arduino.
Nous avons trouvé une très bonne vidéo pour trouver le matériel nécessaire et commencer à réfléchir sérieusement à notre projet.


#Séance du 8 janvier 2018


Nous avons travaillé avec l'accéléromètre, en particulier nous avons cherché des librairies utiles au fonctionnement du gyroscope MPU-6050
(MPU-6050 et i2CScanner) et nous l'avons emprunté pour continuer les recherches chez nous.


#Séance du 15 janvier 2018


Nous avons pris une carcasse d'un self-balancing-robot d'un ancien élève avec un motor controller L298 et 2 moteurs avec des roues pour faire avancer la carcasse. Nous avons donc fait des essais pour faire avancer ou reculer notre robot plus ou moins vite et plus ou moins longtemps.



#Séance du 22 janvier 2018


Nous avons fait notre présentation de 10 minutes sur notre projet et nous avons écouté les présentations des autres groupes pendant une bonne partie de la séance.


#Séance du 21 février 2018


Nous avons fait marcher nos nouvelles roues (les roues que nous allons utiliser pour le robot final), bien que des problèmes soient arrivés. En effet, nous avons eu un problème de masse commune: il y a une masse pour la carte arduino (pour contrôler le robot avec un programme) et une pour le générateur de tension (pour appliquer une tension de 12 Volt, ce qui n'est pas possible por l'arduino). Nous avons donc dû relier les 2 masses pour que les composants n'aient pas besoin de s'adapter. En effet, quand nous n'avions pas relié les masses, les roues ne tournaient pas à leur vitesse maximale et pas tout le temps (notre programme faisait tourner les roues continuellement et à vitesse maximale). En parallèle, nous avons pris en main l'accéléromètre pour combiner les deux: nous avons réussi à faire tourner les roues dans un sens quand l'accéléromètre donnait une valeur entre  et 0 et 180° et les faire tourner dans l'autre pour les valeurs de 180 à 360°.






