# ✦ The Mystic One — Android App

> Intelligence mystique alimentée par Claude AI

## 📲 Télécharger l'APK directement

**→ Aller sur l'onglet [Releases](../../releases) de ce repo pour télécharger l'APK**

---

## 🚀 Compiler l'APK via GitHub (0 installation requise)

### Étape 1 — Créer votre repo GitHub

1. Aller sur [github.com](https://github.com) → **New repository**
2. Nom : `the-mystic-one`
3. Visibilité : **Public** (ou Private)
4. Cliquer **Create repository**

### Étape 2 — Uploader les fichiers

**Option A — Via l'interface web GitHub :**
1. Dans votre repo → **Add file** → **Upload files**
2. Glisser-déposer TOUT le contenu du ZIP extrait
3. Cliquer **Commit changes**

**Option B — Via Git (terminal) :**
```bash
git init
git add .
git commit -m "Initial: The Mystic One"
git remote add origin https://github.com/VOTRE_NOM/the-mystic-one.git
git push -u origin main
```

### Étape 3 — Activer les Actions GitHub

1. Dans votre repo → onglet **Actions**
2. Si demandé : cliquer **"I understand my workflows, go ahead and enable them"**

### Étape 4 — La compilation démarre automatiquement !

- Dès que vous faites un push, le workflow se lance
- Aller dans **Actions** → voir la progression en temps réel (2-3 min)
- Une fois terminé → onglet **Releases** → télécharger `TheMysticOne.apk`

---

## 📱 Installer l'APK sur Android

1. Télécharger `TheMysticOne.apk` depuis les Releases
2. Sur votre téléphone :
   - **Paramètres → Sécurité → Sources inconnues** → Activer
   - Ou : **Paramètres → Apps → Menu (⋮) → Accès spécial → Installer applis inconnues**
3. Ouvrir le fichier APK → **Installer**
4. Lancer **The Mystic One**

---

## ⚙️ Configuration dans l'app

Au premier lancement → appuyer **⚙️** :

| Paramètre | Valeur |
|-----------|--------|
| Clé Anthropic | `sk-ant-api03-...` |
| Wake Word | Activé → dites **"Mystic"** |
| Voix auto | Activé |
| Vitesse | 0.92 (naturelle) |
| Tonalité | 0.88 (grave) |

**Obtenir une clé gratuite** : [console.anthropic.com](https://console.anthropic.com)

---

## 🎙️ Optimiser la voix française

Pour une voix encore plus naturelle sur Android :

1. **Paramètres → Accessibilité → Synthèse vocale**
2. Moteur : **Google Text-to-Speech**
3. Langue : **Français (France)**
4. Cliquer **Télécharger** la voix haute qualité

---

## ✨ Fonctionnalités

- 🎤 **Wake word "Mystic"** — activation vocale permanente
- 🗣️ **Voix française naturelle** — Google TTS haute qualité
- 💬 **IA Claude** — intelligence conversationnelle
- 🌤️ **Météo Alger** en temps réel (gratuit, sans clé)
- 📅 **Google Calendar** via MCP
- 📧 **Gmail** via MCP
- 🔍 **Recherche web** temps réel
- 📱 **Design glassmorphism** — fond gris mat + verre
- 📳 **Vibration** au wake word
- 💾 **Paramètres persistants**

---

## 🔧 Structure du projet

```
the-mystic-one/
├── .github/workflows/build.yml   ← CI/CD GitHub Actions
├── app/
│   ├── build.gradle
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── assets/index.html     ← L'app complète
│       ├── java/com/mysticone/app/MainActivity.java
│       └── res/
│           ├── mipmap-*/         ← Icônes (toutes densités)
│           └── values/           ← Styles, couleurs, strings
├── build.gradle
├── settings.gradle
├── gradle.properties
├── gradlew
└── README.md
```

---

*The Mystic One v2.0 — Intelligence mystique*
