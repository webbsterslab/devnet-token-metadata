# Devnet Token Metadata

Public repository hosting metadata for Solana devnet test tokens used in the Dupeiter ecosystem.

## Test Tokens

### Mock WBTC
- **Mint Address**: `DmXzkJ9MYZaRyKfMTDq4aRXfJGa6EES1sqBfyQZCJFXD`
- **Symbol**: WBTC
- **Decimals**: 8
- **Mainnet Equivalent**: `3NZ9JMVBmGAqocybic2c7LQCJScmgsAZ6vQqTDzcqmJh`
- **Metadata URL**: https://raw.githubusercontent.com/webbsterslab/devnet-token-metadata/main/wbtc-metadata.json
- **Icon Source**: Solana Labs Token List (mainnet WBTC logo)

### Mock WETH
- **Mint Address**: `4jVKVCiLU2ERrFoxSxvJp7GzJcJyntAp5r4RadWRcp8E`
- **Symbol**: WETH
- **Decimals**: 8
- **Mainnet Equivalent**: `7vfCXTUXx5WJV5JADk17DUJ4ksgau7utNKj4b963voxs`
- **Metadata URL**: https://raw.githubusercontent.com/webbsterslab/devnet-token-metadata/main/weth-metadata.json
- **Icon Source**: Solana Labs Token List (mainnet WETH logo)

### Mock USDT
- **Mint Address**: `DwdZXtYtxu8NjF4foBXkXE5Gn3Z9sfUP5E2vvp3q7Zfu`
- **Symbol**: USDT
- **Decimals**: 6
- **Mainnet Equivalent**: `Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB`
- **Metadata URL**: https://raw.githubusercontent.com/webbsterslab/devnet-token-metadata/main/usdt-metadata.json
- **Icon Source**: Solana Labs Token List (mainnet USDT logo)

## Usage

These tokens are available on Solana devnet for testing purposes. Each token has metadata that displays properly in wallets like Phantom when connected to devnet.

## Token Icon Strategy

All token icons are sourced from the **official Solana Labs token list** to ensure consistency with mainnet tokens and compatibility across wallets and dApps.

### Icon URL Format
```
https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/{MAINNET_MINT_ADDRESS}/logo.{png|svg}
```

### Why Solana Labs Icons?
- **Official Source**: Maintained by Solana Labs, trusted across the ecosystem
- **Consistency**: Same icons users see on mainnet in Phantom, Solflare, etc.
- **No Maintenance**: No need to host/maintain custom icon files
- **Instant Recognition**: Users immediately recognize familiar token logos
- **CDN Performance**: GitHub CDN ensures fast global delivery

### Current Token Icons
| Token | Mainnet Mint | Icon URL |
|-------|--------------|----------|
| USDC | `EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v` | [logo.png](https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v/logo.png) |
| USDT | `Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB` | [logo.svg](https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB/logo.svg) |
| WBTC | `3NZ9JMVBmGAqocybic2c7LQCJScmgsAZ6vQqTDzcqmJh` | [logo.png](https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/3NZ9JMVBmGAqocybic2c7LQCJScmgsAZ6vQqTDzcqmJh/logo.png) |
| WETH | `7vfCXTUXx5WJV5JADk17DUJ4ksgau7utNKj4b963voxs` | [logo.png](https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/7vfCXTUXx5WJV5JADk17DUJ4ksgau7utNKj4b963voxs/logo.png) |
| SOL | `So11111111111111111111111111111111111111112` | [logo.png](https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/So11111111111111111111111111111111111111112/logo.png) |

## Metadata Format

Each JSON file contains:
- Token name and symbol
- Description
- **Icon URL** (from Solana Labs token list)
- Token decimals
- Devnet and mainnet mint addresses
- Attributes (token type, network, mainnet equivalent, purpose)
