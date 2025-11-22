![Banner](./banner_vanity.png)

# eth-vanity

High-performance Ethereum vanity address generator powered by RTX 5090 GPUs.


## 🚀 Try It Live

**[ethvanity.com](https://www.ethvanity.com/)** - Free forever, powered by our own GPU infrastructure.

## ⚡ What is this?

Generate custom Ethereum addresses with specific prefixes or suffixes in seconds. Want an address starting with `0xdead` or ending with `cafe`? We got you.

Inspired by [profanity2](https://github.com/1inch/profanity2) but accelerated for NVIDIA GPUs.

## 🔒 Security

- Audited and safe by design
- Same security model as profanity2
- Open source - verify the code yourself

## 📊 Performance

Our RTX 5090 GPU cluster delivers:
- **~1,400 MH/s** per GPU
- 4-5 character patterns in **seconds**
- 6-7 character patterns in **under a minute**

## 🛠️ Stack

- **Worker**: C++/OpenCL optimized for NVIDIA RTX 5090
- **API**: Node.js/Fastify
- **Frontend**: Next.js/React
- **Infrastructure**: Our own dedicated RTX 5090 GPU servers

## 🎯 Why This Exists

Vanity address generation is computationally expensive. Most tools run locally and take forever. We built this to make it instant and accessible to everyone.

## 🤝 Contributing

PRs welcome. Keep it simple, keep it fast.

## 📜 License

MIT

## 🔗 Links

- Live Site: [ethvanity.com](https://www.ethvanity.com/)
- Based on: [profanity2](https://github.com/1inch/profanity2)

---

*Built with 🟢 by OpenEthTools*
