# 📐 Tage Mage — App Maths

Application PWA de révision mathématiques pour le Tage Mage.  
Installable sur téléphone, fonctionne **hors ligne**.

## Contenu
- Tables de 1 à 20 (jusqu'aux multiples de 20)
- Carrés (1² à 25²) et Cubes (1³ à 12³)
- Nombres premiers (2 à 100) + méthode de détection
- Nombres parfaits + méthode
- Critères de divisibilité de 2 à 11 (avec explications détaillées)
- Quiz configurable par thème + explication à chaque erreur

---

## 🚀 Déployer sur GitHub Pages (gratuit)

### Étape 1 — Créer le repo GitHub

1. Va sur [github.com](https://github.com) → **New repository**
2. Nom : `tage-mage` (ou ce que tu veux)
3. Mets-le en **Public**
4. Ne coche rien d'autre → **Create repository**

### Étape 2 — Envoyer les fichiers

Depuis ton PC, dans le dossier `tage-mage-app/` :

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TON-USERNAME/tage-mage.git
git push -u origin main
```

### Étape 3 — Activer GitHub Pages

1. Dans ton repo GitHub → **Settings** → **Pages**
2. Source : **Deploy from a branch**
3. Branch : `main` / `/ (root)` → **Save**
4. Attends 1-2 minutes → ton app est sur `https://TON-USERNAME.github.io/tage-mage/`

### Étape 4 — Installer sur le téléphone

**Android (Chrome) :**
1. Ouvre `https://TON-USERNAME.github.io/tage-mage/` dans Chrome
2. Menu ⋮ → "Ajouter à l'écran d'accueil"
3. Confirmer → l'icône apparaît sur ton bureau

**iPhone (Safari) :**
1. Ouvre l'URL dans Safari (pas Chrome !)
2. Bouton Partager (carré avec flèche) → "Sur l'écran d'accueil"
3. Confirmer → l'icône apparaît sur ton bureau

---

## 📁 Structure des fichiers

```
tage-mage-app/
├── index.html      ← L'app complète (HTML + CSS + JS)
├── manifest.json   ← Config PWA (nom, icône, couleurs)
├── sw.js           ← Service Worker (mode hors-ligne)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

---

## ⚠️ Important pour GitHub Pages

Si ton repo s'appelle `tage-mage` (pas `TON-USERNAME.github.io`), l'URL sera :
`https://TON-USERNAME.github.io/tage-mage/`

Dans ce cas, le service worker fonctionne déjà correctement.

---

Bonne révision ! 💪
