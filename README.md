# QRL Web Tools

A collection of web-based utilities for the QRL (Quantum Resistant Ledger) network.

## Tools

- **Wallet Generator** - Generate QRL wallets offline
- **Address Info** - Validate and inspect QRL addresses
- **Hexseed Validator** - Validate hexseed format
- **Mnemonic Tester** - Test and validate mnemonic phrases

## Use

**Either**:

- Download the latest [release](https://github.com/theQRL/webtools/releases) and open index.html in a modern browser (one which [supports webassembly](https://caniuse.com/#feat=wasm))

**or**:

- Run a local web server:

```bash
npm install
npm run dev
```

## Help

- [Discord community](https://discord.gg/jBT6BEp)
- <support@theqrl.org>

## Developing/Building from source

### Dependencies

- Node.js (see .nvmrc for version)
- npm

### Project setup

```bash
npm install
```

### Development server

```bash
npm run dev
```

### Production build

```bash
npm run build
```

### Preview production build

```bash
npm run serve
```
