# Video Player 🎬

## 🇫🇷 Français

### Description
Un script vidéo pour serveur FiveM permettant de lire des vidéos YouTube et Vimeo dans le jeu GTA V. Les administrateurs peuvent ouvrir un menu pour entrer l'URL d'une vidéo et la diffuser à tous les joueurs du serveur.

### Fonctionnalités
- ✅ Support YouTube et Vimeo
- ✅ Interface utilisateur fluide
- ✅ Contrôle à la souris lors de la lecture
- ✅ Fermeture par ESC ou bouton
- ✅ Commandes administrateur
- ✅ Notification d'erreur

### Installation
1. Téléchargez les fichiers
2. Placez le dossier dans votre répertoire `resources`
3. Ajoutez `ensure MenuURL` dans votre `server.cfg`
4. Ajoutez `add_ace group.admin video.admin allow` dans votre `server.cfg`

### Commandes
- `/url` - Ouvre le menu de lecture vidéo (Admin)
- `/urls` - Arrête la vidéo en cours (Admin)

### Fichiers
- `fxmanifest.lua` - Configuration du script
- `client/main.lua` - Logique client principale
- `client/menu.lua` - Gestion du menu
- `client/player.lua` - Commandes joueur
- `server/main.lua` - Logique serveur
- `html/index.html` - Interface HTML
- `html/style.css` - Styles
- `html/script.js` - Logique Frontend

---

## 🇬🇧 English

### Description
A video script for FiveM servers that allows playing YouTube and Vimeo videos in GTA V. Administrators can open a menu to enter a video URL and broadcast it to all server players.

### Features
- ✅ YouTube and Vimeo support
- ✅ Smooth user interface
- ✅ Mouse control during playback
- ✅ Close with ESC or button
- ✅ Admin commands
- ✅ Error notifications

### Installation
1. Download the files
2. Place the folder in your `resources` directory
3. Add `ensure MenuURL` in your `server.cfg`
4. Add `add_ace group.admin video.admin allow` in your `server.cfg`

### Commands
- `/url` - Opens the video player menu (Admin)
- `/urls` - Stops the current video (Admin)

### Files
- `fxmanifest.lua` - Script configuration
- `client/main.lua` - Main client logic
- `client/menu.lua` - Menu management
- `client/player.lua` - Player commands
- `server/main.lua` - Server logic
- `html/index.html` - HTML interface
- `html/style.css` - Styles
- `html/script.js` - Frontend logic

---

## 📝 Author
**Léo**

## 📦 Version
1.0.0
