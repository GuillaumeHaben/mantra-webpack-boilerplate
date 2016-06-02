# Installation

### Node / NPM
Ce projet a été testé avec node@6.2 / npm@3.

Il est conseillé d’installer nvm qui permet d’avoir toutes les versions de node voulues sur une même machine. Voici le lien : [NVM](https://github.com/creationix/nvm)

### Configuration Gitlab

* Se créer un compte sur Gitlab.com.
* Demander à Alex, Julien ou Théo de t'ajouter au projet assipe.
* Créer une clé ssh via la commande ssh-keygen.
* Ajouter la clé sur https://gitlab.com/profile/keys

### Lancer le projet

```bash
git clone git@gitlab.com:assipe/assipe.git
cd assipe
npm install
meteor
```


# A bien comprendre

*	[ES2015 : nouvelle spécification javascript](https://babeljs.io/docs/learn-es2015/)
* React
* Meteor
* [Mantra](https://kadirahq.github.io/mantra)  : Principes d’architecture pour Meteor et React
*	Hot reloading : permet de recharger tes composants React sans recharger toute la page quand tu fais une modification de code. Par contre faut suivre cette prérogative pour que ça marche : https://github.com/mantrajs/kickstart-mantrajs-webpack#hot-module-reload-hmr


# Librairies utilisées
*	[React-bootstrap](https://react-bootstrap.github.io/) : pour utiliser les composants bootstrap avec react
* 	[Formsy-react](https://github.com/twisty/formsy-react-components) pour gérer les formulaires
* Flow router : pour gérer les différentes routes

# Outils utiles
* Perso j’utilise Atom comme éditeur mais c’est comme tu veux évidemment
* https://github.com/mantrajs/mantra-cli permet de générer des fichiers de type Mantra : tu te places dans le dossier src/ et tu executes les commandes que tu veux.

