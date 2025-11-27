# 🪪 DiscountCard Smart Contract

A simple and beginner-friendly Ethereum smart contract that allows an owner to issue, manage, and revoke digital discount cards for users. Users can redeem their discount a limited number of times directly on the blockchain.

This project is ideal for learning the basics of:
- Solidity
- Smart contract deployment
- Mappings and structs
- Access control
- Events and state management

---

## 📖 Project Description

The DiscountCard smart contract is a basic blockchain-based loyalty and discount system. Instead of using physical discount cards, this contract enables digital discount cards that are securely stored and managed on the Ethereum blockchain.

The contract is owned by a single administrator (the deployer), who can issue discount cards to users with a specific discount percentage and a limited number of uses. Each user can then redeem their card until all uses are exhausted.

This project is built for educational purposes and as a foundation for real-world blockchain-based loyalty systems.

---

## ⚙️ What It Does

- The contract deployer becomes the **owner** of the system.
- The owner can:
  - Issue discount cards to users.
  - Set discount percentage and number of uses.
  - Remove (deactivate) any user’s card.
- Users can:
  - Use their discount card.
  - Check their own card details.
- Each time a card is used:
  - The usage count is reduced.
  - When the usage count reaches zero, the card is automatically deactivated.

All actions are recorded on the blockchain using events.

---

## ✨ Features

- ✅ Simple and beginner-friendly Solidity code
- ✅ No constructor inputs required
- ✅ Owner-only card issuance and removal
- ✅ User-based discount redemption
- ✅ Automatic deactivation after last use
- ✅ Transparent on-chain event logs
- ✅ Public card lookup using wallet address
- ✅ Secure access control using onlyOwner modifier

---

## 🔗 Deployed Smart Contract Link

Contract Address:
0xCD62eCF30ed073F01997f092639b4e4eC0C7aCae

You can view the contract on a block explorer by pasting this address into your network’s explorer (e.g., Etherscan / Sepolia Etherscan).

---

## 📄 Smart Contract Code

// SPDX-License-Identifier: MIT  
pragma solidity ^0.8.19;  

//paste your code

---

## 🚀 Future Improvements (Optional Ideas)

- Add expiry date to discount cards
- Add merchant verification
- Add NFT-based discount cards
- Add frontend UI with wallet connection
- Add multiple admin roles

---

## 🧑‍💻 Author

Built as a beginner blockchain project for learning Solidity and smart contract deployment.

---

⭐ If you found this project helpful, feel free to star the repository!
