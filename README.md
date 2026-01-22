# Moolaah Finance

![Build Status](https://img.shields.io/badge/status-specification-blue)
![License](https://img.shields.io/badge/license-BSL--1.1-blue)
![Network](https://img.shields.io/badge/network-Avalanche%20Subnet-red)
![Category](https://img.shields.io/badge/category-RWA-green)

**Moolaah Finance** is the institutional standard for biological asset tokenization. We provide the infrastructure to digitize, value, and finance livestock operations on the blockchain, bridging the gap between global capital markets and independent agriculture.

> [!NOTE]
> **Public Specification**: This repository contains the public documentation and architectural specifications for the Moolaah Finance protocol. The core logic contracts are currently held in a private repository and are protected under the **Business Source License (BSL) 1.1**.

## The Problem
Global agricultural finance is fragmented and inefficient. Liquidity is constrained by legacy banking models that fail to account for the real-time value creation of biological growth. Producers are capital-starved, while institutional investors lack accessible, transparent channels to deploy capital into this massive non-correlated asset class.

## The Solution
Moolaah Finance creates a **Digital Twin** for livestock assets. By combining **IoT telemetry** (Proof of Life) with **Chainlink Oracles** (Market Data), we enable:
1.  **Real-Time Valuation**: Assets are repriced daily based on actual weight gain and market conditions.
2.  **Liquid Collateral**: Livestock becomes a liquid financial instrument that can be traded or borrowed against.
3.  **Trustless Settlement**: Smart contracts automate payments, yield distribution, and risk management.

## Security & Architecture

Our architecture creates a "clean room" environment for asset management:

*   **Proprietary Vault Logic**: Built in **Vyper**, our vaults utilize a dampened rebalancing algorithm to filter noise from IoT sensors and prevent oracle manipulation.
*   **Hardened Control Layer**: **Solidity** controllers manage complex business state transitions, including emergency pivots to processed goods preservation during market shocks.
*   **Verified Data**: All inputs are cryptographically verified via Chainlink Functions before affecting on-chain state.

For a deeper look, please consult our [Whitepaper](WHITEPAPER.md) and [Architecture Guide](docs/ARCHITECTURE.md).

## Roadmap & Status

We are currently in **Phase 1 (Foundation)**. Our economic models have been validated via extensive simulations on the Avalanche Fuji Testnet. We are preparing for external security audits and physical pilot trials.

See our full [Roadmap](ROADMAP.md) for launch timelines.

## License & Rights

The Moolaah Finance Protocol is protected under the **Business Source License (BSL) 1.1**.
*   **Non-Production Use**: Researchers and developers are free to view, copy, and modify the code for non-production environments (e.g., testnets, research).
*   **Production Use**: Use of the core protocol for commercial revenue generation is restricted until **January 1, 2028**.
*   **Open Source Commitment**: On the Change Date (Jan 1, 2028), the license automatically converts to a permissive **MIT License**, ensuring long-term decentralization.

## Contact & Inquiries

**Moolaah Finance Labs**
Institutional Partnerships & Investor Relations
*   **Email**: contact@moolaah.finance
*   **Security**: security@moolaah.finance

---
*Copyright © 2026 Moolaah Finance.*
