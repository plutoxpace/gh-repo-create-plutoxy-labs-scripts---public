# gh-repo-create-plutoxy-labs-scripts---public
MasteryBitcoin 
# secp256k1 Termux Setup

This repository provides a simple script to install **Node.js**, build tools, and the **secp256k1** crypto library inside [Termux](https://termux.dev/).  
It also includes a fallback to [`@noble/secp256k1`](https://github.com/paulmillr/noble-secp256k1) in case the native module fails.

---

## 🔹 Quick Install (one line)

Run this inside Termux:

```bash
wget https://raw.githubusercontent.com/YOUR-USERNAME/secp256k1-termux/main/setup-secp256k1.sh -O setup-secp256k1.sh && chmod +x setup-secp256k1.sh && ./setup-secp256k1.sh
