# 🚀 CashPump CP

## 📋 Overview

CashPump is a next-generation token launch platform built on BNB Smart Chain that allows anyone to create a token, trade it on a bonding curve, and graduate it to a decentralized exchange—while rewarding creators and holders in a transparent, sustainable way.

**The platform is fully functional on testnet.** We are raising funds to bring a proven product to mainnet, with full audit coverage, deep initial liquidity, and aggressive marketing.

---

## 💰 PRESALE - MAINNET (BSC)

### Token Overview

| Parameter | Value |
|-----------|-------|
| Token Name | CashPump Token |
| Symbol | CP |
| Network | BNB Smart Chain (Mainnet) |
| Total Supply | 1,000,000,000 CP |
| Decimals | 18 |
| Standard | BEP-20 |

### Presale Addresses

| Contract | Address | BscScan |
|----------|---------|---------|
| CP Token | `0x9618F4eC6bB5Cd9Bb4fd4239f1e8D8616DA9c2e1` | [↗](https://bscscan.com/address/0x9618F4eC6bB5Cd9Bb4fd4239f1e8D8616DA9c2e1) |
| Presale Contract | `0x9E4d0f1D4a5aACDBbdb07d60f8c0F6F7378aEd68` | [↗](https://bscscan.com/address/0x9E4d0f1D4a5aACDBbdb07d60f8c0F6F7378aEd68) |
| Treasury Safe | `0x0E9C16E3813cEe64b6a0e933C98f17D7B0E7BCbb` | [↗](https://bscscan.com/address/0x0E9C16E3813cEe64b6a0e933C98f17D7B0E7BCbb) |

### Tokenomics Distribution

| Allocation | Percentage | Supply | Security |
|------------|------------|--------|----------|
| Public Presale | 52.55% | 525,500,000 CP | Instant TGE |
| Liquidity (DEX) | 20% | 200,000,000 CP | Locked 24 months |
| Ecosystem Development | 12% | 120,000,000 CP | 6/12 months unlock |
| Marketing & Growth | 5.45% | 54,500,000 CP | 3/9 months unlock |
| Dev / Team | 10% | 100,000,000 CP | 12/24 months unlock |

### Presale Stages

| Stage | Supply | BNB Target | Rate | Bonus |
|-------|--------|------------|------|-------|
| Stage 1 | 115,000,000 CP | 13 BNB | 8,846,153 CP/BNB | +15% |
| Stage 2 | 160,500,000 CP | 30 BNB | 5,350,000 CP/BNB | +7% |
| Stage 3 | 250,000,000 CP | 65 BNB | 3,846,153 CP/BNB | 0% |

**🎯 Target Funding Goal:** 108 BNB (13 + 30 + 65)

### Fund Allocation
Raised BNB goes directly to Safe multisig:
- **Liquidity:** Deep initial liquidity on PancakeSwap
- **Development:** Platform enhancement and features
- **Marketing:** Global marketing campaigns
- **Security:** Audits and security measures

---

## 🏗️ PLATFORM - TESTNET (BETA)

### Deployed & Verified Contracts

| Contract | Address | BscScan |
|----------|---------|---------|
| FeeManager | `0x9618F4eC6bB5Cd9Bb4fd4239f1e8D8616DA9c2e1` | [↗ Verify](https://testnet.bscscan.com/address/0x9618F4eC6bB5Cd9Bb4fd4239f1e8D8616DA9c2e1) |
| LiquidityManager | `0xe4FffC5Ece5aF1546A0223f9Aa2aCAFA477a10B2` | [↗ Verify](https://testnet.bscscan.com/address/0xe4FffC5Ece5aF1546A0223f9Aa2aCAFA477a10B2) |
| GraduationManager | `0x9E4d0f1D4a5aACDBbdb07d60f8c0F6F7378aEd68` | [↗ Verify](https://testnet.bscscan.com/address/0x9E4d0f1D4a5aACDBbdb07d60f8c0F6F7378aEd68) |
| LaunchToken Impl | `0xA25590c72e8Cf7fa2386F56EC1b876C393Ae8596` | [↗ Verify](https://testnet.bscscan.com/address/0xA25590c72e8Cf7fa2386F56EC1b876C393Ae8596) |
| TokenFactory | `0xF8F13Ca4f9B5622F7D0A8b56F81696f92e13C051` | [↗ Verify](https://testnet.bscscan.com/address/0xF8F13Ca4f9B5622F7D0A8b56F81696f92e13C051) |
| BondingCurve Impl | `0x7Dc17559d3c536510236F060185bC5C813e4b002` | [↗ Verify](https://testnet.bscscan.com/address/0x7Dc17559d3c536510236F060185bC5C813e4b002) |
| BondingCurveFactory | `0x8eF156347466a2cFaE9C013dd94413E17045d1D4` | [↗ Verify](https://testnet.bscscan.com/address/0x8eF156347466a2cFaE9C013dd94413E17045d1D4) |
| LaunchFactory | `0x91262770a8a0072E1B20790e55934273A44E8FF4` | [↗ Verify](https://testnet.bscscan.com/address/0x91262770a8a0072E1B20790e55934273A44E8FF4) |

### ✅ Verified on BscScan Testnet
All platform contracts are publicly verified on BscScan Testnet. Anyone can:
- Review the complete source code
- Verify functions and permissions
- Check for malicious functions
- Validate bonding curve logic

---

## 🎯 Problem & Solution

### ❌ Problem
- High upfront liquidity requirements
- Opaque token launches
- Creator rewards are often unfair
- Manual liquidity locking
- No price discovery mechanism

### ✅ Solution
- Zero initial liquidity bonding curve
- Fully transparent on-chain process
- Automatic creator rewards
- Liquidity locked forever at graduation
- Algorithmic price discovery

---

## 📈 Bonding Curve Mechanics

### Formula
```text
Price = (VIRTUAL_ETH_RESERVE + ethReserve) / (VIRTUAL_TOKEN_RESERVE + tokenReserve)

### Parameters

| Parameter | Value |
|-----------|-------|
| Virtual ETH Reserve | 2.0475 BNB |
| Virtual Token Reserve | 273,000,000 |
| Max Sellable Tokens | 800,000,000 (80%) |
| Liquidity Tokens | 200,000,000 (20%) |
| Graduation Threshold | 6 BNB |
| Graduation Reward | 1 BNB |

### Price Progression

| Milestone | BNB Reserves | USD Price | Market Cap | Progress |
|-----------|--------------|-----------|------------|----------|
| Start | 0 BNB | $0.000001164 | $1.16K | 0% |
| 25% | 0.512 BNB | $0.000001955 | $1.96K | 25% |
| 50% | 1.396 BNB | $0.000003040 | $3.04K | 50% |
| 75% | 2.558 BNB | $0.000005565 | $5.57K | 75% |
| Graduation | 6 BNB | $0.000017982 | $17.98K | 100% |

---

## 🎓 Graduation Process

When token reaches 6 BNB in bonding curve:
1. **Liquidity Pool:** 5 BNB + 200M tokens paired on PancakeSwap
2. **LP Burn:** Liquidity locked forever
3. **Creator Reward:** 0.5 BNB
4. **Platform Fee:** 0.5 BNB for maintenance

---

## 🔒 Trading Limits

| Parameter | Value |
|-----------|-------|
| Min Buy | 0.0001 BNB |
| Max Buy | 0.25 BNB |
| Total Fee | 1% |
| Creator Fee | 0.5% |
| Treasury Fee | 0.5% |

---

## 🚀 Launch Principles

- ✓ No presale on platform tokens  
- ✓ No team tokens on platform tokens  
- ✓ 100% of supply goes to bonding curve  
- ✓ Price determined by the market  
- ✓ Liquidity burned forever  
- ✓ Nobody can withdraw liquidity  

---

## 🛡️ Security & Transparency

### Platform (Testnet)
- ✅ Contracts verified on BscScan Testnet  
- ✅ Public source code  
- ✅ No unlimited mint functions  
- ✅ No backdoors  
- ✅ Complete unit tests  

### Presale (Mainnet)
- ✅ Contract verified on BscScan  
- ✅ Safe multisig 2/3  
- ✅ No mint function  
- ✅ Locks verifiable on-chain  
- ✅ Audit scheduled
