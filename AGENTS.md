# Site public — guillaumerollando.github.io

Pages publiques des jeux et applis de Guillaume : présentation et **pages légales** exigées par les stores
(politique de confidentialité, conditions d'utilisation). Publié par **GitHub Pages** (Jekyll intégré) à
chaque `git push` sur `main` : https://guillaumerollando.github.io/

⚠️ Dépôt **public** : rien de privé ici (pas de code de jeu, pas de secret, pas de note interne).

## Organisation
- `_config.yml` : éditeur, adresse de contact, pays — **une seule source**, reprise par toutes les pages (`{{ site.contact }}`)
- `_layouts/default.html` + `assets/style.css` : la mise en page commune (clair / sombre, lisible sur téléphone)
- `index.md` : la liste des jeux et applis
- `<appli>/` : un dossier par appli : `index.md` (présentation), `confidentialite.md` + `privacy.md`, `conditions.md` + `terms.md`
- URL sans extension : `/<appli>/confidentialite`, `/<appli>/privacy` (c'est celle qu'on donne à la Play Console)

## Ajouter une appli
Suivre le skill `pages-legales` de l'Atelier (`~/Dev/Atelier/skills/pages-legales/SKILL.md`) : partir des modèles,
les remplir d'après ce que fait **vraiment** l'appli (lire son code), ajouter une ligne dans `index.md`.

## Règles
- Toute modification d'une page légale = changer sa date « Dernière mise à jour » (FR et EN ensemble)
- Français et anglais toujours tenus en parallèle (mêmes sections, même contenu)
- Une promesse faite dans une page (bouton « Confidentialité », « Restaurer mes achats »…) doit exister dans l'appli
