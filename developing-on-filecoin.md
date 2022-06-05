# Developing on Filecoin

This gist contains links to the resources referenced in the HackFS workshop [Developing on Filecoin](https://youtu.be/aGCpq0Xf-w8).

Slides for this presentation can be found [here](https://drive.google.com/file/d/1ptghAQYCAWnXUNYxLwUZoiGAPjt6rVex/view?usp=sharing).

## Filecoin Workshops at HackFS

- [How Filecoin Works: an in-depth system overview](https://youtu.be/P28aNAdZDi4) by Juan Benet
- [Developing on Filecoin](https://youtu.be/aGCpq0Xf-w8) by Pooja Shah 
- [Getting Started with Filecoin (Textile Powergate)](https://youtu.be/SePJrCLUM0g) by Andrew Hill
- [Textile: Getting Started](https://youtu.be/IZ8M9m9_uJY) by Carson Farmer
- [Building an App with Filecoin from scratch - using Slate Components & Powergate](https://youtu.be/FJjPMKRy8xQ) by Jimmy Lee
- [Build a chain explorer using Lotus](https://youtu.be/QhGhZgUL9iM) by Vaibhav Saini
- [Using Lotus](https://youtu.be/3dkzLJuv1jc) by Whyrusleeping and Aayush Rajasekaran

## Filecoin Core Technologies

1. IPFS Products and Protocol Implementations
2. Filecoin-backed IPFS Pinning Services (FPS)
3. Powergate
4. Filecoin Protocol Implementations

### 1. IPFS Products and Protocol Implementations

- [ipfs.io](https://ipfs.io)
- [IPFS Docs](https://docs.ipfs.io/)
- [go-ipfs](https://github.com/ipfs/go-ipfs)
- [js-ipfs](https://github.com/ipfs/js-ipfs)
- [IPFS Cluster](https://cluster.ipfs.io/)
- [ipfs-http-client](https://github.com/ipfs/js-ipfs/tree/master/packages/ipfs-http-client#readme)
- [IPFS Desktop](https://github.com/ipfs-shipyard/ipfs-desktop)
- [IPFS Companion](https://github.com/ipfs-shipyard/ipfs-companion)
- IPFS Pinning Services:
	- [Pinata](https://pinata.cloud/)
	- [Temporal](https://temporal.cloud/)
	- [Infura](https://infura.io/)

### 2. Filecoin-backed IPFS Pinning Services (FPS)

- [Overview of FPS Services on Filecoin Docs](https://docs.filecoin.io/build/core-products/filecoin-backed-pinning-services/)
- [IPFS Pinning Summit YouTube Playlist](https://www.youtube.com/playlist?list=PLuhRWgmPaHtTvsxuZ9T-tMlu_v0lja6v5)
- Filecoin-backed IPFS Pinning Services (currently live):
	- [Textile Buckets](https://docs.textile.io/buckets/)
	- [Pinata](https://pinata.cloud/): Coming soon
	- ChainSafe: Coming soon

### 3. Powergate

- [Overview of Powergate on Filecoin Docs](https://docs.filecoin.io/build/core-products/powergate/)
- [Textile Powergate Docs](https://docs.textile.io/powergate/)
- [Getting Started with Filecoin (Textile Powergate)](https://youtu.be/SePJrCLUM0g) Workshop for HackFS
- [Into the Powergate](https://youtu.be/aiOTSkz_6aY) Presentation for IPFS Pinning Summit

### 4. Filecoin Protocol Implementations

- [Overview of Protocol Implementations on Filecoin Docs](https://docs.filecoin.io/build/core-products/protocol-implementations/)
- [Filecoin spec](https://filecoin-project.github.io/specs/)
- [How Filecoin Works: an in-depth system overview](https://youtu.be/P28aNAdZDi4) by Juan Benet
- [Announcing Filecoin Implementations in Rust and C++](https://filecoin.io/blog/announcing-filecoin-implementations-in-rust-and-c++/) on Filecoin Blog
- [lotus](https://github.com/filecoin-project/lotus), main reference implementation, written in Go
	- [Lotus Docs](https://lotu.sh/) 
	- [Lotus JS API](https://github.com/filecoin-shipyard/js-lotus-client)
	- Lotus JSON-RPC API for [storage miner](https://github.com/filecoin-project/lotus/blob/master/api/api_storage.go), [full node](https://github.com/filecoin-project/lotus/blob/master/api/api_full.go), and [both](https://github.com/filecoin-project/lotus/blob/master/api/api_common.go)
- [forest](https://github.com/chainsafe/forest), Rust implementation
- [fuhon](https://github.com/filecoin-project/cpp-filecoin), C++ implementation

## Example Use Cases and Architectures

**Storing static data**
- [Audius](https://audius.co/) embeds IPFS nodes locally into user software

**Publish a static website**
- Use [Fleek](https://fleek.co/), [Unstoppable Domains](https://unstoppabledomains.com/), or [ENS](https://ens.domains/) to easily deploy websites to IPFS
- [Cloudflare's IPFS Gateway](https://developers.cloudflare.com/distributed-web/ipfs-gateway)

**Build dweb infrastructure, like a pinning service**
- Powergate Pinning Service example application [Docs]https://docs.filecoin.io/build/examples/simple-pinning-service/overview/) and [Repo](https://github.com/filecoin-shipyard/powergate-pinning-service)

**File storage and other dynamic applications**
- [Slate](https://github.com/filecoin-project/slate), a full-featured application built on Filecoin
- [Slate Design System](https://slate.host/system), a design system with components you can use in your own applications
- Meme Marketplace example application [Docs](https://docs.filecoin.io/build/examples/meme-marketplace/overview/) and [Repo](https://github.com/filecoin-shipyard/meme-marketplace)

**Chain explorers**
- [Filscan](https://filscan.io/)
- [Filfox](https://filfox.io/en)
- Filecoin Network Inspector example application [Docs](https://docs.filecoin.io/build/examples/network-inspector/overview/) and [Repo](https://github.com/filecoin-shipyard/filecoin-network-inspector/)

**Wallets**
- [Glif Web Wallet](https://wallet.glif.io/?network=t)
- [Filecoin remote signing libraries](https://github.com/Zondax/filecoin-signing-tools)

## Support

- [Filecoin Docs](http://docs.filecoin.io/)
- [Filecoin Shipyard](https://github.com/filecoin-shipyard/), GitHub organization with several example projects and experiments to learn from
- [Filecoin Slack](https://filecoin.io/slack)
	- During HackFS:
		- #hfs-sponsor-filecoin-team
		- #hfs-hackfs-support
		- #hfs-filecoin-ipfs-help
	- Beyond HackFS:
		- #fil-storage-dev
		- #fil-help
- [Filecoin Discussion Forum](https://discuss.filecoin.io)
- [Filecoin Developer Office Hours](https://forms.gle/ZMgz2nyEqotrAQdH7)
- [Filecoin Development Grants](https://filecoin.io/grants)