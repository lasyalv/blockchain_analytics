# Meme Coin Analysis 
I have performed an in-depth analysis of the Dogwifhat (WIF) memecoin, focusing on its on-chain metrics, holder distribution, and trading behaviour. The analysis is conducted using Dune Analytics and aims to provide actionable insights into the token’s performance and investor behaviour.  

Here is the dashboard link with SQL queries: https://dune.com/lasya26/memecoinanalyais-extracredit

## Overview  
Dogwifhat (WIF) is a meme token on the Solana network that has attracted significant interest in the cryptocurrency market. This project analyses key performance dimensions of WIF, including:  
- **Holder Distribution**: Examining the number of token holders over time and their respective holdings.  
- **Trading Volume**: Measuring weekly/daily trading volumes in main liquidity pools and how the token’s volume share shifts across platforms.  
- **Volatility vs Trading Activity**: Investigating the relationship between spikes in trading volume and changes in price volatility and new vs returning traders.

## Data Sources  
Data for this analysis is sourced from Dune Analytics, leveraging on-chain transfers, DEX trade tables, wallet cohort information and token supply data.

## Key Insights  
- **Holder Growth**: The number of WIF token wallets increased from 220k to 250k over period November 2024 to present, suggesting growing interest or speculative uptake.  
- **Distribution Skew / Concentration Risk**: A small number of large wallets hold a disproportionately high share of the token, which may heighten risk of large sell-pressure or volatility.  
- **Volume & Market-Share Trends**: Weeks with high trading volume correspond with shifts in platform market-share and often precede price jumps.  
- **Volume-Volatility Correlation**: There is a noticeable relationship between heightened trading activity (especially via new traders) and increased token volatility, implying volume spikes may precede or accompany price movement.

## Methodology  
The analysis was conducted using SQL queries on Dune Analytics to extract transaction-level data, wallet cohort information and trading-platform volumes. Visualisations include:  
- Time-series charts of wallet counts and token holdings by size category.  
- Scatter-plots mapping volume vs volatility.  
- Stacked bar charts showing weekly trading volume alongside platform market-share.  
- Cohort charts tracking new vs returning trader participation over time.  
Each chart is accompanied by an interpretive caption explaining what is shown and what the pattern suggests.

