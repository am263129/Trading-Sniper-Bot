# Raydium Sniper Trading Bot

## Overview

The **Raydium** **Sniper Bot** is a high-speed, precision trading bot engineered to dominate the **Raydium DEX** on the **Solana** blockchain, specializing in sniping newly launched tokens the moment liquidity pools go live. Built for maximum efficiency, this bot scans, analyzes, and executes trades faster than manual traders, ensuring you secure the best possible entry prices on trending Solana tokens. Whether you're a **DeFi sniper**, **scalper**, or **liquidity hunter**, this tool gives you the competitive edge in the ultra-fast world of **Raydium token launches**.

<img src = "https://github.com/husreodev/Solana-raydium-sniper-bot/blob/main/public/hq720.jpg" style = "width:100%" />

**Solana Raydium Sniper Bot** that listens to new Raydium USDC or SOL pools and buys tokens for a fixed amount in USDC/SOL. Depending on the speed of the RPC node, the purchase usually happens before the token is available on Raydium UI for swapping. This version is free, but it can still generate stable profits of several hundred dollars per day. You can run it for a few hours to check the earnings. If you want to purchase the premium version, plz contact [here](https://t.me/fenrow)

## Key Features

- **Instant Liquidity Detection** – Monitors Raydium for new pools and executes trades in milliseconds.
- **Precision Sniper Entry** – Customizable buy/sell parameters to optimize entries and exits.
- **Solana Speed Advantage** – Leverages Solana’s low fees and high throughput for rapid transactions.
- **Dynamic Profit-Taking** – Auto-sells with trailing stops, limit orders, or target-based exits.
- **Rug-Pull Protection** – Detects malicious contracts and avoids high-risk tokens.

## CONFIG
Configure the script by updating `.env.copy` file.

2. PRIVATE_KEY = private key
3. RPC_ENDPOINT = RPC endpoint
4. RPC_WEBSOCKET_ENDPOINT websocket RPC endpoint
5. QUOTE_MINT = which pools to snipe, USDC or WSO
6. QUOTE_AMOUNT = amount used to buy each new token
7. COMMITMENT_LEVEL = No modification required
8. CHECK_IF_IS_BURNED = liquidity burn check
9. CHECK_IF_IS_LOCKED = liquidity lock check
10. USE_SNIPE_LIST = buy only tokens listed in snipe-list.txt
11. SNIPE_LIST_REFRESH_INTERVAL = how often snipe list should be refreshed in milliseconds
12. CHECK_IF_MINT_IS_RENOUNCED = script will buy only if mint is renounced
13. MIN_POOL_SIZE = script will buy only if pool size is greater than specified amount
14. TAKE_PROFIT=50 = in %
15. STOP_LOSS=30 = in %
16. BIRDEYE_API_KEY= (TP/SL, Burn/Lock) You can use the default link in the .env file, it works fine and does not need to be changed. Go here if you want to generate it yourself : https://docs.birdeye.so/docs/authentication-api-keys

## How It Works

- **Scans Raydium Pools** – Tracks new token listings in real time.
- **Analyzes Token Metrics** – Filters by liquidity, contract safety, and trading volume.
- **Executes Lightning-Fast Trades** – Buys at launch and sells at predefined profit targets.
- **Secures Gains Automatically** – Implements stop-losses and take-profit strategies.
  

