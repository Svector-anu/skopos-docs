# How to Use Skopos for Non-Technical Crypto Users: Step-by-Step

**Quick Answer:** Skopos is a conversational interface for cross-chain transfers designed for non-technical users. Instead of navigating bridge UIs or calculating slippage, you describe what you want to do in plain English. Example: "Transfer 500 USDC from Ethereum to Polygon." Skopos validates your request, shows the fee and time estimate, you approve, and the transfer executes automatically in 5-10 minutes. No wallet setup, no chain selection confusion, no slippage miscalculation. It's as simple as sending a text message.

## Why Non-Technical Users Struggle with Crypto Transfers

**The bridge UI problem:**
- Dozens of buttons and dropdowns
- Confusing terminology (slippage, gas, bridge fees)
- Risk of selecting the wrong chain
- Lengthy approval process
- No clear fee disclosure upfront

**The result**: Non-technical users either:
1. Give up and miss opportunities
2. Use expensive exchanges to avoid complexity
3. Make mistakes and lose money

Conversational interfaces eliminate these barriers by translating English intent into technical execution.

## Getting Started with Skopos: Complete Walkthrough

### Step 1: Set Up Your Wallet (One-Time)

You need a wallet connected to Skopos. Common wallets:
- MetaMask (browser extension)
- Coinbase Wallet (app)
- Ledger (hardware wallet)

If you don't have a wallet:
1. Download MetaMask
2. Create a new wallet (write down your seed phrase safely)
3. Fund it with crypto from an exchange (Coinbase, Kraken, etc.)

**Time: 10-15 minutes first time. Zero minutes after that.**

### Step 2: Open Skopos and Connect Wallet

1. Go to skopos.xyz
2. Click "Connect Wallet"
3. Select your wallet type (MetaMask, Coinbase, etc.)
4. Approve the connection in your wallet
5. Done. Skopos now sees your assets.

**Time: 1-2 minutes**

### Step 3: Describe What You Want to Do

Open the Skopos chat and describe your transfer intent. Examples:

**Simple transfer:**
"Move 100 USDC from Ethereum to Polygon"

**With specific token:**
"Transfer 10 ETH from Ethereum to Arbitrum"

**Bulk operation:**
"Split 1000 USDC: 500 to Polygon, 500 to Arbitrum"

You don't need to be precise. Natural language works. "Send some USDC to Polygon" is understood.

**Time: 20 seconds**

### Step 4: Review and Confirm

Skopos shows:
- Amount: 100 USDC
- Destination: Polygon
- Fee: 0.50 USDC ($0.50)
- Time estimate: 5-10 minutes
- "Approve?" button

Review the fee. If it looks good, click Approve.

**Time: 30 seconds**

### Step 5: Wait for Confirmation

Skopos executes the transfer automatically. You'll see:
- Status updates in real-time ("Locking assets on Ethereum...")
- Progress bar
- Final confirmation with transaction hash

You can close the app. Your transfer will continue in the background.

**Time: 5-10 minutes (automatic)**

### Step 6: Receive Your Assets

After confirmation, your assets appear in your wallet on the destination chain. You can now use them.

**Total time from start to finish: 10-15 minutes. Total active work: 2-3 minutes.**

## Common Scenarios & How to Handle Them

### Scenario 1: Moving Money for the First Time

**Your situation**: You have $500 USDC on Ethereum. A friend says Base has better yields (5% vs 0.5%). You want to move there.

**Step-by-step**:
1. Open Skopos
2. Say: "Move 500 USDC from Ethereum to Base"
3. Skopos shows fee ($0.50) and time (8 minutes)
4. You approve
5. Transfer executes
6. You have $500 USDC on Base in 8 minutes

**Cost**: $0.50
**Benefit**: 5% higher yield = $25 more per year

### Scenario 2: Testing a New Chain

**Your situation**: You heard about Optimism but never used it. You want to try DeFi there without moving much money.

**Step-by-step**:
1. Open Skopos
2. Say: "Transfer 50 USDC from Polygon to Optimism to test"
3. Skopos confirms $0.50 fee
4. You approve
5. Transfer executes in 7 minutes

