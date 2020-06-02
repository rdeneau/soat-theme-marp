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

## VS Code

Le thème **soat** est disponible grâce au fichier `.vscode/settings.json` dont le contenu indique l'emplacement du fichier de style.

```json
{
  "markdown.marp.themes": [
    "./themes/soat.css"
  ]
}
```

:tip: Vous pouvez ajouter plusieurs styles et/ou remplacer le path du fichier css par une url si vous souhaitez avoir un fichier de style distant.

## CSS Génération

Le thème SOAT est décrit dans le fichier `./theme/soat.css` qui n'est pas versionné.
En effet, ce fichier est généré depuis le fichier `./theme/soat.scss`.

### Génération statique

Vous pouvez donc générer ce fichier de manière statique grâce à la commande suivante:

```bash
cd themes
node-sass .\soat.scss
```

### Génération dynamique

Vous pouvez également générer le fichier de manière dynamique grâce au paramêtre `--watch` quand vous travaillez sur le thème :

```bash
cd themes
node-sass --watch .\soat.scss
```

Grâce à cette commande, chaque modification du fichier `soat.scss` génerera une nouvelle version du fichier `soat.css`.
