# Raffle Lottery Smart Contract 🎟️

This project is a decentralized **Raffle Lottery Smart Contract** built in Solidity, following the [Cyfrin Updraft](https://www.cyfrin.io/updraft) course by Patrick Collins.  
The contract allows participants to enter a lottery by paying an entrance fee. A random winner is selected using Chainlink VRF (Verifiable Random Function), and the process can be automated with Chainlink Automation.

---

## 📌 Features
- **Enter Raffle**: Users can enter the lottery by sending ETH equal to or above the required entrance fee.
- **Random Winner Selection**: Uses Chainlink VRF to ensure fair and tamper-proof randomness.
- **Automated Execution**: Uses Chainlink Automation to trigger winner selection at regular intervals.

---

## 🛠️ Tech Stack
- **Solidity** (Smart Contract Language)  
- **Foundry** (Testing & Development Framework)  
- **Chainlink VRF & Automation** (Randomness & Task Scheduling)  
- **Ethereum / EVM-based Chains** (Deployment Target)

---

## Learning Outcomes

- Through this project, I learned:

- How to implement a decentralized lottery system in Solidity.

- How to integrate Chainlink VRF for randomness.

- How to use Chainlink Automation for scheduled execution.

- How to write and run tests with Foundry.

## Possible Extensions

- Programmatically Add Automation: Instead of manually setting up Chainlink Upkeeps via the UI, integrate it directly into the deployment scripts.

- More Integration Tests: Expand test coverage to simulate full end-to-end flows with VRF and Automation mocks.
