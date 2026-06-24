# Site Saraaf' – Portfolio UGC

## Structure des fichiers

```
saraaf_site/
├── index.html              ← Page d'accueil (portfolio)
├── portfolio.html          ← Portfolio complet
├── mediakit.html           ← Media Kit (version web)
├── assets/
│   ├── images/             ← Toutes les photos
│   └── videos/             ← Toutes les vidéos
└── README.md
```

## Déploiement sur GitHub Pages

### 1. Créer un compte GitHub (si pas déjà fait)
→ https://github.com

### 2. Créer un nouveau dépôt
- Cliquer sur **New repository**
- Nom : `saraaf-portfolio` (ou `ton-pseudo.github.io` pour une URL propre)
- Visibilité : **Public** (obligatoire pour GitHub Pages gratuit)
- Cliquer **Create repository**

### 3. Uploader les fichiers
- Dans le dépôt, cliquer **Add file → Upload files**
- Glisser-déposer **tous** les fichiers et dossiers de ce zip
- Commit : "Premier dépôt – site Saraaf'"

### 4. Activer GitHub Pages
- Aller dans **Settings → Pages**
- Source : **Deploy from a branch**
- Branch : **main** / dossier : **/ (root)**
- Cliquer **Save**

### 5. URL du site
- Si le dépôt s'appelle `saraaf-portfolio` : `https://ton-pseudo.github.io/saraaf-portfolio/`
- Si le dépôt s'appelle `ton-pseudo.github.io` : `https://ton-pseudo.github.io/`

## ⚠️ Important – Les vidéos

Les vidéos (dossier `assets/videos/`) font entre 3 et 28 Mo chacune.
GitHub Pages les héberge gratuitement jusqu'à 1 Go au total.

**Pour une meilleure performance (recommandé à terme) :**
Uploader les vidéos sur YouTube en mode "Non répertorié" et remplacer les balises `<video>` par des `<iframe>` YouTube. Contacter bysaraaf@gmail.com pour obtenir de l'aide sur cette migration.

## Contact
bysaraaf@gmail.com
