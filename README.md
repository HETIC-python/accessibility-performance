# Projet Web Accessibilité & Performance

> **Une démo en ligne est disponible ici : [https://hetic-python.github.io/accessibility-performance](https://hetic-python.github.io/accessibility-performance)  
> Découvrez le rendu final, testez la navigation accessible, le responsive et les optimisations de performance en conditions réelles !**

Bienvenue dans le projet **Accessibilité & Performance** ! Ce dépôt propose un modèle de site web moderne, accessible et performant, idéal pour les agences ou développeurs souhaitant présenter leurs services, tarifs et portfolio avec un fort accent sur l’accessibilité web et l’éco-conception.

...


## L´Équipe
- **Jiad Abdul**
- **Paul Charbel**
- **Faithgot glin-dayi**
- **Hugo cieplucha**
- **Ahmat Rouchad**
- **Siaka doumbia**

## 🌟 Présentation du projet

Ce projet met en avant les bonnes pratiques en matière de :

- **Accessibilité Web (a11y) :** HTML sémantique, attributs ARIA, navigation clavier, dialogues accessibles.
- **Performance :** CSS optimisé, JavaScript minimal, minification automatique du HTML.
- **Design Responsive :** Mise en page mobile-first et composants adaptatifs.
- **Éco-conception :** Assets légers et code efficace pour réduire l’impact environnemental.

---

## 📁 Structure du projet

```
accessibility-performance/
│
├── about.html            # Page À propos
├── about.css             # Styles de la page À propos
├── cookie_popup.html     # Popup de consentement cookies accessible (à intégrer)
├── footer.css            # Styles du pied de page
├── footer.html           # Fragment HTML du pied de page
├── index.html            # Page d’accueil (Landing page)
├── landingPage.html      # (Réservé pour une future landing page)
├── main.css              # Styles généraux et landing page
├── navbar.css            # Styles de la barre de navigation
├── navbar.html           # Fragment HTML de la navbar
├── pricing.html          # Page Tarifs
├── .gitignore            # Fichier gitignore
├── README.md             # Ce fichier
│
└── .github/
    └── workflows/
        └── minify-html.yml  # GitHub Action pour la minification HTML
```

---

## 🚀 Fonctionnalités

- **Navigation accessible :** Navbar compatible clavier avec labels ARIA et menu hamburger pour mobile.
- **Pied de page accessible :** Liens utilitaires avec focus visible.
- **Popup cookies :** Dialogue de consentement entièrement accessible et personnalisable.
- **Tableau des tarifs :** Plans tarifaires clairs et sémantiques avec ARIA.
- **Mise en page responsive :** Adaptation à tous les écrans.
- **Optimisation des performances :** Minification HTML automatisée via GitHub Actions.

---

## 🛠️ Utilisation

### 1. **Cloner le dépôt**

```sh
git clone https://github.com/votre-utilisateur/accessibility-performance.git
cd accessibility-performance
```

### 2. **Ouvrir en local**

Ouvrez n’importe quel fichier `.html` dans votre navigateur. Aucun build n’est nécessaire.

### 3. **Personnaliser le contenu**

- Modifiez les fichiers HTML pour adapter les informations, services et contacts de votre agence.
- Ajustez les fichiers CSS pour votre charte graphique.

### 4. **Intégration du popup cookies**

Pour ajouter le popup de consentement, intégrez le contenu de `cookie_popup.html` à la fin du `<body>` de vos pages.

### 5. **Minification HTML automatisée**

À chaque push sur la branche `main`, le workflow GitHub Action `.github/workflows/minify-html.yml` :
- Minifie tous les fichiers `.html` avec `html-minifier-terser`
- Commit et push les fichiers minifiés dans le dépôt

---

## ♿ Points forts accessibilité

- **Liens d’accès rapide** pour les utilisateurs clavier
- **Labels et rôles ARIA** pour la navigation et les dialogues
- **Gestion du focus** dans les modales et menus
- **Contraste des couleurs** et indicateurs de focus visibles

## Ce qu'on a du abandonner :

- **Animations d’arrière-plan**, 🌪️ Distrayantes, perturbent les personnes neuroatypiques (autisme, TDAH), peuvent provoquer malaise ou nausée (motion sickness).
- **Transitions rapides ou brutales** ⚡ Peu confortables à suivre, notamment pour les personnes avec des troubles de l’attention ou de la perception.
- **Usage excessif de couleurs pour transmettre de l’information** 🎨 Exemple : “les erreurs sont rouges, les réussites vertes”, illisible pour les daltoniens si non doublé de texte ou d’icône.


## Objectifs futurs

- [ ] Optimiser le temps de chargement initial :
- [ ] Ajout d´images (WebP, compression)
- [ ] Utilisation de `lazy-loading` pour les images et les composants lourds
- [ ] Activer la mise en cache statique (Cache-Control, ETag)
- [ ] Minifier les fichiers CSS/JS en plus du HTML
- [ ] Permettre **l’ajustement de la taille du texte** :
- [ ] Prévoir un système de **traduction multilingue** (i18n) FR / EN au minimum

---

## 📦 Dépendances

- Aucune dépendance externe requise pour l’utilisation du site.
- GitHub Actions utilise `html-minifier-terser` pour la minification.

---

## 📄 Licence

Ce projet est open-source et disponible sous licence [MIT](LICENSE).

---

## ✨ Crédits

Créé par une équipe de développeurs web passionnés par l’accessibilité et la performance.

---

## 📬 Contact

Pour toute question ou collaboration : [contact@example.com](mailto:contact@example.com)

---

**Bon développement ! Rendons le web accessible à tous.**
