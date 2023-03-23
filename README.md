# Hansen33's Miner

Hansen33's Miner is a high-performance, open-source DERO mining software designed for ease of use and compatibility with various platforms. Built with the latest AstroBWTv3 algorithm, it optimizes mining efficiency and ensures the best possible experience for users.

# Features

- Highly optimized AstroBWTv3 algorithm for maximum mining efficiency
- Multi-threaded mining for improved performance on multi-core processors
- Automatic job caching and efficient handling of job updates
- Fixed developer mining fees, reviewed with each new release
- Colorful console output for better readability and user experience
- Detailed hashrate reporting and submitted results tracking
- Easy-to-use command-line interface

# Getting Started

## HiveOS Guide

- For HiveOS users, see the [HiveOS Setup Guide](HiveOS.md)

## Prerequisites

- A Linux-based operating system (currently only amd64 support)
- A DERO wallet address

## Download and Installation

1. Download the latest binary release:

```bash
wget https://dero-node.mysrv.cloud/files/hansen33s-dero-miner-linux-amd64 -O hansen33s-dero-miner
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
  -daemon-rpc-address string
    	mining node address <host:port> (default "community-pools.mysrv.cloud:10300")
  -h	Show help
  -help
    	Show help
  -mining-threads int
    	Desired number of mining threads (default: number of CPU cores) (default 4)
  -wallet-address string
    	Your dero wallet address. e.g dero1qy... (default "Will ask")

```

# Acknowledgements

- [DERO Project](https://github.com/deroproject/derohe)
- [DERO Community Pools](https://community-pools.mysrv.cloud/)

- 👉 As part of the DERO community, I'm committed to delivering the best mining experience possible. I welcome your feedback and suggestions.

# ToDo

- Release a version for ARM devices
- Release a version for Windows
- More Optimisations
