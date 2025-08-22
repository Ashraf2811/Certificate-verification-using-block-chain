# 🎓 Blockchain-Based Certificate Verification System

## 📌 Overview
A decentralized application (dApp) that issues, stores, and verifies **academic certificates** using **Ethereum + IPFS**.

- **University (admin)** issues certificates.
- Certificates are uploaded to **IPFS** (returns CID).
- On-chain contract stores:
  - Student Name
  - Course
  - IPFS CID
  - File hash
  - Issuer (university address)
  - Issue date
- **Employers/third parties** can verify authenticity by checking file hash.

---

## ⚡ Features
- **Tamper-proof:** Certificate details stored on blockchain.
- **Off-chain storage:** Encrypted PDFs/images stored on IPFS.
- **Duplicate prevention:** File hash cannot be reused.
- **Revocation:** Issuer can revoke certificates if required.
- **Instant verification:** Employers verify authenticity in seconds.

---

## 🛠 Setup Instructions
1. Install dependencies:
   ```bash
   npm install -g truffle
   npm install
