# 🏫 Lydex Réclamations — Guide de déploiement

## Déploiement sur Vercel (5 minutes)

### Étape 1 — Créer un compte GitHub (si pas déjà fait)
1. Aller sur https://github.com
2. Cliquer "Sign up" → email + mot de passe
3. Confirmer votre email

### Étape 2 — Créer un dépôt et uploader les fichiers
1. Cliquer le "+" en haut à droite → "New repository"
2. Nom : `lydex-reclamations`
3. Cliquer "Create repository"
4. Cliquer "uploading an existing file"
5. **Glisser-déposer TOUT le contenu du dossier `lydex-app`**
6. Cliquer "Commit changes"

### Étape 3 — Déployer sur Vercel
1. Aller sur https://vercel.com
2. Cliquer "Sign up with GitHub"
3. Cliquer "Add New Project"
4. Choisir le dépôt `lydex-reclamations`
5. Laisser les paramètres par défaut → cliquer **"Deploy"**
6. Attendre ~1 minute ✅

### Étape 4 — Obtenir le lien personnalisé
- Votre app sera accessible sur : `lydex-reclamations.vercel.app`
- Si ce nom est pris, Vercel en proposera un similaire

---

## Comptes de test

| Rôle | Email | Accès |
|------|-------|-------|
| Admin | y.elhint@lydex-se.ma | Dashboard complet |
| Admin | m.moubsit@lydex-se.ma | Dashboard complet |
| Élève/Staff | n'importe.qui@lydex-se.ma | Formulaire réclamation |

---

## Ajouter le vrai logo Lydex

Dans le fichier `src/App.jsx`, chercher la fonction `LydexLogo` et remplacer le contenu par :
```jsx
<img src="URL_DE_VOTRE_LOGO" style={{width:"100%",height:"100%",objectFit:"contain"}} />
```

Ou me donner le logo en PNG/JPG et je m'en occupe !

---

## QR Codes

Une fois l'app en ligne, aller dans le dashboard admin → onglet "📲 QR Codes" pour générer et télécharger les QR codes de chaque bâtiment.
