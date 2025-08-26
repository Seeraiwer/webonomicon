# 💀 Webonomicon

**Webonomicon** est une **startpage autonome** permettant d’organiser vos favoris dans un simple fichier **HTML unique**.  
Pas de serveur, pas de dépendance externe : tout est embarqué (favoris, moteur de recherche, thèmes, drag & drop…).

---

## ✨ Fonctionnalités

- 🎨 **Thèmes clair/sombre/auto** + persistance
- 🔍 **Barre de recherche intégrée** (Google, DuckDuckGo, Qwant, Bing, Brave, Startpage)
  - Alias rapides (`!ddg`, `!q`, `!b`, etc.)
- 📂 **Groupes de favoris** (création, suppression, renommage, déplacement)
- 🔗 **Liens favoris** :
  - ajout / édition via modale
  - réorganisation par **drag & drop**
- 📥 **Import / Export** :
  - JSON (sauvegarde/restauration)
  - HTML de favoris **Chrome / Firefox**
  - Fichier HTML standalone (auto-contenu)
- 🖱️ **Drag & drop complet** :
  - liens entre groupes
  - groupes réordonnables
  - groupes vides acceptent le drop
- 🛡️ **Vérification des doublons** :
  - détection automatique
  - liens dupliqués mis en évidence (bordure rouge)

---

## 🚀 Installation & Usage

1. Télécharge `webonomicon.html`
2. Ouvre-le directement dans ton navigateur
3. Active le **mode édition** (case à cocher en haut) pour :
   - ajouter un groupe
   - ajouter/modifier un lien
   - réorganiser via drag & drop

---

## ⌨️ Raccourcis clavier

- `/` → focus sur la recherche
- `e` → bascule mode édition

---

## 📦 Import / Export

- **Exporter JSON** : sauvegarde les favoris dans un fichier `.json`
- **Importer JSON** : recharge un fichier `.json`
- **Importer Bookmarks HTML** : charge un export Chrome/Firefox (avec fusion automatique des groupes)
- **Exporter HTML** : génère un nouveau fichier `webonomicon.html` autonome avec vos données intégrées

---

## 🛠️ Technologies

- HTML5 + CSS3 (custom design responsive)
- JavaScript Vanilla (aucune dépendance)
- LocalStorage pour la persistance locale

---

## 🧑‍💻 Développement

Clone ce repo et édite simplement le fichier `webonomicon.html` :

```bash
git clone https://github.com/toncompte/webonomicon.git
cd webonomicon