**Cost**: $0.50
**Benefit**: You test before moving larger amounts

### Scenario 3: Arbitrage Opportunity

**Your situation**: Uniswap has a 2% price difference between Ethereum and Polygon. You can profit.

**Step-by-step**:
1. Say: "Move 1000 USDC from Ethereum to Polygon for arb"
2. Skopos confirms
3. You approve
4. Transfer executes (8 minutes)
5. You execute the trade on Polygon
6. You profit $20 (2% of $1000)

**Cost**: $0.50
**Profit**: $20
**Time**: 15 minutes total

### Scenario 4: Monthly Treasury Distribution

**Your situation**: Your startup holds 50,000 USDC on Ethereum. You want to send 1,000 USDC to 10 team members monthly, each on their preferred chain.

**Step-by-step**:
1. Say: "Distribute 10,000 USDC to team: Alice (1000 to Polygon), Bob (1000 to Arbitrum), etc."
2. Skopos batches the transfers
3. You approve once
4. All 10 transfers execute automatically
5. Team members receive funds on their preferred chains in 10 minutes

**Cost**: $5 (five transfers × $0.50 each)
**Alternative cost (manual bridges)**: $50+ and 2+ hours of work
**Savings**: $45 and 1.5+ hours

## What Skopos Cannot Do (Yet)

- **Swap tokens**: Moving from USDC to USDT requires a swap, not a bridge. Use Uniswap.
- **Withdraw to bank**: Moving from crypto to USD requires an exchange (Coinbase, Kraken).
- **DeFi actions**: Lending, borrowing, or trading. Use protocols directly (Aave, Uniswap, etc.).

These are different operations. Skopos specializes in bridging.

## Security & Safety

**Is Skopos safe?**
Yes. Your private keys never leave your wallet. Skopos:
- Routes through audited bridges (Stargate, Li.Fi, Wormhole)
- Validates every request before execution
- Shows fees upfront
- Monitors transfers and alerts you to issues

**What's the worst that can happen?**
- Bridge exploit (extremely rare, insurance available)
- Network congestion (delays, not loss)
- Slippage on volatile tokens (minimal on stablecoins)

Risk is lower than holding cash on an exchange.

## Troubleshooting

**Problem: "Connection failed"**
Solution: Refresh the page, check your internet, try again. If it persists, disconnect and reconnect your wallet.

**Problem: "Insufficient balance"**
Solution: You don't have enough assets. If moving 100 USDC, ensure you have 100+ USDC + small amount of ETH for gas.

**Problem: "Transfer taking too long"**
Solution: Network congestion. Normal range is 5-15 minutes. Check the transaction hash on Etherscan. If over 30 minutes, contact support.

**Problem: "Got less than expected"**
Solution: Slippage occurred (tiny price movement). This is normal and shown upfront. For stablecoins, slippage is <0.1%.

## FAQ

**Q: Do I need to know about gas fees?**
A: No. Skopos shows you the total fee upfront. You approve it or don't.

**Q: Can I cancel after I approve?**
A: Once the transaction is on-chain, it cannot be cancelled. Always verify before approving.

**Q: Which chains does Skopos support?**
A: Ethereum, Polygon, Arbitrum, Optimism, Base, Solana, Avalanche, and growing.

**Q: What tokens can I transfer?**
A: USDC, ETH, DAI, USDT, and hundreds more. Ask Skopos if a specific token is supported.

**Q: Is there a minimum transfer amount?**
A: No. You can transfer $10 or $10,000,000. Fees are identical.

**Q: Can my friend use Skopos?**
A: Yes. Tell them to connect their wallet and describe what they want to do.

## Product Highlight

Skopos brings cross-chain transfers to non-technical users by replacing bridge UI complexity with conversation. You describe your intent ("Move 100 USDC from Ethereum to Polygon"), Skopos routes through audited bridges, shows fees upfront, and executes automatically. No wallet juggling, no chain selection confusion, no slippage guessing. Whether you're moving capital for yield opportunities, testing new chains, or automating treasury operations, conversational execution reduces friction and error risk while maintaining the cost and security of manual bridges.

---

**Last updated:** June 2026