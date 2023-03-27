# Hansen33's Miner

Hansen33's Miner is a **high-performance**, closed-source **DERO miner for HiveOS** designed for ease of use and compatibility with various platforms. Built with the latest **AstroBWTv3 algorithm**, it optimizes mining efficiency and ensures the best possible experience for users.

Mining Fee: **Only 2% Fee**

# Features

- Highly optimized AstroBWTv3 algorithm for maximum mining efficiency
- Multi-threaded mining for improved performance on multi-core processors
- Automatic job caching and efficient handling of job updates
- Colorful console output for better readability and user experience
- Detailed hashrate reporting and submitted results tracking
- Easy-to-use command-line interface
- HiveOS Support
- AMD64 and ARM64 Architecture Supported

# Customized Version Available on Request!

We are excited to announce that we now offer a customized version of Hansen33's Miner on request. Whether you are a mining pool or an individual miner, we can create a branded version of the miner or a node-locked/wallet-locked version to suit your needs. We are also open to discussing other customizations you might require. Our customizations start at just 25 DERO, and we are happy to work with you to create the best possible mining experience. Contact us today to learn more about how we can help you optimize your mining setup.

# Getting Started

## HiveOS Guide

- For HiveOS users, see the [HiveOS Setup Guide](HiveOS.md)

## Prerequisites

- A Linux-based operating system (Supported on amd64 and arm64 architecture)
- A DERO wallet address

## Download and Installation

1. Download the latest binary release:

* AMD64 Architecture
```bash
wget https://dero-node.mysrv.cloud/files/hansen33s-dero-miner-linux-amd64 -O hansen33s-dero-miner
```

* ARM64 Architecture
```bash
wget https://dero-node.mysrv.cloud/files/hansen33s-dero-miner-linux-arm64 -O hansen33s-dero-miner
```

2. Make the binary file executable:

```bash
chmod +x hansen33s-dero-miner
```

3. Run the miner with the required flags:

```bash
./hansen33s-dero-miner -wallet-address "your-wallet-address" -daemon-rpc-address "mining-pool-address:port"
```

Replace "your-wallet-address" with your DERO wallet address and "mining-pool-address:port" with the address and port of the mining pool you want to mine on.

*If mining to own node, consider checking out [Hansen33 Mod](https://github.com/Hansen333/derohe-Hansen33-mod/releases)*

# Usage

```
Usage: ./hansen33s-dero-miner-linux-amd64 [OPTIONS]
Options:
  -batch-size uint
    	Batch size (default: 100000) (default 100000)
  -daemon-rpc-address string
    	mining node address <host:port> (default "community-pools.mysrv.cloud:10300")
  -dump-stats-in-tmp
    	Dump Miner Stats in /tmp/miner_*.txt files (default: false)
  -h	Show help
  -help
    	Show help
  -mining-threads int
    	Desired number of mining threads (default: number of CPU cores) (default 4)
  -turbo
    	2x output hash rate (default: false)
  -wallet-address string
    	Your dero wallet address. e.g dero1qy... (default "Will ask")
  -worker-name string
    	Worker name (default: empty)


```

# Acknowledgements

- [DERO Project](https://github.com/deroproject/derohe)
- [DERO Community Pools](https://community-pools.mysrv.cloud/)

👉 As part of the DERO community, I'm committed to delivering the best mining experience possible. I welcome your feedback and suggestions.

# ToDo

- Many More Optimisations (Stay tuned for updates)
- Release a version for Windows

