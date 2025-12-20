# 🌐 CommunityCoins — Developer Navigation Hub

Welcome to **git.communitycoins.org**, the development hub for all CommunityCoins and Rooty software.

CommunityCoins/Rooty is a Federated Initiative of community coin teams. That means that it is created and maintained by groups of friends that work together to make something amazing happen: We put the power of Bitcoin in the hands of everybody in their own country and region. For people that Bitcoin would otherwise never reach.

This communitycoin hub/library operates on Forgejo, an open source Gitea fork. It serves to maintain and collect multiple projects that are releated to Communitycoins. Gitea itself has a specific organisation that should be uderstood for comfortable navigation. We explain it in [CONTRIBUTING](CONTRIBUTING.md). We encourage each team that considers itself as a Communitycoins team to contribute to this library but at least to mirror this hub/library as a means toward federation.

> 👉 **A community coin is a true cryptocurrency, that has its own globally accessable blockchain but with a local bias, community and identity.**

This page provides a **single-entry overview** of all organisations, repositories, project boards, and development areas related to Communitycoins.

---

## 🧭 Main Areas (Organisations /org)

### 🔹 Rooty (Identity & Vision)  

Since the mission of every community coin is to serve a much larger community beyond the team and early adopters, we consider ourselves grassroots initiatives. For this reason, we’ve chosen the name ROOTY as a project identity—or rather, as a badge of honor for Communitycoins.

Main communitycoins/rooty website  
➡ https://communitycoins.org

Rooty ecosystem documents, narrative & branding  
➡ [rooty](/rooty)

### 🔹 Communitycoins Core data
Central repository of Core blockchain and environmental data  
➡ [ecoincore](/ecoincore)  
➡ https://ecoincoire.com

### 🔹 Core Wallets, docker-builds and the deploiment of images
This is a collection of core-wallet repositories. These are not mirrors of their original but a fork of their original by the end of 2025. They serve to build and deploy their docker-image based on the latest Ubuntu version, currently 24.04.  
➡ [core-wallets](/core-wallets)  

### 🔹 SPV / ROT Infrastructure  
Indexers, Electrum servers, API layers, monitoring  
➡ [Infrastructure](/spv-infra)

### 🔹 Light client / Communitycoins Multicoin Wallet
PWA (Progressive Web App) 

### 🔹 Documentation & Governance  
Manifestos, community docs, decentralisation frameworks  
➡ [Documentation & Governance](/docs-governance)  

### 🔹 Web & Visuals  
Website, graphic identity, announcements  
➡ [Visuals](/web-visuals)

---

## 📌 Master Project Boards (Cross-Organisation Planning)

### ⭐ **CommunityCoins Master Board**  
High-level governance & roadmap across ALL organisations  
➡ https://git.communitycoins.org/communitycoins/projects

### 📍 Release Roadmap  
Coordinates multi-repo release planning  
➡ *(link after you create it)*

### 💬 Communications & Outreach Board  
Public-facing progress & announcement planning  
➡ *(optional board)*

---

## 📦 Highlighted Repositories

### Core Wallets
- e-Gulden daemon → https://git.communitycoins.org/core-wallets/e-gulden  
- cc-wallet (light wallet) → *(add link)*  
- bitcoinjs-lib fork → *(add link)*  

### SPV Infra
- cc-index → *(add link)*  
- cc-electrum-monitor → *(add link)*  
- electrumx → *(add link)*  

### Docs / Governance
- Manifesto → *(add link)*  
- Docs → *(add link)*  

---

## 🧑‍💻 Developer Onboarding

### 1. Join the organisation  
Admins can add new developers via organisation settings.

### 2. Fork a repository  
Each repo allows development workflows based on:
- branches  
- pull requests  
- CI via Forgejo Actions  

### 3. Follow project boards  
Global planning goes via the **Master Board**.  
Project-specific tasks live in the organisation boards.

### 4. Coding Guidelines  
- Open a PR early  
- Use feature branches  
- CI must pass before merge  

---

## ⚙️ Technical Infrastructure

### Forgejo instance and external mirrors (Gitlab / Github)
`https://git.communitycoins.org` — self-hosted, decentralised

### CI (Forgejo Actions)  
Workflows defined in:
