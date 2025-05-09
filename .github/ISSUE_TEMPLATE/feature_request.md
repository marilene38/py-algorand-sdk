---
name: "🔔 Feature Request"
about: Suggestions for improving the Algorand platform SDK, including wallet connections, ASAs, payments, clawbacks, fees, locating accounts, smart contracts, NFTs, DApps, consensus, and SDK tools.
title: "[Feature Request] <Short description of the feature>"
labels: "new-feature-request, enhancement"
assignees: "marilene38"
---

## Problem

<!-- Describe the problem or limitation you're facing. For example:
- Are there missing features in the SDK?
- Are you unable to connect wallets (e.g., Pera, Defly)?
- Is ASA creation, querying, or management difficult?
- Are payment requests, withdrawal clawbacks, or fee calculations unsupported?
- Are there challenges with smart contracts, NFTs, or DApps? -->

<details>
  <summary>Examples of Problems:</summary>
  - The SDK lacks tools to connect wallets like Pera or Defly.
  - No utilities for programmatically managing ASAs or NFTs.
  - Payment requests or clawbacks are hard to implement via the SDK.
  - Missing functionality for supporting DApps or smart contract interactions.
  - Consensus mechanisms are not represented in SDK tools.
</details>

<textarea placeholder="Explain the problem clearly. Include examples if possible." required></textarea>

---

## Proposed Solution

<!-- Provide a detailed explanation of the solution or feature you propose. Include any technical details or implementation ideas. -->

- **Primary Solution**: <textarea placeholder="Describe the main solution or feature you’d like implemented." required></textarea>
- **SDK Functionalities**:
  - **Wallet Connections**: Add tools to connect and manage wallets like Pera and Defly.
  - **Wallet Management**: Locate assets, manage accounts, send/receive payments, and perform clawbacks.
  - **ASA Tools**:
    - Create, transfer, and query ASAs.
    - Manage ASA metadata (e.g., decimals, freeze, and clawbacks).
  - **NFT Support**: Enable minting, transferring, and querying NFTs.
  - **Smart Contracts**: Provide tools for creating, deploying, and interacting with smart contracts.
  - **DApps Support**: Extend SDK utilities for DApp integrations.
  - **Consensus Tools**: Add utilities for implementing consensus mechanisms.
  - **Fee Calculation**: Include tools to estimate and manage transaction fees.
- **Alternative Solutions (if any)**: <textarea placeholder="List any alternative approaches or ideas to solve the problem." required></textarea>

---

## Dependencies

<!-- List any dependencies or external libraries/APIs involved. For example:
- Are wallet APIs like Pera or Defly required?
- Are there backend services needed for implementing this feature?
- Are there blockchain-specific requirements for ASA, NFT, or payment management? -->

<textarea placeholder="List dependencies, such as APIs, libraries, or technical requirements." required></textarea>

---

## Urgency

<!-- How urgent is the feature for your project or workflow? -->

- **Select Urgency**:
  <dropdown id="urgency" required>
    <option>Critical - Needed immediately</option>
    <option>High - Required in the next release</option>
    <option>Medium - Nice to have but not urgent</option>
    <option>Low - No strict timeline</option>
  </dropdown>

---

## Additional Context

<!-- Add any other context, designs, or resources that could help implement this feature. Provide links to relevant documentation or mockups. -->

<textarea placeholder="Link to designs, mockups, or technical docs (optional)." required></textarea>
