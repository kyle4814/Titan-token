# Titan ($TITAN) — Token Metadata

## Contract
| Field | Value |
|-------|-------|
| **Address** | `0x377C542E5A50908d94500f266fa7e4F5d033fBa7` |
| **Chain** | Base (8453) |
| **Name** | Titan |
| **Symbol** | TITAN |
| **Decimals** | 18 |
| **Total Supply** | 1,000,000,000 |

## Description
Titan ($TITAN) is the utility token powering the QuadNode autonomous infrastructure ecosystem on Base L2. It integrates flash loan arbitrage, revenue splitting via ConstitutionalGuard governance, and on-chain heartbeat monitoring.

## Logo
- `logo.svg` — vector source (512x512)
- `logo.png` — raster (512x512)
- `logo-256.png` — token list size (256x256)

## Files
- `token.json` — full token metadata (DexTools/DexScreener format)
- `base_tokenlist_entry.json` — entry for Base community token lists

## Free Listing Steps

### DexScreener (auto-populates)
DexScreener indexes Base tokens automatically once there is DEX liquidity. To update the profile for free:
1. Go to https://dexscreener.com/base/0x377C542E5A50908d94500f266fa7e4F5d033fBa7
2. Click "Update token info" — free, requires signing with deployer wallet
3. Upload logo, add description and social links

### DexTools (community token list)
DexTools reads from community-maintained token lists:
1. Push this repo to GitHub (e.g. `kylegraham/titan-token`)
2. Submit a PR to a Base community token list that DexTools indexes
3. Or submit directly at https://www.dextools.io/app/en/base/token-creator — free tier available

### CoinGecko (free)
1. Apply at https://www.coingecko.com/en/coins/new — requires DEX liquidity and trading volume
2. Fill in contract address, chain, links, logo
3. Review takes 1-4 weeks

### Uniswap Token List
1. Fork https://github.com/Uniswap/default-token-list
2. Add TITAN entry to `src/tokens/base.json`
3. Submit PR with logo in `assets/`

### Base Community Lists
1. Check if `ethereum-optimism/ethereum-optimism.github.io` accepts Base token submissions
2. Submit entry from `base_tokenlist_entry.json`
