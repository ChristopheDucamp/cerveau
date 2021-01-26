# Comment publier votre propre site [neuron]

[neuron] est une app de prise de notes optimisée pour la publication. Utilisez ce dossier de modèles pour démarrer avec la  [publication](https://neuron.zettel.page/778816d3.html) de votre propre site neuron qui ressemblera à [un ce ces][examples].

- Allez sur <https://github.com/srid/neuron-template/generate>
- Donnez un nom à votre nouveau dépôt, disons `mesnotes`
- Sélectionnez "*Include all branches*" ([pourrait être nécessaire pour que le site soit publié](https://stackoverflow.com/a/47368231/55246))
- Cliquez sur "Create repository from template"
  - Note : si vous êtes sur plan GitHub gratuit, votre dépôt devrait être public afin que GitHub le pubie.

GitHub construira maintenant le site et le servira sous : `https://<yourgithubusername>.github.io/mesnotes/`.

For more information, see [neuron documentation][neuron] as well as the [GitHub Pages guide](https://help.github.com/en/github/working-with-github-pages).

## Set your site metadata

- In your new repository, edit the `neuron.dhall` file to set your site configuration (such as title, author, color theme) to suitable values.

## How to edit and add notes

Assuming you have changed the `editUrl` configuration in `neuron.dhall` (see the above section), you can simply click the "edit" icon on the published site to edit any note (see [Editing files in your repository](https://help.github.com/en/github/managing-files-in-a-repository/editing-files-in-your-repository) and [Creating new files](https://help.github.com/en/github/managing-files-in-a-repository/creating-new-files)). On every change, your site should eventually rebuild.

To understand how linking works, read [the neuron guide on Linking][linking].

For other ways to edit your notes (editors, web interface), see the [neuron guide][create]. In particular, [Cerveau](https://www.cerveau.app/) is the easiest way to edit your notes on the go.

Got questions? Checkout the [[faq]]. To find who else is using this template *publicly on GitHub*, [see here](https://github.com/search?o=desc&q=filename%3Aneuron.dhall&s=indexed&type=Code).

[neuron]: https://neuron.zettel.page/
[examples]: https://neuron.zettel.page/examples.html
[linking]: https://neuron.zettel.page/linking.html
[create]: https://neuron.zettel.page/create.html

