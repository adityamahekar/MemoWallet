# 🧠 MemoWallet using Motoko
## 🪙 Decentralised Notes Keeper on the Internet Computer (ICP)

MemoWallet is a blockchain-based notes application built on the **Internet Computer (ICP)**.  
It lets users **create, store, and delete notes** securely on-chain.  
Backend is in **Motoko**; frontend uses **React**.

---

## ✨ Features
- Create and store notes on-chain  
- Delete notes securely  
- Persistent notes via stable variables  
- Async calls with UI refresh  
- Simple, clean interface

---

## 🛠️ Tech Stack
| Technology | Purpose |
|---|---|
| Motoko | Smart-contract backend (canister) |
| React / JavaScript | Frontend UI |
| DFX | ICP local replica & deployment |
| Webpack | Bundling |
| HTML / CSS | Markup & styling |

---

## 📂 Project Structure
| Path | Description |
|---|---|
| `src/dkeeper/main.mo` | Motoko backend |
| `src/dkeeper_assets/src/components/` | React components |
| `src/dkeeper_assets/src/index.jsx` | Frontend entry |
| `dfx.json` | Canister configuration |
| `webpack.config.js` | Webpack config |

---
## 📸 Screenshots

| Dashboard | Create Note |
|---|---|
| ![MW1](./imgg/mw1.png) | ![MW2](./imgg/mw2.png) |

| Notes View | – |
|---|---|
| ![MW3](./imgg/mw3.png) |  |


---

## 🚀 Running Locally

1. Install dependencies  
   ```bash
   npm install
    ```
2. Start local ICP replica
   ```bash

   dfx start --clean
    ```

3. Deploy canisters
   ```bash

    dfx deploy
    ```
4. Start frontend
   ```bash

      npm start
   ```
5. Open in browser:

👉 [http://localhost:8080/](http://localhost:8080/)

