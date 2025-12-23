# Pinterest Board Downloader (Standalone & Universal)

Un outil professionnel pour sauvegarder vos tableaux Pinterest avec une organisation parfaite et une qualité maximale.

## 🚀 Fonctionnalités Clés
- **Multi-Navigateur** : Synchronise vos cookies depuis **Firefox, Chrome, Edge, Brave, etc.** pour une connexion transparente.
- **Qualité Maximale** : Récupère les images dans leur résolution d'origine (pas de miniatures).
- **Rangement par Tableau** : Crée automatiquement des dossiers nommés selon vos tableaux Pinterest.
- **Support Vidéo complet** : Télécharge les fichiers `.mp4` avec fusion audio/vidéo automatique.
- **Anti-Doublon Intelligent** : Utilise un fichier `archive.txt` pour ne télécharger que les nouvelles épingles lors des prochains lancements.
- **Sélecteur de Dossier** : Fenêtre interactive pour choisir où enregistrer vos fichiers sans toucher au code.
- **Anti-Ban** : Délais aléatoires (3-7s) imitant un comportement humain.

## 📥 Installation

### Option A : Version Exécutable (Recommandé)
1. Téléchargez `PinterestDownloader.exe` depuis la section [Releases](https://github.com/votre-pseudo/votre-repo/releases).
2. Lancez-le directement. Aucune installation de Python n'est requise.

### Option B : Version Python (Développeurs)
1. Clonez ce dépôt.
2. Installez les dépendances : `pip install -r requirements.txt`.
3. Lancez le script : `python pinterest_exporter.py` ou utilisez le `.bat`.

## 📖 Utilisation
1. **Connexion** : Assurez-vous d'être connecté à Pinterest sur votre navigateur habituel.
2. **Fermeture** : Fermez votre navigateur un court instant avant de lancer le scan (pour libérer les cookies).
3. **Configuration** : Indiquez votre pseudo Pinterest et choisissez votre navigateur dans la liste proposée.

## 🛠️ Composants Internes
Ce script est un wrapper intelligent autour de :
- **gallery-dl** : Pour l'extraction d'images.
- **yt-dlp** : Pour le moteur vidéo.
- **FFmpeg** : Pour la finalisation des vidéos (téléchargé automatiquement au premier lancement).

## 🛡️ Confidentialité
- **Aucun mot de passe requis** : Le script utilise uniquement vos cookies de session locale.
- **Zéro fuite** : Vos données d'accès restent sur votre machine et ne sont jamais téléchargées sur GitHub.

---
*Fait avec ❤️ pour les curateurs de contenu.*
