# 🪪 Discount Card Smart Contract (Solidity)

A simple and beginner-friendly **Solidity smart contract** that allows an owner to issue, manage, and revoke digital **discount cards** for users on the blockchain. Users can redeem their discount a limited number of times in a fully transparent and decentralized way.

---

## 📌 Project Description

This project implements a **blockchain-based discount card system** using Solidity.  
Instead of using physical cards or centralized databases, this contract stores discount cards **on-chain**, making them:

- Transparent ✅  
- Tamper-proof ✅  
- Trustless ✅  

Only the **contract owner** can issue or remove cards, while **users can securely redeem their own discounts**.

This project is ideal for:
- Learning basic Solidity concepts
- Understanding mappings and structs
- Working with events
- Practicing smart contract deployment

---

## ⚙️ What It Does

- The **owner deploys the contract** (no constructor input required).
- The **owner gives a discount card** to any user.
- Each card has:
  - A **discount percentage**
  - A **limited number of uses**
  - An **active/inactive status**
- The **user redeems the card** using `useMyCard()`.
- After all uses are exhausted, the card automatically becomes inactive.
- The **owner can remove a card at any time**.
- Anyone can **view their own card details**.

---

## ✨ Features

- ✅ No input required during deployment  
- ✅ Owner-controlled card issuance  
- ✅ User-controlled card usage  
- ✅ Automatic expiration after usage limit  
- ✅ Fully on-chain storage  
- ✅ Public card visibility via mapping  
- ✅ Event logging for:
  - Card creation
  - Card usage
  - Card removal  
- ✅ Very beginner-friendly logic  
- ✅ Gas-optimized with Solidity `^0.8.x`  

---

## 📄 Smart Contract Overview

### Main Functions

- `giveCard(address user, uint discount, uint uses)`  
  → Owner gives a discount card to a user.

- `useMyCard()`  
  → User redeems their discount once.

- `removeCard(address user)`  
  → Owner disables a user’s card.

- `myCard()`  
  → User checks their own card details.

- `cards(address user)`  
  → Public read access to any user’s card.

---

## 🔗 Deployed Smart Contract

**Contract Address:**

```
0xCD62eCF30ed073F01997f092639b4e4eC0C7aCae
```

You can verify and interact with this contract using a blockchain explorer like Etherscan or through Remix using the **“At Address”** feature.

---

## 🧪 How to Test in Remix (Beginner Steps)

1. Open **Remix IDE**
2. Create a new file: `discount.sol`
3. Paste your contract code:
   ```solidity
   //paste your code
   ```
4. Select compiler:
   ```
   0.8.30+commit.73712a01
   ```
5. Click **Compile**
6. Go to **Deploy & Run**
7. Select **Injected Web3**
8. Click **Deploy**
9. Interact using:
   - `giveCard()`
   - `useMyCard()`
   - `myCard()`

---

## 🛠️ Tech Stack

- **Language:** Solidity  
- **Compiler Version:** `0.8.30`  
- **EVM Version:** Shanghai  
- **Optimizer:** Enabled (200 runs)  
- **Network:** XXX  
- **Wallet:** MetaMask  
- **IDE:** Remix  

---

## 📚 Use Cases

- Digital loyalty cards  
- Student or employee discount systems  
- Event entry passes  
- Web3-based coupons  
- Blockchain learning projects  

---

## 🚀 Future Improvements (Optional Ideas)

- Add **expiry time** to each card
- Add **merchant roles**
- Add **NFT-based discount cards**
- Add **frontend using React + Ethers.js**
- Add **payment integration**

---

## 🧑‍💻 Author

Built with ❤️ for learning Web3 and Solidity.

---

## 📜 License

This project is licensed under the **MIT License**.

---

### ⭐ If you like this project, give it a star on GitHub!
