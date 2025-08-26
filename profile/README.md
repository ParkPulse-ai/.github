# 🌳 ParkPulse

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/Status-Active-brightgreen)]()
[![Hedera](https://img.shields.io/badge/Blockchain-Hedera-blue)]()
[![React](https://img.shields.io/badge/Frontend-React-blueviolet)]()

**Chatbot and Civic Voting to Protect Local Parks, Powered by Hedera and Real-Time NDVI Data**

---

## 🎯 Overview

ParkPulse empowers communities to make informed decisions about green spaces.
As cities grow, protecting parks and trees is vital for neighborhood health.

**Key Benefits:**

* Discover nearby parks and view size, usage, and NDVI-based greenery insights.
* Review government proposals affecting parks with clear, simple facts.
* Vote securely using Hedera wallets — tamper-evident and transparent.
* Earn rewards for verified voting.
* Prevent duplicate accounts with light location verification.

---

## 🛠 Features

### Civic Engagement

* **Proposal Pages:** Easy-to-read summaries of government park proposals.
* **Voting:** Secure vote recording on Hedera using smart contracts.
* **Rewards:** Verified participants receive incentives in their wallet.
* **Fraud Prevention:** One wallet per person; location-based checks to reduce duplicates.

### Chatbot & Data Insights

* **Virtual Assistant:** Built with LangChain agents answering park questions.
* **NDVI Visualizations:** Show potential impact on green cover and neighborhoods.

### Technology Stack

* **Frontend:** React — clean, responsive web app and chatbot.
* **Data & Maps:** PostgreSQL + PostGIS — spatial queries, park polygons, interactive map.
* **Blockchain:** Hedera and Flow — secure, consensus-backed voting.
* **Smart Contracts:** Solidity — manage proposals, votes, and rewards.
* **Hedera Agent Kit:** Proposal publishing, topic management, vote events.
* **Storage:** Walrus — decentralized storage for proposal JSON blobs.

---
### SmartContract Transactions

- Hashscan: <https://hashscan.io/testnet/contract/0.0.6595859>
- Flowscan: <https://testnet.flowscan.io/evm/contract/0x3528E5821436Ac55798e5079ccE97De405B1C544>
- Walrusscan: <https://walruscan.com/testnet/blob/o6jVj-iOywJmcqZJRRSWOtcQZuCeftPbJTH7vyl7HEU>


## ⚡ Demo / Screenshots

![Screenshot of ParkPulse Map](./assets/map-screenshot.png)
*Interactive map showing nearby parks with NDVI insights.*

![Screenshot of Proposal Voting](./assets/proposal-vote.png)
*Proposal page with vote counts and details.*

*Optional: include a short GIF showing the chatbot in action*
`![Chatbot Demo](./assets/chatbot-demo.gif)`

---

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/parkpulse.git
cd parkpulse
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file with:

```text
OPERATOR_ID=<your_hedera_account_id>
OPERATOR_KEY=<your_private_key>
CONTRACT_ID=<your_deployed_contract_id>
PUBLISHER=<walrus_endpoint>
```

4. Start the development server:

```bash
npm start
```

---

## 💡 Usage

* Chat with the assistant to explore parks and NDVI metrics.
* Navigate to proposal pages to see government proposals.
* Sign in with HashPack wallet to cast votes securely.
* Verified votes are rewarded and stored on Hedera.

---

## 📦 Proposal Storage

* Proposal results are stored as **blobs in Walrus**, ensuring tamper-evident, decentralized storage.
* JSON includes: proposal ID, park name, vote counts, voter addresses, and metadata.

---

## 🔮 Future Enhancements

* Add air quality and tree coverage metrics.
* Mobile app for civic participation on-the-go.
* Predictive analytics for park usage and environmental impact.

---

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

---

## ✨ Contributions

Contributions are welcome! Please open issues or submit pull requests.

---

## 🤝 Contact

For questions or collaboration, contact: **Manoj Srinivasa**
