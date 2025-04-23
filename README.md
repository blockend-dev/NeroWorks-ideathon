# Neroworks – Gasless Freelancing on NERO Chain

## 🚀 Elevator Pitch
**Neroworks** is a Web3 freelancing platform built on NERO Chain that makes it possible for anyone to work or hire talent without worrying about gas fees, wallets, or crypto complexity — thanks to Account Abstraction and Paymaster integration.

## 🎯 Problem
Freelancers in emerging markets and non-crypto natives face friction when trying to earn onchain:
- Complex wallet setup & private keys
- High or unpredictable gas fees
- Poor UX for job management and payments

## 🌟 Solution
Neroworks provides a gasless, wallet-free experience using:
- **NERO's Account Abstraction (AA)** to allow social login, smart wallets, and simplified interactions.
- **NERO's Paymaster API** to let clients/platform sponsor gas fees or allow freelancers to pay using stablecoins or project tokens.
- **Blockspace 2.0** for fair, MEV-resistant job contract execution.

## 👥 User Flow

![mermaid-diagram-2025-04-23-083154](https://github.com/user-attachments/assets/d8f30555-b027-488e-bc9e-41e0ebb3087c)

**Freelancer:**
1. Visits app → logs in with email (AA)
2. Browses gigs, applies, gets hired
3. Delivers work → gets paid, no gas paid
   
![mermaid-diagram-2025-04-23-083749-freelancer](https://github.com/user-attachments/assets/6f87cb56-4590-4830-8028-12ae1531f76d)

**Client:**
1. Logs in → posts job
2. Reviews applicants → hires → deposits escrow
3. Approves delivery → funds released automatically
   
![mermaid-diagram-2025-04-23-083902-client](https://github.com/user-attachments/assets/06de8248-cf80-4aff-aa31-84c9f0e89c64)


## 🧠 AA & Paymaster Vision (30%)
Neroworks showcases a clear integration of:
- **Account Abstraction**: Walletless onboarding, session keys for job tasks, and programmable smart accounts.
- **Paymaster**: Sponsored transactions for freelancers, flexible gas logic, ERC20-based gas payments.

## 🧩 Architecture Overview
![Architecture Diagram](assets/architecture.png)

- **Frontend**: React / Next.js
- **Smart Contracts**: Job escrow, milestone tracking, payment release
- **NERO Chain SDKs**: For AA smart accounts and Paymaster logic
- **IPFS**: Metadata storage, notifications, job feeds
  
![mermaid-diagram-2025-04-23-084443-archi](https://github.com/user-attachments/assets/5a8ba90c-a37a-4516-8fd1-1173e9a61ed5)


## 🎨 Innovation & Relevance 
Neroworks creatively applies NERO’s AA and gasless infra to an untapped segment: global freelancers and startups. It aligns with themes like usability, AA innovation, and real-world adoption.

## 🌍 User Impact 
Designed for:
- **Newcomers & Non-Crypto Users**
- **Emerging market freelancers**
- **Startups needing agile hiring**

## 📈 Ecosystem Fit 
- Shareable, useful, and visible on X/Farcaster
- Encourages real-world use of NERO
- Flexible token gas logic makes it useful for any builder

## 🛣️ Continuity 
**Wave 2 Goals:**
- Build MVP (job post, hire, pay)
- Paymaster and AA integrated
- Deploy to NERO testnet with smart accounts

**Wave 3+:**
- Add reputation NFTs, onchain reviews
- Mobile-friendly version
- Token integrations for fee logic


## 📹 Video Demo
See `video-link.txt` for demo.

---

Thank you for considering Neroworks 🙌

We believe this project can show the real power of NERO’s AA and Paymaster to empower builders and workers around the world.

