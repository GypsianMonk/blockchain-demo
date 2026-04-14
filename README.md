

# ⛓️ Blockchain Demo

<div align="center">

![Blockchain](https://img.shields.io/badge/Blockchain-Core_Concepts-orange?style=for-the-badge&logo=bitcoin)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

> *"A chain is only as strong as its weakest block — and here, every block is verified."*

**A ground-up implementation of blockchain fundamentals** — built to understand the machinery behind distributed trust, cryptographic integrity, and decentralized consensus.

</div>

---

## 🧠 Why I Built This

As an AI/ML engineer, I'm obsessed with systems that make decisions without a central authority — whether it's a neural network learning from data or a blockchain network reaching consensus without trust.

This project was my deep dive into:
- How **cryptographic hashing** creates tamper-proof data chains
- How **proof-of-work** mimics the "cost of computation" as trust
- The parallels between **distributed ledgers** and **federated learning** architectures

---

## 🔍 What's Inside

```
blockchain-demo/
│
├── 🧱 core/              # Block structure & chain logic
├── 🔐 crypto/            # Hashing, signing, verification
├── 🌐 network/           # Peer-to-peer node simulation
├── ⛏️  mining/            # Proof-of-work implementation
└── 🧪 tests/             # Unit & integration tests
```

---

## ⚙️ Core Concepts Demonstrated

| Concept | Description |
|---|---|
| 🔗 **Block Chaining** | Each block holds the hash of the previous — break one, break all |
| 🔐 **SHA-256 Hashing** | Cryptographic fingerprinting of block data |
| ⛏️ **Proof of Work** | Mining difficulty simulation with nonce iteration |
| 📡 **Node Consensus** | Longest chain rule for distributed agreement |
| 🧾 **Transaction Ledger** | Simple UTXO-style transaction recording |

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
pip
```

### Installation
```bash
# Clone the repo
git clone https://github.com/GypsianMonk/blockchain-demo.git
cd blockchain-demo

# Install dependencies
pip install -r requirements.txt
```

### Run the Demo
```bash
python main.py
```

---

## 🧪 Sample Output

```
⛓️  Initializing Blockchain...
✅  Genesis Block created    | Hash: 0000a3f9...
➕  Block #1 added           | Tx: Alice → Bob [5 BTC]
⛏️  Mining Block #2...       | Difficulty: 4
✅  Block #2 mined           | Nonce: 84291 | Hash: 0000b7c2...
🔍  Chain Validity Check     | Status: VALID ✅
```

---

## 🤖 The AI Engineer's Lens

Blockchain and AI share more DNA than people realize:

| Blockchain | AI/ML Analog |
|---|---|
| Consensus Protocol | Ensemble Voting |
| Proof of Work | Gradient Descent Cost |
| Distributed Nodes | Federated Learning Clients |
| Immutable Ledger | Append-only Training Logs |
| Smart Contracts | Autonomous Decision Agents |

> This project sits at that intersection — a playground for thinking about **decentralized intelligence**.

---

## 📌 Roadmap

- [x] Core block & chain structure
- [x] SHA-256 hashing & verification
- [x] Proof-of-work mining
- [ ] REST API for node communication
- [ ] Wallet & digital signature support
- [ ] Smart contract execution layer
- [ ] Visualization dashboard (React frontend)

---

## 👨‍💻 Author

**Bharat** — AI/ML Engineer | M.Tech AI/ML  
🔗 [GitHub: @GypsianMonk](https://github.com/GypsianMonk)  
📍 Jaipur, India

> *Building systems that learn, adapt, and now — verify.*

---

## 📄 License

MIT License — use it, fork it, build on it.

---

<div align="center">

⭐ **Star this repo if you found it useful!**  
*Every star is a validated block in my motivation chain.*

</div>

# Blockchain Visual Demo

View the site [here](https://anshulkanwar.github.io/blockchain-demo/)

Inspired from Anders Brownworth's [Blockchain 101 - A Visual Demo](https://www.youtube.com/watch?v=_160oMzblY8)
