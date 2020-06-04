![CSS Generation](https://github.com/michaelfery/soat-theme-marp/workflows/CSS%20Generation/badge.svg?branch=master)

# Thèmes

## Gestion des thèmes avec MARP

Marp possède des thèmes par défaut.
Le thème SOAT se base sur le thème **Gaia** et ajoute des spécificités de styles.

```css
@import-theme 'gaia';
```

L'utilisation des thèmes se fait en ajoutant ces lignes au début du fichier markdown de slides :

```markdown
---
marp: true
theme: soat
---
```

## CSS Génération

Le thème SOAT est décrit dans le fichier `./theme/soat.css` qui n'est pas versionné.
En effet, ce fichier est généré depuis le fichier `./theme/soat.scss`.

### Génération statique

Vous pouvez donc générer ce fichier de manière statique grâce à la commande suivante:

```bash
cd themes
node-sass .\soat.scss
```

ou via la commande npm:

```bash
cd themes
npm run -s build
```

### Génération dynamique

Vous pouvez également générer le fichier de manière dynamique grâce au paramêtre `--watch` quand vous travaillez sur le thème :

```bash
cd themes
node-sass --watch .\soat.scss
```

Grâce à cette commande, chaque modification du fichier `soat.scss` génerera une nouvelle version du fichier `soat.css`.

## Sample

Pour tester le theme, vous pouvez générer le deck de slides via le fichier `sample.md` et la commande suivante:

```bash
npx @marp-team/marp-cli sample.md --pdf --allow-local-files --theme themes/soat.css
```

Vous pouvez également utiliser la commande suivante:

```bash
npm run -s test
```

Vous aurez donc un fichier pdf généré avec le thème.

## VS Code

Vous pouvez avoir un pré-rendu live de votre deck dans VSCode en utilisant l'extension [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).

Vous pouvez alors utiliser le thème **SOAT** automatiquement grâce au fichier `.vscode/settings.json` dont le contenu indique l'emplacement du fichier de style.

```json
{
  "markdown.marp.themes": [
    "./themes/soat.css"
  ]
}
```
