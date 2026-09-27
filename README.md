# 🔐 CodeVaultAI_2027
*Où le code rencontre l’intelligence. Où le rêve devient réalité.*

> **Un coffre-fort intelligent pour développeurs, construit avec passion… et un cœur IA à l’intérieur.**

## 🚀 Fonctionnalités

- ✅ Application de bureau (Electron), 100 % hors-ligne
- ✅ Éditeur de code intégré (Monaco — le moteur de VS Code)
- ✅ Snippets sécurisés stockés en base SQLite
- ✅ Assistant IA locale « Laetitia » (via Ollama)
- ✅ Analyse statique + Auto-Fix + Beautify
- ✅ Recherche full-text instantanée
- ✅ Import/Export multi-fichiers + backup JSON
- ✅ Mode Admin avec mot de passe haché
- ✅ Détection automatique de 35+ langages

## 🛠️ Tech Stack

- **Electron 28** — application de bureau multiplateforme
- **React 18 + Tailwind CSS** — interface (thème sombre « Glassmorphism »)
- **Monaco Editor** — édition du code
- **SQLite** (`codevault.db`) — stockage local
- **Ollama** — IA locale optionnelle
- **i18next** — internationalisation
- **electron-builder** — packaging (AppImage / deb)

## 🧠 Par Thierry & Laetitia

Dédié à ceux qui croient encore aux rêves.

## 🛡️ Sécurité

- Pas de cloud
- Pas de télémétrie
- Mot de passe haché
- Accès local uniquement

## 🌍 En ligne

Disponible ici en me contactant pour plus d'infos :
- [https://sergio49290.github.io/CodeVaultAI_2027](https://sergio49290.github.io/CodeVaultAI_2027)
- [https://ThierryRAM49290.github.io/CodeVaultAI_2027](https://ThierryRAM49290.github.io/CodeVaultAI_2027)

## 💌 Contact

📧 sergio49290@gmail.com

💙 `#CodeVaultAI_2027`

---

## 🚀 Rapport de Mission — CodeVaultAI 2027

Nous avons transformé une simple « boîte à snippets » en un véritable **Assistant de Développement IA Sécurisé**.

### 1. Intelligence Artificielle locale (`ai-assistant.js`, `code-analyzer.js`)

- 🔍 **Analyse statique & IA** : détection d'erreurs de syntaxe, de variables inutilisées (`var` vs `let`) et de mauvaises pratiques. Avec Ollama connecté, analyse approfondie via LLM.
- 🔧 **Auto-Fix** : correction automatique (`==` → `===`, points-virgules manquants…) en respectant ton style.
- 🤖 **Chatbot « Laetitia »** : interface de chat flottante pour poser des questions techniques sans quitter l'éditeur.
- 🧠 **Mode AUTO** (bouton cerveau) : au glisser-déposer, l'app détecte le langage (35+ langages), propose un titre, des tags intelligents et formate le code automatiquement.

### 2. Architecture robuste (SQLite)

- 💾 Migration du stockage volatil (`localStorage`) vers une base SQL locale (`codevault.db`).
- ✅ Plus de limite de stockage, persistance réelle, meilleures performances.
- 🔄 Migration automatique des anciens snippets au premier démarrage.

### 3. Interface premium (UI/UX)

- 🌈 Coloration syntaxique (Prism.js, thème « Tomorrow Night »).
- ⚡ Recherche en temps réel (debounce) par titre, contenu ou thème.
- 📋 Copier-coller rapide des snippets.
- 🎨 Design moderne « Glassmorphism » sombre (Tailwind CSS).

### 🛠️ Capacités actuelles

| Fonctionnalité | État | Description |
|----------------|------|-------------|
| Gestion Snippets | ✅ | Créer, Lire, Modifier, Supprimer (CRUD) avec persistance SQL |
| Sécurité | ✅ | Stockage local uniquement, aucune donnée envoyée |
| Analyse Code | ✅ | Détection d'erreurs JS/TS/JSON/CSS + suggestions d'amélioration |
| Correction Auto | ✅ | Fix automatique des problèmes courants (linter basic) |
| Formatage | ✅ | « Beautify » pour indenter proprement le code |
| Recherche | ✅ | Recherche full-text instantanée dans toute la bibliothèque |
| Import/Export | ✅ | Import multi-fichiers avec auto-détection + backup JSON |
| Support Langages | ✅ | JS, TS, Python, CSS, HTML, Bash, JSON, React (35+ en mode AUTO) |

### 🔮 Prochaines étapes

- Connecter un modèle Ollama plus puissant (ex. DeepSeek Coder).
- Système de tags plus flexible que les « Thèmes ».
- Vue « Diff » pour voir les changements avant l'Auto-Fix.

**CodeVaultAI 2027 est maintenant prêt pour la production locale. 🚀**
