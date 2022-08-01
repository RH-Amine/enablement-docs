<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture and Practice <!-- {_class="course-title"} -->
### Cartographie des processus basée sur les métriques <!-- {_class="title-color"} -->
DO500 <!-- {_class="title-color"} -->



### Value Streams
Chaque tableau sélectionne un secteur et un cas d'utilisation métier (quelques exemples ci-dessous) :
* Telco - Commande d'un nouveau forfait large bande
* Finance - Création d'un nouveau compte courant
* Gouvernement - Paiement de la taxe d'habitation
* Énergie - Changement de fournisseur d'énergie

Quel est l'élément déclencheur du flux ?
Quelle est la valeur métier finale ?
Quelles sont toutes les étapes intermédiaires ?
Quelle est la technologie ou le système qui permet de réaliser cette étape ?



### Cartographie des processus basée sur les métriques
#### _Qu'est-ce que c'est ?_
* Fortement influencé par le travail de Karen Martin dans ce domaine.
* Conçus pour visualiser la vision détaillée, la situation et apporter des améliorations tactiques avec les travailleurs de première ligne.
* La première génération est issue du "flux d'informations et de matériaux" de Toyota.
tel que documenté dans [Lean Thinking] (https://rht-labs.github.io/practice-library/practices/vsm-and-mbpm/#footnote-1)
et la deuxième génération de [Learning to See] (https://rht-labs.github.io/practice-library/practices/vsm-and-mbpm/#footnote-2).



### Cartographie des processus basée sur les métriques
#### _Pourquoi l'utiliser?_
* Analyser et optimiser les processus de livraison "brownfield", y compris la définition des besoins, l'approvisionnement en infrastructure et le développement d'applications.
* Représenter visuellement la manière dont le travail progresse dans une organisation.
* Construire une compréhension partagée à travers les différents niveaux de l'organisation.
comment le travail est réellement effectué.
* Formuler des plans d'amélioration spécifiques, basés sur des données.



### Cartographie des processus basée sur les métriques
Comment



#### Etiquettez la carte et créez "des couloirs de natation"
![Map Label](images/vsm/mbpm-swim-lanes.png)



#### Ajoutez le temps
![Map Label](images/vsm/mbpm-swim-add-time.png)



#### Ajouter les activités (les étapes) sur la carte
![Map Label](images/vsm/mbpm-steps.png)



#### Certaines peuvent être en parallèle
![Map Label](images/vsm/mbpm-steps-final.png)



### Cartographie des processus basée sur les métriques
Documenter toutes les activités (les étapes)



#### L'activité
![the activity](images/vsm/mbpm-activities-0.png)



#### Nommez l'activité et qui est impliqué
![Map Label](images/vsm/mbpm-activities-1.png)



#### Ajoutez le nombre de personnes
![Map Label](images/vsm/mbpm-activities-2.png)



#### Ajouter de la précision
![Map Label](images/vsm/mbpm-activities-3.png)



#### Délai de traitement / délai d'exécution
![Map Label](images/vsm/mbpm-activities-4.png)



### Cartographie des processus basée sur les métriques
Différence entre délai d'exécution et temps de traitement


![Map Label](images/vsm/pt-lt-1.png)



![Map Label](images/vsm/pt-lt-2.png)



![Map Label](images/vsm/pt-lt-3.png)



### Cartographie des processus basée sur les métriques
#### métriques: temps
* Temps de traitement (PT)
  * Le temps nécessaire pour effectuer le travail, si l'on peut le faire sans interruption.
  * Inclut le temps spécifique à la tâche à accomplir : Toucher, parler, lire et penser.
* Temps de travail (LT)
  * Temps écoulé entre le moment où le travail est mis à disposition et celui où il est achevé et transmis à la personne suivante ou à un autre employé.
  jusqu'à ce qu'il soit terminé et transmis à la personne ou au service suivant dans la chaîne.
  * Comprend le processus


### Cartographie des processus basée sur les métriques
#### métriques: Qualité
* Pourcentage d'achèvement et de précision
* Pourcentage de temps pendant lequel le client suivant peut effectuer la tâche sans avoir à :
  * **Corriger** les informations ou le matériel fournis
  * **Ajouter** des informations qui auraient dû être fournies
 *  **Clarifier** les informations qui auraient dû ou pu être plus claires.



### Cartographie des processus basée sur les métriques: Comment
#### Définir le _chemin critique du calendrier_.
![Critical Path](images/vsm/mbpmstep6.png)



### Cartographie des processus basée sur les métriques: What Else To Do?
* Créer la chronologie
* Créer un résumé des métriques
* Identifier les domaines d'amélioration



### Métriques suggérées pour évaluer l'avant et l'après
* Fréquence des déploiements (plus fréquents, mieux c'est)
* Délai de mise en œuvre des nouvelles fonctionnalités : de l'idéation à la livraison (plus court, c'est mieux).
* Fréquence des échecs de changement (moins de changements, c'est mieux)
* Temps moyen de réparation (MTTR) (des temps de récupération plus courts sont préférables).



### Exercice -  TODO List Cartographie des processus basée sur les métriques (Hypothèses)

* préconisations sont :
  * Début - Fonctionnalité complète et prête à être livrée
  * Fin - Fonctionnalité déployée dans l'environnement de test
* Transfert manuel et travaux



### Exercice - TODO List Cartographie des processus basée sur les métriques  (installation)

![Swimlanes](images/vsm/mbpmstep2.png) <!-- {_class="inline-image"} -->
* Comment allez-vous appeler votre diagramme MBPM ?
* Qui/quelles sont les fonctions typiques qui travaillent dans votre processus ?



### Exercice - TODO List MBPM

![Metrics](images/vsm/mbpmstep5.png) <!-- {_class="inline-image"} -->
* PT = Le temps nécessaire pour effectuer le travail.
* LT = Temps entre le moment où le travail est disponible et celui où il atteint l'étape suivante
* % C&A = Pourcentage de temps pendant lequel les étapes en aval peuvent être achevées sans retour.



<!-- .slide: data-background-image="images/chef-background.png", class="white-style" -->
### Les pratiques DevOps utilisées dans cette section :
- [Cartographie des processus basée sur les métriques](https://openpracticelibrary.com/practice/vsm-and-mbpm/)