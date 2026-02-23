# Grist Shared Files Widget

> **Author:** Said Hamadou
> **License:** Apache-2.0

---

*[English](#english) | [Français](#français)*

---

<a id="english"></a>

## 🇬🇧 English

File sharing and management widget for Grist. Upload, preview, and download documents directly from your Grist tables.

**Widget URL:** `https://isaytoo.github.io/grist-shared-files/`

### 🚀 Quick Start

1. In Grist, click **"Add widget to page"**
2. Select **"Custom"** as the widget type
3. Enter the custom widget URL:
   ```
   https://isaytoo.github.io/grist-shared-files/
   ```
4. Set the access level to **"Full document access"**
5. Done! Start sharing files.

### 📋 Features

- **File upload** with drag & drop support
- **File preview** for common formats (images, PDF, text)
- **Download** files directly from Grist
- **File management**: rename, delete, organize
- **Attachment storage** within Grist documents
- **Bilingual interface** (French / English)

### 🔒 Security

- File type validation
- XSS protection on all user inputs
- Size limits to prevent abuse

### 🛠️ Local Development

```bash
git clone https://github.com/isaytoo/grist-shared-files.git
cd grist-shared-files
python3 -m http.server 8585
```

Then in Grist, use: `http://localhost:8585/index.html`

### ⚙️ Required Configuration

The widget requires **Full document access** to:
- Read and write file attachments
- Manage file metadata in tables

### 📁 File Structure

```
grist-shared-files/
├── index.html       # Widget UI (HTML + CSS + JS)
├── img/             # Screenshots and assets
├── vercel.json      # Vercel config (iframe headers)
├── .gitignore
└── README.md
```

---

<a id="français"></a>

## 🇫🇷 Français

Widget de partage et gestion de fichiers pour Grist. Uploadez, prévisualisez et téléchargez des documents directement depuis vos tables Grist.

**URL du widget :** `https://isaytoo.github.io/grist-shared-files/`

### 🚀 Utilisation rapide

1. Dans Grist, cliquez sur **"Ajouter un widget à la page"**
2. Sélectionnez **"Personnalisé"** comme type de widget
3. Entrez l'URL :
   ```
   https://isaytoo.github.io/grist-shared-files/
   ```
4. Définissez le niveau d'accès sur **"Full document access"**
5. C'est prêt ! Commencez à partager vos fichiers.

### 📋 Fonctionnalités

- **Upload de fichiers** avec glisser-déposer
- **Prévisualisation** des formats courants (images, PDF, texte)
- **Téléchargement** direct depuis Grist
- **Gestion des fichiers** : renommer, supprimer, organiser
- **Stockage des pièces jointes** dans les documents Grist
- **Interface bilingue** (Français / Anglais)

### 🔒 Sécurité

- Validation des types de fichiers
- Protection XSS sur toutes les entrées utilisateur
- Limites de taille pour prévenir les abus

### 🛠️ Développement local

```bash
git clone https://github.com/isaytoo/grist-shared-files.git
cd grist-shared-files
python3 -m http.server 8585
```

Puis dans Grist, utilisez : `http://localhost:8585/index.html`

### ⚙️ Configuration requise

Le widget nécessite un **accès complet au document** pour :
- Lire et écrire les pièces jointes
- Gérer les métadonnées des fichiers dans les tables

### 📁 Structure des fichiers

```
grist-shared-files/
├── index.html       # Interface HTML + CSS + JS du widget
├── img/             # Captures d'écran et assets
├── vercel.json      # Configuration Vercel (headers iframe)
├── .gitignore
└── README.md
```

---

## 🔗 Resources / Ressources

- [Grist Custom Widgets Documentation](https://support.getgrist.com/widget-custom/)
- [Grist Plugin API](https://support.getgrist.com/code/modules/grist_plugin_api/)
- [GristUp Widget Marketplace](https://www.gristup.fr)
