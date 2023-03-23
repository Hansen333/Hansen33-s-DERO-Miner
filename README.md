Hansen33's Miner

Hansen33's Miner is a high-performance, open-source DERO mining software designed for ease of use and compatibility with various platforms. Built with the latest AstroBWTv3 algorithm, it optimizes mining efficiency and ensures the best possible experience for users.

Features

- Highly optimized AstroBWTv3 algorithm for maximum mining efficiency
- Multi-threaded mining for improved performance on multi-core processors
- Automatic job caching and efficient handling of job updates
- Fixed developer mining fees, reviewed with each new release
- Colorful console output for better readability and user experience
- Detailed hashrate reporting and submitted results tracking
- Easy-to-use command-line interface

Getting Started

Prerequisites

- A Linux-based operating system
- A DERO wallet address

Download and Installation

1. Download the latest binary release:

wget https://dero-node.mysrv.cloud/files/hansen33s-dero-miner-linux-amd64 -O hansen33s-dero-miner

2. Make the binary file executable:

chmod +x hansen33s-dero-miner

3. Run the miner with the required flags:

./hansen33s-dero-miner -wallet-address "your-wallet-address" -mining-address "mining-pool-address:port"

Replace "your-wallet-address" with your DERO wallet address and "mining-pool-address:port" with the address and port of the mining pool you want to mine on.

Usage

Usage: hansen33s-dero-miner [OPTIONS]

Options:
  -wallet-address string   Your DERO wallet address. e.g. dero1qy...
  -mining-address string   Address to mine to. e.g. community-pools.mysrv.cloud:10300 (default)
  -h                        Show help
  -help                     Show help

Contributing

Contributions to Hansen33's Miner are welcomed and appreciated. Please fork the repository and submit pull requests for any improvements, bug fixes, or new features you'd like to see.

License

Hansen33's Miner is released under the MIT License. See the LICENSE file for more details.

Acknowledgements

- The AstroBWT project
- Intergalactic Mining's Uranus Miner
- DERO-AM's AstroBWT Miner

ToDo

- Add support for ARM devices
- Release a version for HiveOS
- Release a version for Windows
