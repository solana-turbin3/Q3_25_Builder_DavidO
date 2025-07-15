# DeFi Primitives Monorepo

This monorepo contains foundational smart contracts and tooling for building decentralized finance (DeFi) applications on Solana. It includes reusable components like escrow and vault primitives, as well as prerequisite materials and a starter template for fast development.

## 🧱 Structure

```
.
├── defi-primitives/
│   ├── escrow/         # Escrow program for conditional asset locking
│   └── vault/          # Vault program for token custody and control
│
├── prereq/
│   ├── prereq-rust/    # Rust-based prerequisites for turbin3
│   └── prereq-ts/      # TypeScript-based prerequisites turbin3
│
├── solana-starter/     # Starter project to bootstrap Solana programs using Anchor
├── .gitmodules         # Submodules configuration
└── README.md           # You're here
```

## 📦 Submodules

This project uses Git submodules. After cloning, run:

```bash
git submodule update --init --recursive
```

To update submodules later:

```bash
git submodule update --remote
```

## 🚀 Getting Started

### Requirements

- [Anchor](https://www.anchor-lang.com/) (for Solana smart contract development)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Rust](https://www.rust-lang.org/tools/install)
- Node.js (for TypeScript tooling)

### Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/your-username/your-repo.git
```

## 📁 Folders Overview

- **`defi-primitives/escrow`** – Smart contract for managing token-based escrows.
- **`defi-primitives/vault`** – Token vault contract to securely store and manage tokens.
- **`prereq/prereq-rust`** – Rust tutorials and helper crates for Anchor/Solana devs.
- **`prereq/prereq-ts`** – TypeScript examples and helper scripts for interacting with programs.
- **`solana-starter`** – Anchor-based boilerplate to quickly start new Solana programs.

## 📜 License

MIT License. See individual folders for more details where applicable.

## 🙏 Acknowledgments

- [Solana Labs](https://solana.com/)
- [Anchor by Project Serum](https://www.anchor-lang.com/)

---

Happy BUIDLing! 🛠️