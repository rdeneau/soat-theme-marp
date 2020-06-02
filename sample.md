---
marp: true
theme: soat
paginate: true
html: true

---

<!-- _class: title invert -->

# TITRE DE LA PRESENTATION

## NOM DU CLIENT

### 01/04/2020

---

<!-- _class: orange speaker invert -->

# About me

## Michaël FERY

- DevOps
- Cloud
- Azure MVP
- Microsoft Certified Trainer

[![social-network](./themes/soat/pictos/twitter-round.png) _mfery](https://twitter.com/_mfery)

[![social-network](./themes/soat/pictos/linkedin-round.png) mfery](https://www.linkedin.com/in/mfery/)

---

<!-- _class: purple agenda invert lead -->

![bg right:40% h:300](./themes/soat/pictos/SOAT_pictos_formation.png)

# Agenda - Jour 1

- Le titre
- La page du formateur/speaker
- Agenda
- Les chapitres et ses variantes
- Les pages 'classiques'
- Les pause et workshop
- Fonds, notes, listes, etc.
- Les pages multi-colonnes
- Pictos
- Page de fin

`<!-- _class: purple agenda invert -->`

---

<!-- _class: green chapter invert -->

![bg-right h:300](./themes/soat/pictos/SOAT_pictos_devops.png)

# 1

## Voici une page de chapitre

### `<!-- _class: chapter invert -->`

---

<!-- _class: blue chapter invert -->

![bg-right h:300](./themes/soat/pictos/SOAT_pictos_devops.png)

# 2

## Vous pouvez changer de couleur de chapitre (red, green, blue, orange, purple)

### `<!-- _class: blue chapter invert -->`

---

# Titre

Dans une page classique sans style défini, le titre `<h2>` ou `##` est affiché en haut de page avec un fond de couleur.

```markdown
# Titre

Dans une page classique sans style défini, le titre `<h2>` ou `##` est affiché en haut de page avec un fond de couleur.
```

---

![bg center](./themes/soat/backgrounds/black-white.png)

Vous pouvez définir une image de background

`![bg center](./themes/soat/backgrounds/black-white.png)`

---

<!-- _class: green break lead invert -->

# Break

## 15 minutes

![bg 50% right](./themes/soat/pictos/SOAT_pictos_cafe.png)

```markdown
<!-- _class: green break lead invert -->

# Break

## 15 minutes

![bg 50% right](./themes/soat/pictos/SOAT_pictos_cafe.png)
```

---

<!-- _class: red workshop invert lead -->

# Workshop

## Voici une page de workshop avec une image à définir

`<!-- _class: red workshop invert lead -->`

![bg 50% right](./themes/soat/pictos/SOAT_pictos_pacMan.png)

---

# Les notes de présentateur

Pour définir des notes de présentateur, utilisez les commentaires html

`<!-- Vous retrouverez ces notes dans les versions pptx et html notamment -->`

---

# Titre

Dans une page classique sans style défini, le titre `<h2>` ou `##` est affiché en haut de page avec un fond de couleur.

```markdown
# Titre

Dans une page classique sans style défini, le titre `<h2>` ou `##` est affiché en haut de page avec un fond de couleur.
```

---

# Liste

- Les listes avec `-`
- ne sont **pas fragmentées**

* Les listes avec `*`
* sont **fragmentées** (html seulement)

1. Vous pouvez aussi
2. utiliser des listes **numérotées**

---

# Code sample

\```bash
git commit --amend
git rebase
git cherry-pick
gitmerge --squash
\```

Le code précédent afficher ce résultat

```bash
git commit --amend
git rebase
git cherry-pick
gitmerge --squash
```

---

# Images

Vous pouvez manipuler des images avec la directive `center`, `h`, `w` et `opacity`:

`![center h:400 w:400 opacity:.3](./themes/soat/backgrounds/black-white.png)`

![center h:400 w:400 opacity:.3](./themes/soat/pictos/SOAT_pictos_backEnd.png)

---

# Multi-colonnes

<div class="row">
  <div class="column" style="width: 20%">
    <p>
        L'utilisation de code html est utilisé pour définir des colonnes avec les classes <b>row</b> et <b>column</b>
    </p>
  </div>
  <div class="column" style="width: 80%;background:lightgray;">
    <p>
      &lt;div <b>class="row"</b>&gt;<br/>
      &emsp;&lt;div <b>class="column"</b> <b>style="width: 30%"</b>&gt;<br/>
      &emsp;&emsp;&lt;p&gt;
        L'utilisation de code html est utilisé pour définir des colonnes avec les classes <b>row</b> et <b>column</b>
      &lt;/p&gt;<br/>
      &emsp;&lt;/div&gt;<br/>
      &emsp;&lt;div <b>class="column"</b> <b>style="width: 70%"</b>&gt;<br/>
      &emsp;&emsp;&lt;p&gt;
        ...
      &lt;/p&gt;<br/>
      &emsp;&lt;/div&gt;
      &lt;/div&gt;
    </p>
  </div>
</div>

---

![bg left:30% 100%](./themes/soat/pictos/SOAT_pictos_phylactere1_rose.png)

> The most powerful tool we have as developers is automation.
>> [Scott Hanselman][1]

[1]: https://en.wikipedia.org/wiki/Creativity

---

# Pictos

![h:100](./themes/soat/pictos/SOAT_pictos_agilite.png) ![h:100](./themes/soat/pictos/SOAT_pictos_alEchelle.png) ![h:100](./themes/soat/pictos/SOAT_pictos_applaudir.png) ![h:100](./themes/soat/pictos/SOAT_pictos_architecture.png) ![h:100](./themes/soat/pictos/SOAT_pictos_atelier.png) ![h:100](./themes/soat/pictos/SOAT_pictos_backEnd.png) ![h:100](./themes/soat/pictos/SOAT_pictos_baseDonnees.png) ![h:100](./themes/soat/pictos/SOAT_pictos_biere.png) ![h:100](./themes/soat/pictos/SOAT_pictos_bombe.png) ![h:100](./themes/soat/pictos/SOAT_pictos_cafe.png)

![h:100](./themes/soat/pictos/SOAT_pictos_calendrier.png) ![h:100](./themes/soat/pictos/SOAT_pictos_chefEquipe.png) ![h:100](./themes/soat/pictos/SOAT_pictos_cibleCandidat.png) ![h:100](./themes/soat/pictos/SOAT_pictos_cloud.png) ![h:100](./themes/soat/pictos/SOAT_pictos_coaching.png) ![h:100](./themes/soat/pictos/SOAT_pictos_cocktail.png) ![h:100](./themes/soat/pictos/SOAT_pictos_consoleJeu.png) ![h:100](./themes/soat/pictos/SOAT_pictos_contratTravail.png) ![h:100](./themes/soat/pictos/SOAT_pictos_cooptation.png) ![h:100](./themes/soat/pictos/SOAT_pictos_data.png)

![h:100](./themes/soat/pictos/SOAT_pictos_delivery.png) ![h:100](./themes/soat/pictos/SOAT_pictos_delivery2.png) ![h:100](./themes/soat/pictos/SOAT_pictos_devops.png) ![h:100](./themes/soat/pictos/SOAT_pictos_diplome.png) ![h:100](./themes/soat/pictos/SOAT_pictos_direction.png) ![h:100](./themes/soat/pictos/SOAT_pictos_docs.png) ![h:100](./themes/soat/pictos/SOAT_pictos_Email.png) ![h:100](./themes/soat/pictos/SOAT_pictos_entretien.png) ![h:100](./themes/soat/pictos/SOAT_pictos_equipe.png) ![h:100](./themes/soat/pictos/SOAT_pictos_etudeCas.png)

![h:100](./themes/soat/pictos/SOAT_pictos_formation.png) ![h:100](./themes/soat/pictos/SOAT_pictos_frontEnd_bleu.png) ![h:100](./themes/soat/pictos/SOAT_pictos_frontEnd_jaune.png) ![h:100](./themes/soat/pictos/SOAT_pictos_frontEnd_orange.png) ![h:100](./themes/soat/pictos/SOAT_pictos_frontEnd_rose.png) ![h:100](./themes/soat/pictos/SOAT_pictos_frontEnd_vert.png) ![h:100](./themes/soat/pictos/SOAT_pictos_frontEnd_violet.png) ![h:100](./themes/soat/pictos/SOAT_pictos_idee.png) ![h:100](./themes/soat/pictos/SOAT_pictos_innovation.png) ![h:100](./themes/soat/pictos/SOAT_pictos_lieu.png)

---

<!-- _class: end invert lead-->

# Et voici le template de page de fin
