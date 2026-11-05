# Site d'Ambrelune

Pages publiques de l'appli, pour la fiche App Store (iPhone et Mac).

| Page | Fichier | À utiliser pour |
|---|---|---|
| Accueil | `index.html` | URL marketing (facultatif) |
| Assistance | `assistance.html` | URL d'assistance (obligatoire) |
| Confidentialité | `confidentialite.html` | URL de politique de confidentialité (obligatoire) |

Site statique, sans script ni dépendance : GitHub Pages le sert tel quel
(`.nojekyll` désactive le traitement Jekyll).

## Publier sur GitHub Pages

1. Créer un dépôt **public** `ambrelune-site` sur le compte `Remy901`.
2. Envoyer les fichiers :
   ```
   git remote add origin https://github.com/Remy901/ambrelune-site.git
   git push -u origin main
   ```
3. Sur GitHub : Settings > Pages > Source « Deploy from a branch », branche `main`, dossier `/ (root)`, Save.
4. Une ou deux minutes plus tard :
   - https://remy901.github.io/ambrelune-site/
   - https://remy901.github.io/ambrelune-site/assistance.html
   - https://remy901.github.io/ambrelune-site/confidentialite.html

Chaque `git push` sur `main` met ensuite le site à jour automatiquement.
