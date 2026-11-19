# IT 130 – Introduction aux Technologies Web

Dépôt des travaux pratiques de l'UE **IT 130** (IPNET).

**Auteur :** GNANSA Dorian
**Site publié :** https://dorian21-collab.github.io/ipnet-it130/

## Description

Ce projet est un petit blog personnel construit au fil des semaines avec HTML5.
Chaque semaine ajoute une nouvelle page et de nouvelles notions.

## Contenu du dépôt

| Fichier        | Description                                   | Semaine |
|----------------|-----------------------------------------------|---------|
| `index.html`   | Page d'accueil                                | 1       |
| `blog.html`    | Page de blog                                  | 2       |
| `contact.html` | Page de contact (formulaire, tableaux, médias) | 3       |
| `README.md`    | Description du projet                         | 3       |

## Page de contact (Semaine 3)

La page `contact.html` contient :

- **Un formulaire HTML5 accessible** : champs `text`, `email`, `tel`, `select`, `textarea` et `checkbox`, chacun associé à un `<label>`, regroupés avec `<fieldset>` et `<legend>`.
- **La validation native** : attributs `required`, `minlength`, `maxlength` et `pattern`.
- **Deux tableaux structurés** : « Mes disponibilités » et « Mes compétences », avec `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` et `<th scope>`.
- **Des médias intégrés** : une vidéo (`<video>`) et un fichier audio (`<audio>`) avec formats multiples et texte de repli.

## Accessibilité

- Un seul `<h1>` par page et titres hiérarchisés.
- Labels associés à tous les champs de formulaire.
- Tableaux avec en-têtes `scope="col"` et `scope="row"`.
- Texte de repli pour la vidéo et l'audio.

## Utiliser le projet en local

```bash
git clone https://github.com/dorian21-collab/ipnet-it130.git
cd ipnet-it130
```

Ouvrir ensuite `index.html` dans un navigateur (ou avec l'extension Live Server de VS Code).

## Technologies

- HTML5
- Git et GitHub
- GitHub Pages
- VS Code
