# Malard Construction inc.

Page statique « site en construction » pour Malard Construction inc., entreprise de rénovation haut de gamme.

## Structure

- `index.html` : tout le site (HTML, CSS et SVG intégrés, aucune dépendance, aucune étape de build). Le contenu est en français.

## Prévisualiser en local

Ouvrir `index.html` dans un navigateur, ou servir le dossier :

```sh
python3 -m http.server 8000
```

Puis visiter <http://localhost:8000>.

## Déployer sur GitHub Pages

1. Pousser ce dépôt sur GitHub.
2. Aller dans **Settings → Pages**.
3. Sous **Build and deployment**, choisir **Deploy from a branch**, sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.
4. Le site est publié à `https://<utilisateur>.github.io/<dépôt>/`.

### Domaine personnalisé

Le fichier `CNAME` à la racine déclare le domaine `malardconstruction.com`. Il reste à configurer les enregistrements DNS selon la [documentation GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site), puis à activer **Enforce HTTPS** dans les paramètres Pages.

## Contact

<info@malardconstruction.com>
