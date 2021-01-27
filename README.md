# Comment publier votre propre site [neuron]

[neuron] est une app de prise de notes optimisée pour la publication. Utilisez ce dossier de modèles pour démarrer avec la  [publication](https://neuron.zettel.page/778816d3.html) de votre propre site neuron qui ressemblera à [un ce ces exemples][examples].

- Allez sur <https://github.com/srid/neuron-template/generate>
- Donnez un nom à votre nouveau dépôt, disons `mesnotes`
- Sélectionnez "*Include all branches*" ([pourrait être nécessaire pour que le site soit publié](https://stackoverflow.com/a/47368231/55246))
- Cliquez sur "Create repository from template"
  - Note : si vous êtes sur plan GitHub gratuit, votre dépôt devrait être public afin que GitHub le pubie.

GitHub construira maintenant le site et le servira sous : `https://<yourgithubusername>.github.io/mesnotes/`.

Pour plus d'informations, regardez la [documentation neuron][neuron] tut comme le [guide GitHub Pages](https://help.github.com/en/github/working-with-github-pages).

## Réglez les métadonnées de votre site

- Dans votre nouveau dépôt, éditez le fichier `neuron.dhall` pour régler la configuration de votre site (titre, auteur, couleur du thème) aux valeurs désirées.

## Comment éditer et ajouter des notes

En supposant que vous ayez modifié la configuration `editUrl` dans `neuron.dhall` (voir la section du dessus), vous pouvez cliquer simplement sur l'icône "edit" sur le site publié pour éditer n'importe quelle note (voir [Editing files in your repository](https://help.github.com/en/github/managing-files-in-a-repository/editing-files-in-your-repository) et [Creating new files](https://help.github.com/en/github/managing-files-in-a-repository/creating-new-files)). Sur chaque modification, votre site devrait se reconstruire.

Pour comprendre comment fonctionnent les liens, lisez [the neuron guide on Linking][linking].

Pour d'autres manières d'éditer vos notes (éditeurs, interface web), regardez le [guide neuron][create]. En particulier, [Cerveau](https://www.cerveau.app/) est le moyen le plus facile pour éditer vos notes à la volée.

Got questions? Checkout the [[faq]]. To find who else is using this template *publicly on GitHub*, [see here](https://github.com/search?o=desc&q=filename%3Aneuron.dhall&s=indexed&type=Code).

[neuron]: https://neuron.zettel.page/
[examples]: https://neuron.zettel.page/examples.html
[linking]: https://neuron.zettel.page/linking.html
[create]: https://neuron.zettel.page/create.html

