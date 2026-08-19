# Pre-Req Vault Program

An Anchor-based Solana program that implements a vault system with deposit, withdraw, and close instructions, including a Cross-Program Invocation (CPI) call to the Turbin3 prerequisite registration program.

## Program Details

- **Program ID**: `2UScngshid7mP2vt3CHzoDFvcR7rLwVSADXpuzkeTgty`
- **Cluster**: Devnet
- **Registration Program (CPI)**: Calls `TRBZyQHB3m68FGeVsqTK39Wm4xejadjVhP5MAZaKWDM` (Turbin3 Prereq Registration Program) on withdraw to initialize a prerequisite registration account with the user's GitHub username.

## Getting Started

### Prerequisites

- Rust & Cargo
- Solana CLI
- Anchor CLI

### Build the Program

```bash
anchor build
```

### Deploy to Devnet

```bash
anchor deploy
```
