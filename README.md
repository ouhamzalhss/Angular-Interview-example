## <samp>Les Questions pour un entretien technique  </samp>

#### Angular framework PART 1:

- 1 .	Angular est un framework JavaScript permet le développement d'applications Web open source créé par Google. Il est utilisé pour créer des applications front end d'une seule page SPA. 

- 2 .	Quelle est la différence entre Angular et AngularJS ?

Angular (2+) | Angular Js (1)
--- | --- 
Il utilise des directives et des composants	| Il prend en charge le modèle Model-View-Controller ou MVC
Il utilise le langage TypeScript, un sur-ensemble de JavaScript qui est typé statistiquement	| Il utilise JavaScript, un langage typé dynamiquement
Angular offre un support mobile.	| AngularJS n'offre pas de support mobile
Sa structure simplifiée permet aux développeur de maintenir facilement de grandes applications	| C'est relativement moins structuré.

- 3 .	Angular CLI: Est un interface de ligne de commande. qui donne aux professionnels la possibilité pour ajouter des composants, les déployer instantanément et effectuer des tests et de nombreuses fonctions de ce type.

- 4 .	RxJS : Une implémentation JavaScript de standard ReactiveX permet de faire la programmation réactive.

- 5 .	NgRx : Est une librairie implémentant le pattern Redux en utilisant la programmation réactive basé sur RxJS, permet à une application Angular de centraliser l’état de l’application, (Redux pour Recat).

- 6 .	Package.json : Npm installe le fichier package.json lorsqu'un nouvel espace de travail est créé, il comprend un ensemble de packages (Dependencies, DevDependencies)

- 7 .	Json-server : librairie JavaScript qui permet de créer un serveur Nodejs pour générer une base de données au format JSON, utile juste lors de développement.

- 8 .	Faire communiquer les composants Angular:
  *  @Input / @Output
  *  Un service (Subject) quand vous avez une hiérarchie complexe.
  *  NgRx

- 9 .	Directives en angular : Vous pouvez modifier l'apparence, le comportement ou la disposition d'un élément DOM.
  *  Attribut Directives
  *  Structural Directives
  *  Component Directives

- 10 .	C’est quoi le data binding ?
Aider le développeur à établir la communication entre le DOM et le composant.
  *  Event binding
  *  Property binding
  *  String interpolation
  *  Two-way data binding

- 11 .	C’est quoi Templates ?
Sont écrits à l'aide de HTML qui inclut des attributs et des éléments spécifiques à Angular. Sont combinés avec les données des API web, pour offrir à l'utilisateur une vue dynamique.

- 12 .	Service en Angular: Pour partager la logique sur plusieurs components, par exemple les données des API web.

- 13 .	Promises and Observable:
  *  Promises : émettent une seule valeur à la fois, ils s'exécutent immédiatement après la création
  *  Observables : émettent une séquence de données, ne sont exécutées que lorsqu'elles sont souscrites à l'aide de la méthode de subscribe(). ils aident à effectuer les opérations comme filter , map, pipe…

- 14 .	Bootstrap, comment on peut l’ajouter à Angular:
Est un framework JavaScript, CSS et HTML on peut l’ajouter :
  *  Bootstrap CDN, 
  *  Bootstrap NPM

- 15 .	C’est quoi lifecycle hooks?
Lors de la création d'une application angulaire, il y aura des moments où nous devrons exécuter du code lors d'un événement spécifique, par exemple lorsqu'un composant est initialisé ou lorsque le composant est supprimé de l'écran. ( ngOnChanges, ngOnInit, ngDoCheck, ........ngOnDestroy)

- 16 .	ngOnInit : est une méthode de lifecycle hook exécutée par Angular pour indiquer qu'un composant a été créé.

- 17 .	Angular pipes : sont des classes avec décoration @Pipe, qui transforme l'entrée en sortie selon la logique donnée.

- 18 .	JIT (Développement): la compilation des templates se faite au niveau de navigateurs. Le mode par défaut quand on exécute "ng serve" ou "ng build". 

- 19 .	AOT . (Production): la compilation se fait en avance, donc on a deux avantages :
  *  Rendering plus rapide.
  *  Détection d’erreurs en amout. 

- 20 .	Que sont les Intercepteurs en Angular?
Les intercepteurs font partie du module @angular/common/http et sont également utilisés pour inspecter et transformer les requêtes HTTP et les réponses HTTP. 
