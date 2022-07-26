<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture and Practice <!-- {_class="course-title"} -->
### Event Storming <!-- {_class="title-color"} -->
DO500 <!-- {_class="title-color"} -->



### Event Storming
#### _Qu'est-ce que c'est ? _
* Fournit une technique reproductible et enseignable pour la modélisation :
  * Systèmes pilotés par les événements
  * Les grands systèmes de microservices
* Nécessite une surface de modélisation très, très grande.
* Nécessite beaucoup de post-it dans un arc-en-ciel de couleurs avec une légende pour leur utilisation.



### Event Storming
#### _Qu'est-ce que c'est?_
* Qui : les principales parties prenantes de l'entreprise et les techniciens
* Il y aura beaucoup de discussions, un peu de querelle, et périodiquement des débats **très** animés
* Pas de chaises !
* Attendez-vous à une journée fatigante mais amusante, qui vous permettra de réaliser de grandes choses avec les outils les plus simples.


### Event Storming
#### _D'où vient-il ?_
![Brandolini](images/eventstorming/brandolini.jpg) <!-- {_class="inline-image" width="350"} -->
Event Storming a été développé par Alberto Brandolini.
* Brandolini a une expérience des systèmes pilotés par les événements.
* Il est un membre actif de la communauté DDD (Domain-Driven Design).
* Il a commencé l'Event Storming en tant qu'invité dans l'atelier DDD de Vernon Vaughn.
* Le premier article de blog sur l'Event Storming date de 2013.



### Event Storming
#### _Pourquoi l'utilisons-nous ?_
* Modélisation très simple et accessible à tous les acteurs du métier
* Engage toutes les parties prenantes et supprime les barrières techniques :
  * Les personnes non techniques peuvent contribuer activement
  * Construit une compréhension partagée
  * Agir rapidement pour résoudre les problèmes difficiles
  * Livrer des artefacts de conception vraiment utiles




### Event Storming
#### _Artéfacts_
* **Big Picture**:  construire rapidement une compréhension partagée d'un espace de problème
* **Diagramme de processus** : modélisation des processus métier
* **Aggregate Modeling**: trouver les microservices clés, les opérations et une rétrospective. modèle d'événement
* **UI Modeling**: modéliser le flux de pages dans une application.



### Event Storming
#### _Conseils pour réussir_
* Organiser un atelier sur la vision d'ensemble
* Invitez les bonnes personnes : les parties prenantes de l'entreprise, l'informatique et l'expérience utilisateur (UX).
* Fournissez un espace de modélisation illimité avec une surface, des marqueurs et des autocollants.
* Modélisez **un secteur d'activité entier** avec des événements de domaine.



## Event Storming Diagramme



![System](images/eventstorming/system.jpg)



### Event Storming: Événements
![Events](images/eventstorming/events.jpg) <!-- {_class="inline-image"} -->
Quelque chose qui est arrivé et dont les gens se préoccupent
* Sujet --> Verbe au passé, par exemple **Article expédié**.
* Peut être programmé, par exemple **Comptes réconciliés tous les soirs**.
* Un résultat significatif d'une autre chose, par exemple **Compte verrouillé**.



### Event Storming: Événements
![Event](images/eventstorming/eventsticky.png) <!-- {_class="inline-image"} -->
D'où viennent les événements ?
* Un système
* L'écoulement du temps
* Conséquence d'un autre événement



### Event Storming: Commandes
![Command](images/eventstorming/commandsticky.png) <!-- {_class="inline-image"} -->
* Une **commande** est une **action** lancée par un **acteur**.
* Elle représente la **décision**
* Elle est généralement l'inverse de l'**événement**, par ex :
  * Acheter un billet
  * Annuler une réservation



### Event Storming: Acteurs
![Actor](images/eventstorming/actorsticky.png) <!-- {_class="inline-image"} -->
Un acteur est l'utilisateur du système
* Gardez-le flou, par exemple **Joe**.
* L'acteur prend la décision



### Event Storming: Questions
![Question](images/eventstorming/questionsticky.png) <!-- {_class="inline-image"} -->
* Points douloureux, par exemple **C'est long!**.
* Comment / Quoi / Pourquoi ?
* Points chauds
* Hypothèses



### Event Storming: Systèmes externes
![System](images/eventstorming/systemsticky.png) <!-- {_class="inline-image"} -->
* Services de tiers
* Systèmes existants



### Event Storming: Modèle de lecture
![ReadModel](images/eventstorming/readmodelsticky.png) <!-- {_class="inline-image"} -->
Les **informations** nécessaires à la prise d'une **décision**.
* Représente une implémentation
  * Procédure stockée
  * Requête
  * Projection
* Liens avec la mise en page



### Event Storming: Politiques et procédures
![PolicyProcedure](images/eventstorming/policysticky.png) <!-- {_class="inline-image"} -->
* Les mots-clés à utiliser sont **toujours** et **immédiatement**.
* Les procédures comprennent :
  * Processus automatique
  * Responsable de processus
  * Écouteur
  * "N'oubliez pas de..."
  * Accord
  * Règles
  * Habitude
* Par exemple :

  Remboursement demandé > Politique de remboursement > Délivrer un reçu



### Event Storming: Aggregate
![Aggregate](images/eventstorming/aggsticky.png) <!-- {_class="inline-image"} -->
Partie du système qui **reçoit** la **commande** et décide d' **exécuter**
l'**événement**.
* Généralement un nom, par exemple **Article**.
* L'agrégat est la **machine d'état**.
* Servent de lieu pour regrouper logiquement les commandes une fois que toutes les sources d'événements sont identifiées.



![System](images/eventstorming/system.jpg)



### Event Storming:  Principaux points à retenir
* Construire une compréhension partagée d'un problème spécifique
* Modélisation des processus métier
* Modélisation agrégée pour trouver les microservices clés et le modèle d'événement.
* Modélisation du flux de pages dans une application
* Aligne les parties prenantes et les groupes informatiques



### Exercice
### Event Storm pour la gestion d'une ToDo Liste
![Key](images/eventstorming/key.png) <!-- {_class="inline-image"} -->
* In your teams, create example event storm for the Current state of the To Do List
Management application. Cover the following things:
  1. Add the new Events
  * Add the new Commands, Users and Read Models
  * Are there new Systems or Aggregates?
* Reflect on your Impact Map deliverables and enhance it with some new functionality e.g
  1. Sharing lists between users
  2. Integration with other vendors or providers



<!-- .slide: data-background-image="images/chef-background.png", class="white-style" -->
### DevOps practices used in this section:
- [Event Storming](https://openpracticelibrary.com/practice/event-storming/)
