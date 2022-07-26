<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture and Practice <!-- {_class="course-title"} -->
### Event Storming <!-- {_class="title-color"} -->
DO500 <!-- {_class="title-color"} -->



### Event Storming
#### _Qu'est-ce que c'est ? _
* Fournit une technique reproductible et enseignable pour la mod&eacute;lisation :
  * Syst&egrave;mes pilot&eacute;s par les &eacute;v&eacute;nements
  * Les grands syst&egrave;mes de microservices
* N&eacute;cessite une surface de mod&eacute;lisation tr&egrave;s, tr&egrave;s grande.
* N&eacute;cessite beaucoup de post-it dans un arc-en-ciel de couleurs avec une l&eacute;gende pour leur utilisation.



### Event Storming
#### _Qu'est-ce que c'est?_
* Qui : les principales parties prenantes de l'entreprise et les techniciens
* Il y aura beaucoup de discussions, un peu de querelle, et p&eacute;riodiquement des d&eacute;bats **tr&egrave;s** anim&eacute;s
* Pas de chaises !
* Attendez-vous &agrave; une journ&eacute;e fatigante mais amusante, qui vous permettra de r&eacute;aliser de grandes choses avec les outils les plus simples.


### Event Storming
#### _D'o&ugrave; vient-il ?_
![Brandolini](images/eventstorming/brandolini.jpg) <!-- {_class="inline-image" width="350"} -->
Event Storming a &eacute;t&eacute; d&eacute;velopp&eacute; par Alberto Brandolini.
* Brandolini a une exp&eacute;rience des syst&egrave;mes pilot&eacute;s par les &eacute;v&eacute;nements.
* Il est un membre actif de la communaut&eacute; DDD (Domain-Driven Design).
* Il a commenc&eacute; l'Event Storming en tant qu'invit&eacute; dans l'atelier DDD de Vernon Vaughn.
* Le premier article de blog sur l'Event Storming date de 2013.



### Event Storming
#### _Pourquoi l'utilisons-nous ?_
* Mod&eacute;lisation tr&egrave;s simple et accessible &agrave; tous les acteurs du m&eacute;tier
* Engage toutes les parties prenantes et supprime les barri&egrave;res techniques :
  * Les personnes non techniques peuvent contribuer activement
  * Construit une compr&eacute;hension partag&eacute;e
  * Agir rapidement pour r&eacute;soudre les probl&egrave;mes difficiles
  * Livrer des artefacts de conception vraiment utiles




### Event Storming
#### _Art&eacute;facts_
* **Big Picture**:  construire rapidement une compr&eacute;hension partag&eacute;e d'un espace de probl&egrave;me
* **Diagramme de processus** : mod&eacute;lisation des processus m&eacute;tier
* **Aggregate Modeling**: trouver les microservices cl&eacute;s, les op&eacute;rations et une r&eacute;trospective. mod&egrave;le d'&eacute;v&eacute;nement
* **UI Modeling**: mod&eacute;liser le flux de pages dans une application.



### Event Storming
#### _Conseils pour r&eacute;ussir_
* Organiser un atelier sur la vision d'ensemble
* Invitez les bonnes personnes : les parties prenantes de l'entreprise, l'informatique et l'exp&eacute;rience utilisateur (UX).
* Fournissez un espace de mod&eacute;lisation illimit&eacute; avec une surface, des marqueurs et des autocollants.
* Mod&eacute;lisez **un secteur d'activit&eacute; entier** avec des &eacute;v&eacute;nements de domaine.



## Event Storming Diagramme



![System](images/eventstorming/system.jpg)



### Event Storming: &eacute;v&eacute;nements
![Events](images/eventstorming/events.jpg) <!-- {_class="inline-image"} -->
Quelque chose qui est arriv&eacute; et dont les gens se pr&eacute;occupent
* Sujet --> Verbe au pass&eacute;, par exemple **Article exp&eacute;di&eacute;**.
* Peut &ecirc;tre programm&eacute;, par exemple **Comptes r&eacute;concili&eacute;s tous les soirs**.
* Un r&eacute;sultat significatif d'une autre chose, par exemple **Compte verrouill&eacute;**.



