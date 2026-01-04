# Une liste de tâches

Dans cet exercice, vous devez créer une application web pour gérer une liste de tâches à faire (to-do list) en utilisant le framework Vue 3.

## Modalités
* Vous devez réaliser l'exercice par groupes de deux ou trois étudiants.

## Consignes
Vous devez créer une application de gestion de liste de tâches à l'exemple de [cette application](https://polytechlyon.github.io/js-todo-list-examples/step1/).

Vous réaliserez votre application à partir de ce dépôt.

L'application doit être réalisée en utilisant Vue et Vue Router, sans autre bibliothèque externe.
L'utilisation d'un mécanisme de stockage persistant tel que `localStorage`, `sessionStorage` ou IndexedDB est interdite.

Au-delà de son bon fonctionnement, votre code doit respecter les bonnes pratiques du génie logiciel, telles que la modularité, la lisibilité et l'extensibilité.

## Fonctionnalités

Vous devez animer l'application à l'aide du framework Vue 3 pour permettre les fonctionnalités suivantes.

* La page d'accueil doit contenir un panneau permettant l'ajout d'un nouvel item.
  L'item sera ajouté en bas de la liste.

* La liste de tâches doit être affichée en permanence sur la page.
  Chaque item doit être accompagné de deux boutons : suppression et modification.

* Lorsqu'on actionne le bouton de suppression, l'item correspondant sera supprimé de la liste.

* L'appui sur le bouton de modification active le mode de modification.
  Un panneau sera affiché, permettant de modifier le texte de l'item grâce à un champ de saisie.
  On peut soit confirmer, soit annuler la modification grâce à deux boutons.
  Dans les deux cas, le mode de modification sera désactivé.
  Lorsque le mode de modification est actif, le panneau de création doit être masqué.

La liste ne sera pas sauvegardée entre les rafraîchissements de page, ni lorsque la page est fermée puis visitée à nouveau.

## Extensions

### Gestion des tâches terminées
À l'exemple de [cette application](https://polytechlyon.github.io/js-todo-list-examples/step3/),
vous devez modifier le code pour ajouter à chaque item de la liste une case à cocher qui indique si la tâche en question est accomplie.

### Page d'impression
À l'exemple de [cette application](https://polytechlyon.github.io/js-todo-list-examples/step4/),
vous devez ajouter une page d'impression à votre application qui affiche la liste des tâches en mode lecture seule.
La page affiche un récapitulatif avec le nombre total de tâches ainsi que le nombre de tâches qui ne sont pas encore terminées.
Elle affiche aussi la liste de toutes les tâches, les tâches terminées apparaissant barrées.

Cette page doit être accessible, par un lien, depuis la page principale.
La page principale doit, elle aussi, être accessible depuis la page d'impression.

Pensez à utiliser Vue Router pour réaliser cette étape. La navigation ne doit pas provoquer de rechargement complet de la page.

## Outils
### Pour coder
Pour cet exercice, vous aurez besoin d'un éditeur de texte et d'un navigateur web. Vous devez aussi avoir `npm` installé et fonctionnel.

Vous pouvez utiliser un environnement de développement intégré (IDE), comme VS Code ou WebStorm.

### Pour tester
L'application doit s'afficher dans un navigateur web. Vous pouvez tester le bon fonctionnement de votre application en lançant un serveur de développement local avec `npm` et `vite`.
