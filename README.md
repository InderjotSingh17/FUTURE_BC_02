# 💰 MyToken - Custom ERC-20 Token using OpenZeppelin

This is a simple and secure ERC-20 token implementation built using the OpenZeppelin Contracts library. It includes essential features like minting, burning, and ownership control. The token is named **Ether (ETH)** and follows the best practices for Ethereum smart contracts.

## 🔗 Overview

- **Token Name**: Ether  
- **Symbol**: ETH  
- **Standard**: ERC-20  
- **Tech Stack**: Solidity ^0.8.20, OpenZeppelin v5  
- **Features**:
  - Minting by the contract owner
  - Burning by any token holder
  - Secure access control with `Ownable`

---

🔐 Security Features

✅ Inherits from Ownable to restrict mint() to only the owner.

✅ Uses _mint() and _burn() from OpenZeppelin's audited library.

✅ Complies with the ERC-20 standard for compatibility with wallets and exchanges.

🚀 Future Improvements

Add pausable functionality to freeze transfers.

Add capped supply.

Integrate with a frontend DApp.

Deploy on testnet (e.g. Goerli, Sepolia).

📃 License

This project is licensed under the MIT License.

👨‍💻 Author

Inderjot Singh


⭐️ Show Your Support
If you found this project helpful or interesting, give it a ⭐️ on GitHub and feel free to fork it for your own token ideas!

