# Bitstack Decentralized Analytics Smart Contract

## Overview

The Bitstack Decentralized Analytics platform is a Clarity-based smart contract enabling decentralized analytics through staking, governance, and reward mechanisms on the Stacks blockchain.

## Key Features

- STX token staking with flexible lock periods
- Tiered reward system with multipliers
- Governance proposal creation and voting
- Emergency pause functionality
- Cooldown period for unstaking

## Architecture

- Native fungible token: ANALYTICS-TOKEN
- Three-tier system with increasing benefits
- Governance mechanism with proposal and voting systems
- Cooldown mechanism for secure unstaking

## Getting Started

### Prerequisites

- Stacks wallet
- Minimum 1,000,000 µSTX for basic tier
- Clarity CLI for development

### Installation

1. Clone the repository:

```bash
git clone https://github.com/imabong-ctrl/bitstack-decentralized-analytics.git
```

2. Install dependencies:

```bash
npm install
```

3. Run tests:

```bash
clarity-cli test ./tests
```

## Usage

### Staking

```clarity
(contract-call? .bitstack-analytics stake-stx amount lock-period)
```

### Creating Proposals

```clarity
(contract-call? .bitstack-analytics create-proposal description voting-period)
```

### Voting

```clarity
(contract-call? .bitstack-analytics vote-on-proposal proposal-id vote-for)
```

## Documentation

- [Technical Documentation](./docs/technical.md)
- [Contributing Guidelines](./CONTRIBUTING.md)
- [Security Policy](./SECURITY.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
