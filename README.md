# Itropika Beach Tabarka — Pack GitHub Pages

Ce dossier est prêt pour **GitHub Pages**.

## Déploiement rapide (nouveau dépôt)
1. Créez un dépôt sur GitHub (public ou privé avec Pages activé).
2. Uploadez **tous les fichiers** de ce dossier à la racine du dépôt (y compris `.nojekyll`).
3. Sur GitHub, allez dans **Settings → Pages** :
   - **Source** : sélectionnez **Deploy from a branch**.
   - **Branch** : choisissez **main** (ou `master`) et le dossier **/** (root).
4. Enregistrez : GitHub Pages publiera le site sous `https://<votre-user>.github.io/<nom-du-depot>/`.

## Notes
- `index.html` est la page d’accueil.
- `404.html` gère les URL inconnues.
- `.nojekyll` désactive Jekyll pour éviter des conflits avec des dossiers/fichiers spéciaux.
- Pied de page : *Powered by Itropika Beach Tabarka* a été ajouté à `index.html`.

## Personnalisation
- Pour un domaine perso, créez un fichier `CNAME` à la racine avec votre domaine, par ex. :
  ```
  www.exemple.com
  ```
