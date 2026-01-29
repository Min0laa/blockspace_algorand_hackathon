# Blockspace Algorand Hackathon Project 🚀

Ce projet a été développé dans un but d'apprentissage lors du **Blockspace Algorand Hackathon**. Il explore l'intégration entre une interface moderne en Svelte et la blockchain Algorand via un backend Python Flask.

⚠️ **Note :** Ce projet est un prototype expérimental créé pour apprendre et tester des concepts. Il n'est pas destiné à la production.

## 📝 À propos

L'objectif principal était de créer une application permettant d'interagir avec la blockchain Algorand, notamment pour la création d'actifs (ASA - Algorand Standard Assets). Nous avons voulu comprendre comment lier un front-end réactif à des opérations blockchain complexes.

### Fonctionnalités explorées :
-   Connexion à la blockchain Algorand (TestNet).
-   Création d'actifs (NFTs/Tokens) depuis une interface web.
-   Gestion de portefeuille (Wallet).
-   Architecture Fullstack (Front Svelte + Back Flask).

## 🛠 Technologies utilisées

-   **Frontend** : [Svelte](https://svelte.dev/) + [Tailwind CSS](https://tailwindcss.com/)
-   **Backend** : [Python Flask](https://flask.palletsprojects.com/)
-   **Blockchain** : [Algorand](https://algorand.com/) (via `py-algorand-sdk`)

## ⚙️ Installation et Lancement

### Prérequis
-   Node.js & npm
-   Python 3.9+
-   Un compte/wallet Algorand TestNet (pour les clés API/Mnemonic)

### Configuration
1.  Clonez ce dépôt.
2.  Assurez-vous d'avoir les variables d'environnement nécessaires dans un fichier `.env` dans le dossier `back/` (voir `app.py` pour les variables requises : `PASSPHRASE`, `ACCOUNT_ADDRESS`, etc.).

### Lancement rapide
Le projet inclut un script `start.sh` pour faciliter le démarrage :

```bash
chmod +x start.sh
./start.sh
```

Ce script va :
1.  Installer les dépendances frontend et lancer le serveur de développement Svelte.
2.  Lancer le serveur backend Flask.

*Note : Le backend a été adapté pour fonctionner avec `algosdk` standard afin d'assurer une meilleure compatibilité.*

## 🤝 Contribution

Comme il s'agit d'un projet d'apprentissage, n'hésitez pas à forker le projet pour tester vos propres idées ou à ouvrir des issues si vous avez des suggestions d'amélioration !

---
*Fait avec ❤️ et curiosité pour l'écosystème Algorand.*
