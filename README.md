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

Rooty ecosystem documents, narrative & branding  
➡ [Communitycoins.Rooty](/Communitycoins.Rooty)  

Rooty Main Utilities  
➡ [README introduction, documents and governance](https://git.communitycoins.org/Communitycoins.Rooty/README)  
➡ [bitcoinjs-lib.3.3.2-pos](https://git.communitycoins.org/Communitycoins.Rooty/bitcoinjs-lib.3.3.2-pos)  
➡ [cc-electrum-monitor](https://git.communitycoins.org/Communitycoins.Rooty/cc-electrum-monitor)  
➡ [cc-index, collection of communitycoin identities](https://git.communitycoins.org/Communitycoins.Rooty/cc-index)  
➡ [communitycoins.org-website Main website sources](https://git.communitycoins.org/Communitycoins.Rooty/communitycoins.org_website)  
➡ [visuals, graphic identity](https://git.communitycoins.org/Communitycoins.Rooty/visuals)  


### 🔹 Communitycoins Core data
Central repository of Core blockchain and environmental data  
➡ [ecoincore](/ecoincore)  
➡ https://ecoincoire.com

### 🔹 Rings Of Trust / blockchain exposure

Corewallet daemons, Indexers, Electrum servers, API layers, monitoring, ...

In this organisation core-wallet-daemons are collected, enhanced with an SPV-service, to expose individual communitycoin blockchains to mobile wallets. 
The wallet sources are not mirrors of their original but forks by the end of 2025. They will be patched to follow the Ubuntu two-yearly update cycle, starting with ubuntu 24. Finally they will be merged with the Ring-of-Trust source into a docker-image to provide a reproducible, self-contained runtime.

While not a fully static binary, this offers stronger practical portability and reproducibility by freezing the entire execution environment rather than relying on host OS libraries. Tags + releases are maintained in Forgejo as truth and the builds will be pushed elsewhere later.

➡ [Rings-Of-Trust](/Rings-Of-Trust)  

### 🔹 Light client / Communitycoins Multicoin Wallet
PWA (Progressive Web App) 

➡ [Prototype](https://communitycoins.org/wallet_12)

### 🔹 Documentation & Governance  
Manifestos, community docs, decentralisation frameworks  
➡ [Documentation & Governance](Documentation%20and%20Governance)  

### 🔹 Web & Visuals  
Website, graphic identity, announcements  
➡ [Visuals](https://git.communitycoins.org/Communitycoins.Rooty/visuals)

---

## 📌 Master Project Boards (Cross-Organisation Planning)

### ⭐ **CommunityCoins Master Board**  
High-level governance & roadmap across ALL organisations  
➡ [Communitycoins Overall Coordination](https://git.communitycoins.org/Communitycoins.Rooty/-/projects/2)

### 📍 Release Roadmap  
Coordinates multi-repo release planning  
➡ [Deplyment schedule of SPV services for all communitycoins](https://git.communitycoins.org/Rings-Of-Trust/-/projects/5)

### 💬 Communications & Outreach Board  
Public-facing progress & announcement planning  
➡ [Communitycoins master texts](https://git.communitycoins.org/Communitycoins.Rooty/-/projects/6)

---

## 📦 Highlighted Repositories

### Core Wallets
- e-Gulden daemon → https://git.communitycoins.org/core-wallets/e-gulden  
- cc-wallet (light wallet) → *(add link)*  
- [bitcoinjs-lib fork](https://git.communitycoins.org/Communitycoins.Rooty/bitcoinjs-lib.3.3.2-pos)  

### Docs / Governance / README
- Manifesto →   
- Docs →   

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
- Open a PR/issue early  
- Use feature branches  
- CI must pass before merge  

---

## ⚙️ Technical Infrastructure

### Forgejo instance and external mirrors (Gitlab / Github)
`https://git.communitycoins.org` — [self-hosted, decentralised](https://git.communitycoins.org)
`https://gitlab.com/c4319` — [Orginal collection](https://gitlab.com/c4319)

### CI (Forgejo Actions)  
Workflows defined in ...:
