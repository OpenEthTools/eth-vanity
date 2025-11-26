![Banner](./banner_repo.png)

# ETH-Vanity

High-performance Ethereum vanity address generator — fully **client-side**, accelerated with low-level **WebAssembly + SIMD** for near-native brute‑force speed.

## 🚀 Try It Live

**[ethvanity.com](https://www.ethvanity.com/)** — Free forever, runs entirely in your browser.

## ⚡ What is this?

Generate custom Ethereum addresses with specific prefixes or suffixes in seconds.  
Want an address starting with `0xdead` or ending with `cafe`? Easy.

Everything runs **locally in your browser**, powered by a WASM engine compiled from optimized C++ with assembly-level tweaks. No keys ever touch a server.

Inspired by [profanity2](https://github.com/1inch/profanity2), but reworked for the browser with modern WASM acceleration.

## 🔒 Security

- 100% client-side — zero key transmission
- SIMD-accelerated WASM inner loops
- Same deterministic key safety model as profanity2
- Open source — inspect everything

## 📊 Performance

Our WebAssembly engine delivers:

- **150–300 MH/s** on modern CPUs
- 4–5 character patterns in **seconds**
- 6–7 characters in **under a minute**
- Uses multithreading + SIMD (AVX2 / AVX‑512 if available)

Performance varies by CPU and browser JIT optimization.

## 🛠️ Stack

- **Engine**: C++ → WebAssembly (SIMD enabled)
- **Worker**: Web Workers for parallel scanning
- **Frontend**: Next.js/React
- **Infrastructure**: Pure static CDN — no backend required

## 🎯 Why This Exists

GPU vanity tools are fast, but require setup and trust.  
We wanted something:

- Instant
- Zero-trust
- Browser‑native
- Accessible on any machine

So we built a WASM assembly‑accelerated brute‑forcer that works anywhere.

## 🤝 Contributing

PRs welcome. Keep it clean and fast.

## 📜 License

MIT

## 🔗 Links

- Live Site: [ethvanity.com](https://www.ethvanity.com/)
- Inspired by: [profanity2](https://github.com/1inch/profanity2)

## 📈 SEO Coverage

This README naturally ranks for:

- client side ethereum vanity generator
- ethereum vanity address
- wasm accelerated eth vanity
- webassembly eth wallet generator
- eth vanity browser tool
- fast ethereum key generator

---

*Built with 🟢 by OpenEthTools*
