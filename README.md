# Kamal

**Founder of [Ava](https://www.getava.xyz). I build the wallet an AI agent cannot drain.**

Agents already write code, book travel and argue with support desks. The moment they touch money, we hand them either nothing or everything. Ava is the third option: you sign a spending cap once, the agent works inside it, and every action ends in a receipt anyone can re-read from the chain.

```text
you   Supply 1 USDC to Aave on Monad. Cap it at 5 USDC.
ava   ▸ ava_create_mandate   USDC · monad · cap 5.00 · active
      ▸ ava_lend_execute     1.00 · filled · block 93,291,520 · chain-confirmed

you   Now supply 50 USDC.
ava   ▸ ava_lend_execute     refused
      MANDATE_NOTIONAL_EXCEEDED  Notional 50 exceeds the mandate limit of 5 USDC.
```

Both turns are production runs. The second one is the product.

| | |
|---:|:---|
| **8** | mainnet settlements |
| **4** | chains with confirmed fills |
| **25** | protocol adapters across 12 chains |
| **0** | keys the agent ever holds |

```bash
npx @getava-xyz/connect
```

One MCP server for Claude Code, Cursor, Codex, OpenClaw and Grok. Keys live in a Turnkey enclave, policy is deterministic, and Aave and Morpho lending execute today. Live numbers at [getava.xyz](https://www.getava.xyz).

## How I got here

Before Ava I shipped on more than fifteen chains: Ethereum, Solana, Sui, Aptos, Monad, Hyperliquid, Starknet, Arbitrum, Base, Avalanche, Polygon, Algorand, Celestia, Mantle, Zcash. More than fifty of those builds won.

I treated every one as a field test of a single question: **what breaks when software, not a person, holds the keys?** Different chains, different venues, the same failure every time. The agent was trusted with the whole wallet or none of it. Ava is the answer I kept arriving at, built once and properly.

## What I hold to

- **A refusal is a feature.** An agent that says no with a typed reason beats one that quietly does something plausible.
- **Receipts over reports.** When the executor says it worked, you have a claim. When the chain says it, you have a fact.
- **Mainnet first, then the pitch.** A demo nobody can verify is a rumour.
- **The user should never paste a seed phrase.** Into anything. Ever.

## Also shipped

| | |
|:--|:--|
| [**sealed.cash**](https://sealed.cash) | Hold, send and earn on Starknet without publishing your salary or net worth. |
| [**Last Call**](https://lastcall-sol.vercel.app) | Convert PreStocks pre-IPO tokens before their deadline, even holding 0 SOL. |
| [**frens**](https://frenstrade.vercel.app) | Trade perps on Monad where your friends call the exit on your chart. Accept, counter or pass. |
| [**Exit Window**](https://github.com/kamalbuilds/exit-window) | Know the moment smart money in your Hyperliquid trade starts selling. |
| [**ram-sentinel**](https://github.com/kamalbuilds/ram-sentinel) | A Rust watchdog that tells you in plain English what to close before your Mac starts swapping. |

<details>
<summary><b>Track record</b></summary>
<br>

- Archway 2024, ArchID track winner. [buidl](https://dorahacks.io/buidl/13726) · [announcement](https://x.com/archwayHQ/status/1818368483819946256)
- Celestia, finalist. [buidl](https://dorahacks.io/buidl/12724)
- Lambda Hack Brussels, Dora track winner. [buidl](https://dorahacks.io/buidl/14080)
- Dchain 2024 winner. [buidl](https://dorahacks.io/buidl/14291)
- Algorand Change the Game 2023, DeFi track winner. [buidl](https://dorahacks.io/buidl/8000)
- Avalanche Frontier, second place. [buidl](https://dorahacks.io/buidl/10316)
- Polygon APAC DevX, Polygon ID track winner. [buidl](https://dorahacks.io/buidl/6059)
- ETHGlobal: [TradeSphere](https://ethglobal.com/showcase/tradesphere-5vdrw) · [XChain Investments](https://ethglobal.com/showcase/xchain-investments-4fu2t) · [Gas Protocol](https://ethglobal.com/showcase/gas-protocol-46m74)
- [1clickSUIDefi](https://x.com/1clicksuidefi), one-click DeFi on Sui

</details>

## Now

Ava is onboarding design partners: teams running agents that need to move real money without handing over the keys. If that is you, my DMs are open.

[getava.xyz](https://www.getava.xyz) · [X @kamalbuilds](https://x.com/kamalbuilds) · [LinkedIn](https://www.linkedin.com/in/kamal-singh7) · kamal@getava.xyz
