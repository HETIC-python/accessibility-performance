---
## 📚 Documentation

### Intégration des composants

- **Navbar et Footer**
  Les fragments `navbar.html` et `footer.html` peuvent être inclus dans vos pages pour garantir une navigation et un pied de page cohérents et accessibles.
  Adaptez les liens selon la structure de votre site.

- **Popup de consentement cookies**
  Pour ajouter le consentement cookies, copiez le contenu de `cookie_popup.html` juste avant la balise `</body>` de vos pages.
  Ce composant gère le focus clavier, les préférences et le stockage local du consentement.

### Personnalisation

- **Styles**
  Modifiez les fichiers CSS (`navbar.css`, `footer.css`, `main.css`, etc.) pour adapter les couleurs, polices et espacements à votre identité visuelle.
- **Contenus**
  Mettez à jour les textes, titres, descriptions et adresses e-mail dans les fichiers HTML pour refléter vos services et votre équipe.

### Bonnes pratiques

- **Accessibilité**
  - Vérifiez la présence d’attributs ARIA et de rôles sur les éléments interactifs.
  - Testez la navigation au clavier (Tab, Shift+Tab, Entrée, Échap).
  - Assurez-vous que les contrastes de couleurs sont suffisants.
- **Performance**
  - Utilisez des images optimisées et limitez les scripts tiers.
  - Profitez de la minification HTML automatique via GitHub Actions.
- **Éco-conception**
  - Privilégiez des pages légères et peu gourmandes en ressources.
  - Supprimez les éléments inutiles et limitez les animations coûteuses.

Pour toute question ou suggestion d’amélioration, n’hésitez pas à ouvrir une issue ou à proposer une pull request !
