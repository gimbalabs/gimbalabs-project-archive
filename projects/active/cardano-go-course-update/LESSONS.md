# Cardano Go PBL Lesson Tracker

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/2c60db6d1d5d80ffb482fd2551cf4236
**Course Outline:** https://github.com/gimbalabs/cardano-go-pbl-2026/blob/main/outline.md
**Andamio Course:** https://app.andamio.io/course/fd28cf17d1869bcb1f1f3ceaa7daf02d14358ba74691fd679ba3b633

## Schema

Each lesson has:
- **Lesson #** (title)
- **Requires Demo** (checkbox)
- **Description of Demo** (text)
- **Demo Prerequisite** (text)
- **Demo Owner** (person)
- **Lesson Owner** (person)

---

## Module 100: Foundations

| Lesson | Requires Demo | Description | Status |
|--------|---------------|-------------|--------|
| 100.1 | No | — | Blank |
| 100.2 | — | — | Blank |
| 100.3 | — | — | Blank |
| 100.4 | — | Why Apollo | [Draft on GitHub](https://github.com/gimbalabs/cardano-go-pbl-2026/blob/185fe1baba1515ea44d62dd1497e915c41f2505e/lessons/100/100.4/why-Apollo.md) |
| 100.5 | — | — | Blank |

---

## Module 101: gOuroboros

| Lesson | Requires Demo | Description | Prerequisite | Status |
|--------|---------------|-------------|--------------|--------|
| 101.1 | Yes | How to run gOuroboros Starter Kit | — | Using Demeter CLI |
| 101.2 | — | — | 101.1: Have SK running | — |
| 101.3 | — | — | 101.1: Have SK running | — |
| 101.4 | — | — | — | Blank |

---

## Module 102: Apollo Transactions

| Lesson | Requires Demo | Description | Prerequisite | Status |
|--------|---------------|-------------|--------------|--------|
| 102.1 | — | — | — | Blank |
| 102.2 | Yes | Build a Simple Tx with Apollo | — | **Full draft** (see below) |
| 102.3 | — | Sign a transaction manually and programmatically | — | — |
| 102.4 | — | — | 101.1: Need gOuroboros running | — |
| 102.5 | — | — | 102.2: Build upon simple Tx | — |
| 102.6 | — | — | 102.2: Build upon simple Tx | — |

---

## Module 201: Adder Starter Kit

| Lesson | Requires Demo | Description | Prerequisite | Status |
|--------|---------------|-------------|--------------|--------|
| 201.1 | — | Adder Starter Kit | — | [GitHub](https://github.com/gimbalabs/cardano-go-pbl-2026/blob/main/lessons/201/201.1/run-adder-starter-kit.md) |
| 201.3 | — | — | 201.1: Adder SK | — |
| 201.4 | — | — | 201.1: Adder SK | — |
| 201.5 | — | — | 201.1: Adder SK | — |
| 201.6 | — | — | 201.1: Adder SK | — |

---

## Module 202

| Lesson | Status |
|--------|--------|
| 202.1 | Blank |
| 202.2 | Blank |
| 202.3 | Prerequisite: 201.1 |
| 202.4 | Blank |
| 202.5 | Blank |

---

## Module 203: Aiken/Go Types

| Lesson | Description | Status |
|--------|-------------|--------|
| 203.1 | I can compare types written in Aiken, blueprint files, and Go code | Has content |
| 203.2 | — | Blank |
| 203.3 | — | Blank |
| 203.5 | — | Blank |

---

## Module 204

| Lesson | Status |
|--------|--------|
| 204.1 | Blank |
| 204.2 | Blank |
| 204.3 | Blank |
| 204.4 | Blank |
| 204.5 | Blank |
| 204.6 | Blank |

---

## Module 301: DNS CLI

| Lesson | Status |
|--------|--------|
| 301.1 | Blank |
| 301.2 | Blank |
| 301.3 | Blank |

---

## Module 302

| Lesson | Status |
|--------|--------|
| 302.1 | Blank |

---

## Module 999: BBK/Extras

| Lesson | Requires Demo | Description | Status |
|--------|---------------|-------------|--------|
| 999.1 | — | — | [Andamio lesson](https://app.andamio.io/course/fd28cf17d1869bcb1f1f3ceaa7daf02d14358ba74691fd679ba3b633/999/lesson/1) |
| 999.2 | Yes | A basic Fiber API | [GitHub branch](https://github.com/gimbalabs/cardano-go-pbl-2026/tree/lesson-999-2-basic-fiber-API/lessons) |

---

## Additional Resources

- **What Is Bursa?** — Reference page
- **Newman's version 2025-12-19** — Draft materials

---

## Lesson 102.2: Build a Simple Transaction with Apollo (Full Draft)

*This lesson has a complete Andamio Lesson Coach draft.*

### Overview

Apollo is the Go library that makes Cardano transaction building accessible. Rather than manually constructing CBOR-encoded transactions, Apollo provides a fluent builder pattern that handles UTxO selection, fee calculation, and change output generation automatically.

### Prerequisites

- Go 1.21+ installed
- A Blockfrost API key (free tier at [blockfrost.io](https://blockfrost.io/))
- A Cardano testnet wallet with test ADA (use the [testnet faucet](https://docs.cardano.org/cardano-testnets/tools/faucet/))
- Basic understanding of the UTxO model

### Example: Simple ADA Transfer

```go
package main

import (
    "fmt"
    "log"
    "github.com/Salvionied/apollo"
    "github.com/Salvionied/apollo/txBuilding/Backend/BlockFrostChainContext"
)

func main() {
    // 1. Initialize the chain context (connects to Blockfrost)
    cc := BlockFrostChainContext.NewBlockfrostChainContext(
        "preprod",                           // network
        "preprodYOUR_BLOCKFROST_PROJECT_ID", // API key
        false,                               // not mainnet
    )

    // 2. Load your signing key
    signingKey, err := apollo.LoadSigningKeyFromFile("payment.skey")
    if err != nil {
        log.Fatal("Failed to load signing key:", err)
    }

    // 3. Derive your address from the key
    senderAddr := signingKey.PubKey().Address("preprod")

    // 4. Define the recipient and amount
    recipientAddr := "addr_test1qz..." // recipient's address
    amountLovelace := 5_000_000        // 5 ADA

    // 5. Build the transaction
    apolloBuilder := apollo.New(&cc)
    tx, err := apolloBuilder.
        SetWalletFromBech32(senderAddr.String()).
        PayToAddress(recipientAddr, int(amountLovelace)).
        Complete()

    if err != nil {
        log.Fatal("Failed to build transaction:", err)
    }

    // 6. Sign the transaction
    signedTx := tx.SignWithSkey(signingKey)

    // 7. Submit to the network
    txHash, err := cc.SubmitTx(*signedTx)
    if err != nil {
        log.Fatal("Failed to submit transaction:", err)
    }

    fmt.Printf("Transaction submitted! Hash: %s\n", txHash)
}
```

**What this does:**
- Connects to Cardano preprod testnet via Blockfrost
- Queries your wallet's UTxOs automatically
- Selects appropriate UTxOs to cover the payment + fees
- Calculates transaction fees based on current protocol parameters
- Generates change output back to your wallet
- Signs and submits the transaction

**What this does NOT do:**
- Manage your keys (you provide them)
- Wait for confirmation (returns after submission)
- Handle multi-signature scenarios (single signer only in this example)

### Core Concepts

#### 1. Chain Context

The chain context is your connection to the Cardano network. It queries UTxOs, fetches protocol parameters, and submits transactions.

```go
cc := BlockFrostChainContext.NewBlockfrostChainContext(
    "preprod",           // Network: "mainnet", "preprod", or "preview"
    "preprodXXXXXXXXX",  // Blockfrost project ID (prefixed with network)
    false,               // Set true only for mainnet
)
```

Apollo supports multiple backends—Blockfrost is the most common, but Koios and local node connections are also available.

#### 2. The Builder Pattern

Apollo uses method chaining to construct transactions:

```go
tx, err := apolloBuilder.
    SetWalletFromBech32(senderAddr).     // Set the funding wallet
    PayToAddress(recipient1, 2_000_000). // First output
    PayToAddress(recipient2, 3_000_000). // Second output
    Complete()                            // Finalize and balance
```

The `Complete()` method performs coin selection, calculates fees, and balances the transaction.

#### 3. UTxO Selection

You don't manually select UTxOs. When you call `SetWalletFromBech32()`, Apollo queries all UTxOs at that address. When you call `Complete()`, it automatically selects UTxOs that cover your outputs plus fees.

#### 4. Signing Keys

Cardano uses Ed25519 keys. Apollo can load keys from files or create them programmatically:

```go
// Load from file (Cardano CLI .skey format)
skey, err := apollo.LoadSigningKeyFromFile("payment.skey")

// Or generate new keys
mnemonic, _ := apollo.GenerateMnemonic(24)
rootKey := apollo.FromMnemonic(mnemonic)
paymentKey := rootKey.DeriveAccountKey(0).DerivePaymentKey(0)
```

### Common Patterns

#### Multiple Recipients

```go
tx, err := apolloBuilder.
    SetWalletFromBech32(sender).
    PayToAddress(recipient1, 2_000_000).
    PayToAddress(recipient2, 3_000_000).
    PayToAddress(recipient3, 1_500_000).
    Complete()
```

#### Adding Metadata

```go
metadata := map[string]interface{}{
    "msg": "Hello from Apollo!",
}

tx, err := apolloBuilder.
    SetWalletFromBech32(sender).
    PayToAddress(recipient, 5_000_000).
    SetMetadata(674, metadata).  // 674 is the common message label
    Complete()
```

#### Checking Balance Before Sending

```go
utxos := cc.Utxos(senderAddr)
balance := apollo.SumLovelace(utxos)
fmt.Printf("Available: %d lovelace\n", balance)

if balance < amountToSend + 500_000 {  // amount + buffer for fees
    log.Fatal("Insufficient funds")
}
```

### Troubleshooting

**Issue:** "No UTxOs found at address"
- **Cause:** Wallet has no funds, or you're querying the wrong network.
- **Solution:** Verify your address on a block explorer. Ensure your Blockfrost project matches the network.

**Issue:** "Transaction submit failed: ValueNotConservedUTxO"
- **Cause:** Input value doesn't equal output value plus fees.
- **Solution:** Let Apollo calculate fees automatically by removing any `SetFee()` calls.

**Issue:** "Minimum UTxO not met"
- **Cause:** Cardano requires minimum ADA per UTxO (~1 ADA for simple outputs).
- **Solution:** Ensure each output has at least 1,000,000 lovelace.

### Testing Your Implementation

1. **Submit a transaction**: Send 2 ADA to yourself. Verify on Cardanoscan.
2. **Send to multiple recipients**: Build a transaction with 3+ outputs.
3. **Add metadata**: Attach a message and verify it appears in transaction details.

### Additional Resources

- [Apollo GitHub Repository](https://github.com/Salvionied/apollo)
- [Blockfrost API Docs](https://docs.blockfrost.io/)
- [Cardano Testnet Faucet](https://docs.cardano.org/cardano-testnets/tools/faucet/)
- [Preprod Block Explorer](https://preprod.cardanoscan.io/)
- [Apollo Discord](https://discord.gg/MH4CmJcg49)

### Working Notes

**2026-01-23:** Working draft on GitHub branch: https://github.com/gimbalabs/cardano-go-pbl-2026/tree/lesson-102-2-build-Apollo-Tx

**References:**
- Course outline: https://github.com/gimbalabs/cardano-go-pbl-2026/blob/main/outline.md
- Catalyst milestone: https://milestones.projectcatalyst.io/projects/1300187/milestones/5
- Apollo Plutus V3 docs: https://github.com/Salvionied/apollo/blob/master/docs/plutus_v3_support/transaction_building.md
- James's LinkedIn post with video: https://www.linkedin.com/pulse/reflecting-go-development-andamio-platform-cakqe/
- Live Coding 2024-09-09: https://www.youtube.com/watch?v=dPSHFsblCgQ&t=148s

---

*Generated with Andamio Lesson Coach*