### Event Storming: &eacute;v&eacute;nements
![Event](images/eventstorming/eventsticky.png) <!-- {_class="inline-image"} -->
D'o&ugrave; viennent les &eacute;v&eacute;nements ?
* Un syst&egrave;me
* L'&eacute;coulement du temps
* Cons&eacute;quence d'un autre &eacute;v&eacute;nement



### Event Storming: Commandes
![Command](images/eventstorming/commandsticky.png) <!-- {_class="inline-image"} -->
* Une **commande** est une **action** lanc&eacute;e par un **acteur**.
* Elle repr&eacute;sente la **d&eacute;cision**
* Elle est g&eacute;n&eacute;ralement l'inverse de l'**&eacute;v&eacute;nement**, par ex :
  * Acheter un billet
  * Annuler une r&eacute;servation



### Event Storming: Acteurs
![Actor](images/eventstorming/actorsticky.png) <!-- {_class="inline-image"} -->
Un acteur est l'utilisateur du syst&egrave;me
* Gardez-le flou, par exemple **Joe**.
* L'acteur prend la d&eacute;cision



### Event Storming: Questions
![Question](images/eventstorming/questionsticky.png) <!-- {_class="inline-image"} -->
* Points douloureux, par exemple **C'est long!**.
* Comment / Quoi / Pourquoi ?
* Points chauds
* Hypoth&egrave;ses



### Event Storming: Syst&egrave;mes externes
![System](images/eventstorming/systemsticky.png) <!-- {_class="inline-image"} -->
* Services de tiers
* Syst&egrave;mes existants



### Event Storming: Mod&egrave;le de lecture
![ReadModel](images/eventstorming/readmodelsticky.png) <!-- {_class="inline-image"} -->
Les **informations** n&eacute;cessaires &agrave; la prise d'une **d&eacute;cision**.
* Repr&eacute;sente une impl&eacute;mentation
  * Proc&eacute;dure stock&eacute;e
  * Requ&ecirc;te
  * Projection
* Liens avec la mise en page



### Event Storming: Politiques et proc&eacute;dures
![PolicyProcedure](images/eventstorming/policysticky.png) <!-- {_class="inline-image"} -->
* Les mots-cl&eacute;s &agrave; utiliser sont **toujours** et **imm&eacute;diatement**.
* Les proc&eacute;dures comprennent :
  * Processus automatique
  * Responsable de processus
  * &eacute;couteur
  * "N'oubliez pas de..."
  * Accord
  * R&egrave;gles
  * Habitude
* Par exemple :

  Remboursement demand&eacute; > Politique de remboursement > D&eacute;livrer un re&ccedil;u



### Event Storming: Aggregate
![Aggregate](images/eventstorming/aggsticky.png) <!-- {_class="inline-image"} -->
Partie du syst&egrave;me qui **re&ccedil;oit** la **commande** et d&eacute;cide d' **ex&eacute;cuter**
l'**&eacute;v&eacute;nement**.
* G&eacute;n&eacute;ralement un nom, par exemple **Article**.
* L'agr&eacute;gat est la **machine d'&eacute;tat**.
* Servent de lieu pour regrouper logiquement les commandes une fois que toutes les sources d'&eacute;v&eacute;nements sont identifi&eacute;es.



![System](images/eventstorming/system.jpg)



### Event Storming:  Principaux points &agrave; retenir
* Construire une compr&eacute;hension partag&eacute;e d'un probl&egrave;me sp&eacute;cifique
* Mod&eacute;lisation des processus m&eacute;tier
* Mod&eacute;lisation agr&eacute;g&eacute;e pour trouver les microservices cl&eacute;s et le mod&egrave;le d'&eacute;v&eacute;nement.
* Mod&eacute;lisation du flux de pages dans une application
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
