# Fennec Wallet v1.0.0 — Build 1

**Release date:** 2026-06-15

## What's new

### Multi-chain wallet
- EVM chains (40+): Ethereum, BNB Chain, Polygon, Arbitrum, Optimism, Base, Avalanche, and more
- Solana (SOL, SPL tokens)
- Bitcoin (BTC, BIP84 native SegWit)
- Tron (TRX, USDT-TRC20)
- XRP (Ripple)
- Litecoin (LTC, BIP84 SegWit)
- Dogecoin (DOGE)
- TON (The Open Network, USDT Jetton)
- Stellar (XLM, USDC)

### Payment Gateway (Android only)
- Merchant mode with USDT-TRC20 payment requests
- Real-time payment monitoring via Trongrid
- 1% automatic platform fee collection
- Webhook notifications to merchant systems (HMAC-SHA256 signed)
- WiFi local mode and Internet mode (static payment page)
- QR code generation with countdown timer

### Security
- Biometric + PIN authentication
- ProGuard/R8 obfuscation with aggressive repackaging
- Network security hardening (cleartext traffic blocked)
- Hermes JS engine (no source maps in release builds)

### Features
- Swap aggregation: 1inch, THORChain, LiFi
- NFT browsing and sending
- React Query with persistent cache
- i18n: English, Spanish, French, Portuguese

## Build details
- Platform: Android
- Min SDK: API 24 (Android 7.0)
- Target SDK: API 34 (Android 14)
- Architecture: armeabi-v7a, arm64-v8a, x86, x86_64
- JS engine: Hermes
- Bundle: React Native 0.74.5
