# Blockspace Algorand Hackathon

An educational prototype exploring the integration of a Svelte frontend with the Algorand blockchain via a Python Flask backend. Created during the Blockspace Algorand Hackathon to demonstrate ASA (Algorand Standard Assets) creation.

⚠️ **Note**: This is a learning project/prototype, not intended for production use.

## ⚡ Features

- **Algorand Interaction**: Connect to TestNet and manage wallets.
- **Asset Creation**: Mint NFTs and Tokens (ASAs) directly from the UI.
- **Fullstack Architecture**: Decoupled Svelte frontend and Flask backend.

## 🛠 Tech Stack

- **Frontend**: [Svelte](https://svelte.dev/), [Tailwind CSS](https://tailwindcss.com/)
- **Backend**: [Python Flask](https://flask.palletsprojects.com/)
- **Blockchain**: `py-algorand-sdk`

## 🚀 Quick Start

The project includes a helper script to bootstrap both services.

1. **Setup Environment**
   Ensure you have Node.js and Python 3.9+ installed.
   Configure your `.env` in the `back/` directory with your Algorand TestNet credentials.

2. **Run**
   ```bash
   chmod +x start.sh
   ./start.sh
   ```
   This script installs frontend dependencies and launches both the Vite server and Flask API.

## 🤝 Contributing

Feel free to fork this repository for your own experiments with Algorand!
