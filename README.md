# Hey, I'm Solya 👋

Solana validator operator from Ukraine. Building open source tools for network decentralization.

## ⚡ Validator

I've been running a Solana validator since 2021. Working now with 0% commission on both inflation and MEV rewards. The node is deliberately hosted in São Paulo, Brazil, outside the US/EU datacenter majority, to actually contribute to geographic decentralization of the network.

DoubleZero connected · SFDP approved · Jito BAM · 0% MEV commission

🔗 [StakeWiz](https://stakewiz.com/validator/HwcVgFSgmfeeF7zGFUBLoVA8Hpx8rtwyfCrJ1npBaSVC) · [solya.studio](https://solya.studio)

## 🔭 SONDA

**[Solana Observatory for Network Decentralization Analysis](https://github.com/SolyaUk/sonda)**

Over the years of running a validator, I kept running into the same problem: the data you need to make good infrastructure decisions just isn't reliable. Choosing a datacenter, evaluating geographic distribution, comparing latency across regions — tools like validators.app and others often show inaccurate or conflicting location data, and there's no way to tell which source is right.

I started writing scripts to cross-check this stuff for myself. Then decentralization became more than just a personal concern — it became clear that the whole network needs better visibility into its own structure. That's when I decided to turn those private scripts into an open tool that anyone can use.

SONDA is the result:

- 🌍 **Cross-verified geolocation** — every IP checked against 4 independent providers (DB-IP, IPInfo, GeoJS, ip-api), discrepancies detected and logged, not hidden
- 📡 **DoubleZero as ground truth** — protocol-verified device locations automatically correct what geo databases get wrong
- 🗺️ **Full infrastructure map** — not just validators, but DZ devices, BAM nodes, Jito block engines, Harmonic, Rakurai, NTP servers, RPC nodes, co-hosted nodes — 16 role types total
- 📊 **Multi-dimensional metrics** — Nakamoto coefficient, HHI, Gini, Shannon entropy across country, ASN, city, and validator dimensions simultaneously
- ⚡ **Fast** — full mainnet scan of ~5,000 nodes in ~17 seconds with intelligent per-source caching
- 🔓 **Open source** — MIT licensed, all data sources documented

Public dashboard coming soon at [sonda.network](https://sonda.network)

## 🛠️ Tech

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Solana](https://img.shields.io/badge/-Solana-9945FF?style=flat&logo=solana&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
