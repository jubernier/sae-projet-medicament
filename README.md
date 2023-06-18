# Projet Médicament

## Présentation du projet :
Un système de renforcement par apprentissage dans lequel un soignant donne des médicaments à des patients. Le soignant ne connait pas les pourcentage de réussite des médicaments. Ainsi, le soignant évalue le succès de chaque médicament en fonction du retour qu'il a dut patient. Alors, il peut supposé un pourcentage de réussite pour chaque médicament. Il détermine alors le médicament qui va être donné ensuite au patient. Le but est pour le soignant de trouver le(s) médicament(s) le(s) plus efficace(s) pour soigner le plus de patients possible.

## Présentation des règles :
Des soignants ont accès à 10 types de médicaments. Ils peuvent attribuer 1 médicament par jour à un et un seul patient. Le but est de maximiser les chances de guérisons des patients au cours des 100 jours d'expériences. Un médicament réussit ou est un échec à  sur un patient.

## Structure du projet et méthodes choisies :
- J'ai commencé par réalisé la classe qui représente les **médicaments**. Dans le système, il y a connaissance ici des réelles pourcentages de réussite des médicaments. Quand il est pris par le patient il peut ainsi en fonction des pourcentage de réussite être soigné ou non.
- La classe ```patient``` ou les méthodes permettent de déterminer lorsqu'un médicament a réussis à soigner le patient ou non, en fonction des pourcentages de réussite définis dans ```medicament```. 
- Ensuite, la classe ```soignant``` détermine qu'elle médicament attribué au patient afin d'en soigné le plus possibles.
	- J'ai commencé par développer le stratégie ```findBestMedicIn30jours``` dont le principe est de testar pendant les 20 premiers jours tous les médicaments 2 fois et de garder ceux qui suite à l'expérience on eu le plus de succès. Ainsi, réduire la liste des médicaments à prendre puis, de tester ceux-ci pendant 10 jours, et de trouver le meilleur médicament entre les 5 qu'il reste.

	- La stratégie ```findBestMedicWithBeta``` repose sur l'utilisation de la loi Beta pour déterminer le médicament à administrer aux patients. La loi Beta est une distribution de probabilité continue définie sur une intervalle. Elle est utilisée pour modéliser des variables aléatoires qui représentent des proportions ou des probabilités. Dans ce contexte, la loi Beta est utilisée pour estimer les probabilités de succès des médicaments, c'est-à-dire la probabilité qu'un médicament soit efficace pour soigner un patient.

### Résultat commenté

Résultat de la méthode ```findBestMedicIn30jours``` :


Résultat de la méthode ```findBestMedicWithBeta```:


### Interprétation
# courbe Beta et courbe de si il avait déjà su les pourcentage # de réussite sur les deux courbes pour comparer
# texte et courbe et résultat  commenté
# interprétation des résultat
# bonne forme pour dire ce qu'on veut

# explique vitre technique
# explique votre compréhension du probleme
# les resultats expérimentaux comment évaluer votre technique
 
# qu'el courbe auriez vous obtenu si vous saviez déjà la valeur de la courbe comparer
# pdf