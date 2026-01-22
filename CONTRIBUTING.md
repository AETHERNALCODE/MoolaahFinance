# Contributing to Moolaah Finance

Thank you for your interest in contributing to Moolaah Finance! We are building the institutional standard for livestock tokenization on Avalanche.

## 🛠 Code Standards

### Smart Contracts (Solidity & Vyper)
*   **Solidity Version**: `^0.8.28`
*   **Vyper Version**: `0.3.10`
*   **Style**: Follow the Solidity Style Guide and Vyper Style Guide.
*   **Security**: All external calls must include reentrancy guards where appropriate.
*   **Tests**: New features MUST be accompanied by integration tests in `test/`.

### TypeScript / JavaScript
*   Use `async`/`await` patterns.
*   Linting verification will be run on PR submission.

## 🚀 How to Contribute

1.  **Fork the Repo**: Click the 'Fork' button at the top right.
2.  **Create a Branch**: `git checkout -b feature/amazing-feature`.
3.  **Commit Changes**: `git commit -m 'feat: Add amazing feature'`.
    *   Please use [Conventional Commits](https://www.conventionalcommits.org/) (e.g., `feat:`, `fix:`, `chore:`).
4.  **Push to Branch**: `git push origin feature/amazing-feature`.
5.  **Open a Pull Request**: Submit your PR to the `main` branch.

## 🧪 Testing

Before submitting, run the full test suite and simulation check:

```bash
# Run unit tests
npx hardhat test

# Run simulation sanity check
POOL_ID=10030 npx hardhat run scripts/check_pool_status.cjs --network fuji
```

## 📜 Governance

Significant changes (e.g., changing the yield model or oracle logic) should be discussed in an Issue first.
