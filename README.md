# 🔎 Default System overview

### Introduction

The SPL22 NFT x Token Hybrid Deflation System is one of the latest token standards on Solana that aims to create a bridge between fungible tokens and NFTs, making this model deflationary.

### How it works?

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Current System Structure</p></figcaption></figure>

The two-way bridge created by [LibrePlex](https://twitter.com/LibrePlex) acts as an Escrow between SPL22s (NFTs) and SPL (fungible tokens), allowing users to exchange NFTs for tokens and vice versa.

[When you exchange NFTs for fungible tokens, a fixed percentage of those tokens is burned due to a burn tax, causing token deflation.](#user-content-fn-1)[^1]

### System Disadvantages :

Because the system is still raw, it has some issues that discourage users from depositing liquidity into it.

And here are some of them:

* **No utility:** Due to the limited capabilities of the system, there is no utility yet that would generate interest for users to hold their assets that turns every collection to a slow rug.
* **Honeypot opportunities**: The possibility of creating fake activity, by minting NFT'S from multiple wallets to attract users' attention to the project, and after sold-out suddenly withdraw all collected funds, leaving investors with losses.
* **Exit-liquidity opportunities**: The chance that project creators might just take their fees and leave early, without really working on making the project better.

**And for each problem, we have a solution.**

[^1]: This system was borrowed by Pandora, which implemented the technology on Ethereum and called it "ERC-404"
