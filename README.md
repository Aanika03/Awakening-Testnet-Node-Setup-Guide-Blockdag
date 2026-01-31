# Awakening-Testnet-Node-Setup-Guide-Blockdag
Automation helpers for running and maintaining a **BlockDAG Awakening Testnet node** using Docker.   This repository wraps the official `docker-compose.yml` with simple scripts so you can **start, restart, and clean your node with a single command**.
## 📌 Features

- ✅ **Single command startup** using `blockdag.sh`
- 🔄 **Automatic Docker Compose detection** (v1 & v2 supported)
- 📁 **Opinionated directory structure** for data & logs
- 🔐 **Safe wallet configuration** via `.env` or `wallet.txt`
- ♻️ **Restart & cleanup utilities**
- 🐧 **Optional Docker installer** for Ubuntu/WSL
- 🌐 **EVM-only mining address support**

## 📂 Repository Structure

```bash
blockdag-scripts/
├── blockdag.sh
├── node.sh
├── restart.sh
├── restartWithCleanup.sh
├── install_docker.sh
├── docker-compose.yml
├── .env.example
├── wallet.txt.example
└── bin/
    └── bdag/
        ├── data/
        └── logs/
ℹ️ data/ and logs/ are created automatically when the node runs.
