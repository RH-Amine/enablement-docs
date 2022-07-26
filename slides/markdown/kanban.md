<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture and Practice <!-- {_class="course-title"} -->
### Kanban <!-- {_class="title-color"} -->
DO500 <!-- {_class="title-color"} -->



### Origines du Kanban
![Kanban](images/kanban/toyota-production-system.png) <!-- {_class="inline-image"} -->
* Kanban est un mot japonais qui signifie _carte que l'on peut voir_.
* 1950 Taiichi Onho a défini le [Toyota Production System] (http://www.toyota-global.com/company/vision_philosophy/toyota_production_system/origin_of_the_toyota_production_system.html) basé sur la demande des clients (Just in Time).
* 2007 David J. Anderson l'a introduit comme méthode pour le développement de logiciels.



### Pratiques Kanban

* Visualiser le workflow
* Limiter les travaux en cours
* Gérer le processus
* Rendre les politiques de processus explicites
* Boucles de feedback



### Visualiser le workflow - Tableau Kanban

* Visualiser le processus en colonnes et en cartes (Toujours visible)
* Une **colonne** est une étape du processus et une **carte** est un élément de travail.
* Toute tâche doit être dans le tableau
* Conçu par l'équipe (physique ou virtuel)

![Kanban Board](images/kanban/kanban-board.png) <!-- {_class="" style="height:350px"} -->



### Visualiser le workflow - Carte Kanban

* Représentation visuelle d'un élément de travail (demandé ou déjà en cours).
* Examen des détails en un coup d'œil
* Contient des informations précieuses sur les tâches et leur statut (par exemple : résumé, personne responsable, date limite, ...).
* Identifier les opportunités de collaboration



### Limiter les travaux en cours (WIP)

* Le nombre d'éléments de tâches sur lesquels une équipe travaille actuellement à chaque étape.
* Cadre la capacité du workflow de l'équipe à tout moment.
* Ne signifie pas qu'il faut faire moins de tâches, mais qu'il faut faire moins de tâches **en même temps**.
* Aide à identifier les goulots d'étranglement
* Empêcher un changement de contexte constant entre les tâches
* Définit un flux de travail stable et ensuite une livraison prévisible


### Gérer le flux

* Flow means the movement of work items through the process
* Manages the work but not the people
* Main goal is to create a smooth, healthy flow.
* Focus on managing the work processes and how to improve it to work faster
* Deliver value to end customers as fast as possible



### Rendre les politiques de processus explicites

* Votre processus doit être clairement défini, publié et socialisé.
* Déclarer des politiques explicites pour :
  - Quand déplacer un élément de travail d'une colonne à la suivante.
  - La priorisation
  - Comment gérer les éléments de travail urgents
* Les politiques permettront de prendre des décisions rapides sans doutes ni questions.


### Boucle de feedback

* S'assurer que nous répondons de manière adéquate aux changements potentiels.
* Définir une fréquence, une durée fixe, aller droit au but et ne jamais être inutilement long.

| Événement | Objectif |
| --- | --- |
| **Daily Standup** | Synchronisation quotidienne pour partager une compréhension commune des objectifs, coordonner l'effort de l'équipe, rendre compte de l'avancement des travaux et communiquer les problèmes et les améliorations. Commence par la colonne de droite (éléments de travail les plus proches de la fin). |
| **Révision de la livraison** | Suivre le workflow ou le processus de livraison. |
| **Revue des risques** | Vérifier, identifier et/ou atténuer les risques dans notre processus. |



###  Métriques Kanban

* **Lead Time**: Mesure le temps qu'une tâche passe dans le tableau Kanban, depuis son entrée jusqu'à sa sortie. Une mesure pour nos clients
* **Temps de cycle**:  Mesure le temps qu'une tâche passe à travers le processus, à partir du moment où la tâche a commencé.
* **Rendement**: Mesure la quantité totale de travail fourni (éléments de travail terminés).
*  Le temps de cycle, le débit et l'encours sont liés par la **[Little's Law](https://en.wikipedia.org/wiki/Little%27s_law)**

![Little's Law](images/kanban/kanban-littles-law.png)

* Soyez concentré pour **réduire le Lead Time**.



<!-- .slide: data-background-image="images/chef-background.png", class="white-style" -->
### Pratiques DevOps utilisées dans cette section :
- [Kanban](https://openpracticelibrary.com/practice/kanban/)
- [Kanban Picture](https://openpracticelibrary.com/practice/kanban-picture/)
- [Daily Standup](https://openpracticelibrary.com/practice/daily-standup/)
