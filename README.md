# Hansen33's Miner

Hansen33's Miner is a **high-performance**, closed-source **DERO miner** designed for ease of use and compatibility with various platforms. Built with the latest **AstroBWTv3 algorithm**, it optimizes mining efficiency and ensures the best possible experience for users.

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

## Docker Guide

- For Docker users, see the [Docker Guide](Docker.md)

## Prerequisites

- A Linux-based operating system (Supported on amd64 and arm64 architecture)
- A DERO wallet address

## Download the Miner

Download the latest binary release from the [Github repository](https://github.com/Hansen333/Hansen33-s-DERO-Miner/releases).

- For Windows and macOS, simply double-click on the downloaded file to run the miner.
- For Linux and other platforms, use the command line to navigate to the downloaded file and run the miner using the following command:

| Platform | Architecture | Download Link |
| -------- | ------------ | ------------- |
| Android  | ARM64        | [hansen33s-dero-miner-android-arm64.tar.gz](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-android-arm64.tar.gz) |
| Darwin   | AMD64        | [hansen33s-dero-miner-darwin-amd64.tar.gz](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-darwin-amd64.tar.gz) |
| Darwin   | ARM64        | [hansen33s-dero-miner-darwin-arm64.tar.gz](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-darwin-arm64.tar.gz) |
| FreeBSD  | AMD64        | [hansen33s-dero-miner-freebsd-amd64.tar.gz](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-freebsd-amd64.tar.gz) |
| Linux    | AMD64        | [hansen33s-dero-miner-linux-amd64.tar.gz](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-linux-amd64.tar.gz) |
| Linux    | ARM64        | [hansen33s-dero-miner-linux-arm64.tar.gz](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-linux-arm64.tar.gz) |
| Windows  | AMD64        | [hansen33s-dero-miner-windows-amd64.zip](https://github.com/hansen333/dero-miner/releases/latest/download/hansen33s-dero-miner-windows-amd64.zip) |

## Start Mining

- When prompted, enter your DERO wallet address to start mining.
- For an even better mining experience, use the options available to optimize the miner's performance.

## Consider the Hansen33 Mod

If you're mining to your own node, consider checking out [Hansen33 Mod](https://github.com/Hansen333/derohe-Hansen33-mod/releases) for enhanced features and performance stats.


# Usage

```
  -batch-size uint
    	Batch size (default: 100000) (default 100000)
  -daemon-rpc-address string
    	mining node address <host:port> (default "community-pools.mysrv.cloud:10300")
  -dump-stats-in-tmp
    	Dump Miner Stats in /tmp/miner_*.txt files (default: false)
  -enable-log
    	Enable log file (default: false)
  -gc int
    	Garbage collection percentage (default: 1000) (default 1000)
  -h	Show help
  -help
    	Show help
  -log-file string
    	Log file name (default "/home/lenny/derohe/hansen33s-dero-miner-linux-amd64.log")
  -mining-threads int
    	Desired number of mining threads per worker (default: number of CPU cores) (default 16)
  -turbo
    	2x output hash rate (default: false)
  -wallet-address string
    	Your dero wallet address. e.g dero1qy... (default "Will ask")
  -worker-name string
    	Worker name (default: empty)
  -worker-start-delay int
    	Delay in seconds before starting worker processes (default 1)
  -workers int
    	Number of miner processes (default 1)
```

# Acknowledgements

- [DERO Project](https://github.com/deroproject/derohe)
- [DERO Community Pools](https://community-pools.mysrv.cloud/)

👉 As part of the DERO community, I'm committed to delivering the best mining experience possible. I welcome your feedback and suggestions.

## Upcoming Developments

Get ready for the mining revolution! We are proud to announce that we are currently rewriting the codebase for an entirely new type of miner. This groundbreaking innovation has never been seen before in the world of cryptocurrency mining. Stay tuned for updates on our progress and be among the first to experience the future of mining.