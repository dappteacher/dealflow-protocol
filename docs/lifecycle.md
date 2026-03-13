# Agreement Lifecycle

## Overview

This document describes the full lifecycle of an agreement created using DealFlow Protocol.

Each agreement progresses through several stages from deployment to completion.

---

## 1. Agreement Creation

An operator deploys a new agreement through the Factory contract.

During deployment, the operator specifies:

- token name
- token symbol
- initial token supply
- quorum requirement
- governance participants
- agreement deadlines
- profit distribution token

Once deployed, the Agreement contract becomes active.

---

## 2. Token Initialization

The agreement deploys its ERC20 participation token.

The initial supply is minted and distributed according to the agreement configuration.

These tokens represent ownership or participation rights.

---

## 3. Governance Participation

Authorized voters begin participating in governance decisions.

Typical governance actions include:

- unlocking token transfers
- approving milestones
- enabling profit distribution

Votes are recorded within the agreement contract.

---

## 4. Quorum Achievement

Once the required quorum is reached:

- governance proposals may execute
- agreement state transitions may occur

This ensures decisions require approval from multiple stakeholders.

---

## 5. Profit Distribution

After governance conditions are satisfied, profits may be distributed to participants.

Profit distribution occurs using the configured stablecoin.

Participants receive profits proportional to their token holdings.

---

## 6. Agreement Completion

Once all obligations are fulfilled:

- profits have been distributed
- governance actions are finalized
- tokens represent completed participation

The agreement remains permanently stored on-chain as a record of the contract.

---

## Lifecycle Summary

Agreement lifecycle stages:

1. Deployment
2. Token creation
3. Governance voting
4. Quorum approval
5. Profit distribution
6. Agreement completion
