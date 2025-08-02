# Mon Blog Professionnel

Un blog professionnel moderne et responsive créé pour partager mes expériences, compétences et réalisations dans le domaine du développement informatique.

## 🚀 Fonctionnalités

- **Design moderne et responsive** : Interface utilisateur élégante qui s'adapte à tous les appareils
- **Navigation intuitive** : Menu de navigation clair et accessible
- **Pages structurées** : Organisation logique du contenu selon les exigences académiques
- **Animations fluides** : Transitions et animations pour une expérience utilisateur optimale
- **Optimisé SEO** : Balises meta et structure HTML sémantique
- **Compatible GitHub Pages** : Prêt pour le déploiement

## 📁 Structure du projet

```
blog/
├── index.html                 # Page d'accueil
├── assets/
│   ├── css/
│   │   └── style.css         # Styles principaux
│   └── js/
│       └── script.js         # JavaScript
├── pages/
│   ├── articles.html         # Liste des articles
│   └── articles/
│       └── nba-data-viewer.html  # Article sur le projet NBA
└── README.md                 # Ce fichier
```

## 🎯 Pages principales

### 1. Page d'accueil (`index.html`)
- Présentation personnelle
- Aperçu des derniers articles
- Compétences techniques en preview
- Statistiques et réalisations

### 2. Articles (`pages/articles.html`)
- Liste complète des articles avec filtres
- Catégories : Projet
- Système de filtrage interactif
- Article détaillé sur le projet NBA Data Viewer

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles modernes avec CSS Grid et Flexbox
- **JavaScript** : Interactions et animations
- **Font Awesome** : Icônes
- **Google Fonts** : Typographie (Inter)

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Préparer le repository

1. Créez un nouveau repository sur GitHub
2. Nommez-le `votre-username.github.io` (remplacez par votre nom d'utilisateur)
3. Clonez le repository en local :
```bash
git clone https://github.com/votre-username/votre-username.github.io.git
```

### Étape 2 : Ajouter les fichiers

1. Copiez tous les fichiers du blog dans le dossier cloné
2. Ajoutez les fichiers au repository :
```bash
git add .
git commit -m "Initial commit: Blog professionnel"
git push origin main
```

### Étape 3 : Activer GitHub Pages

1. Allez dans les paramètres du repository (Settings)
2. Descendez jusqu'à la section "Pages"
3. Dans "Source", sélectionnez "Deploy from a branch"
4. Choisissez la branche "main"
5. Cliquez sur "Save"

### Étape 4 : Accéder au blog

Votre blog sera accessible à l'adresse : `https://votre-username.github.io`

## 📝 Personnalisation

### Informations personnelles

Modifiez les fichiers suivants pour personnaliser le blog :

1. **Nom et titre** : `index.html` (ligne 8 et 58)
2. **Informations de contact** : `pages/contact.html` (lignes 45, 55, 65)
3. **Compétences** : `pages/competences.html` (ajustez les pourcentages)
4. **Projets** : `pages/competences.html` (section projets)

### Couleurs et style

Les couleurs principales sont définies dans `assets/css/style.css` :

```css
:root {
    --primary-color: #2563eb;    /* Bleu principal */
    --primary-dark: #1d4ed8;     /* Bleu foncé */
    --accent-color: #f59e0b;     /* Orange accent */
    --text-primary: #1e293b;     /* Texte principal */
    --text-secondary: #64748b;   /* Texte secondaire */
}
```

### Ajouter de nouveaux articles

1. Créez un nouveau fichier HTML dans `pages/articles/`
2. Utilisez la structure de `bilan-stage.html` comme modèle
3. Ajoutez l'article à la liste dans `pages/articles.html`

## 📋 Contenu requis pour la validation

Le blog est structuré pour répondre aux exigences académiques :

### ✅ Éléments inclus

- **Article détaillé sur le projet** : Analyse complète du développement NBA Data Viewer
- **Technologies utilisées** : PHP, SQLite, API REST, Composer
- **Compétences démontrées** : Développement web, intégration d'API, gestion de base de données
- **Documentation complète** : README détaillé et instructions d'installation

### 📝 Article créé

✅ **Développement d'une application NBA Data Viewer** (`nba-data-viewer.html`)
- Analyse complète du projet basé sur le repository GitHub
- Détail des technologies utilisées (PHP, SQLite, API balldontlie)
- Compétences développées et défis rencontrés
- Perspectives d'amélioration et conclusion

## 🔧 Maintenance

### Mise à jour du contenu

1. Modifiez les fichiers HTML directement
2. Committez et poussez les changements :
```bash
git add .
git commit -m "Mise à jour du contenu"
git push origin main
```

### Ajout d'images

1. Créez un dossier `assets/images/`
2. Ajoutez vos images
3. Utilisez des chemins relatifs : `../assets/images/votre-image.jpg`

## 📱 Responsive Design

Le blog est entièrement responsive et s'adapte à :
- Ordinateurs de bureau
- Tablettes
- Smartphones

## 🎨 Fonctionnalités avancées

- **Navigation mobile** : Menu hamburger responsive
- **Animations** : Transitions fluides et animations au scroll
- **Filtrage d'articles** : Système de filtres interactif
- **Formulaire de contact** : Validation et gestion des soumissions
- **FAQ accordéon** : Questions/réponses interactives

## 📞 Support

Pour toute question ou problème :
- Vérifiez que tous les fichiers sont bien présents
- Assurez-vous que les chemins des liens sont corrects
- Testez en local avant de déployer

## 📄 Licence

Ce projet est créé pour un usage personnel et académique.

---

**Bon blog !** 🚀