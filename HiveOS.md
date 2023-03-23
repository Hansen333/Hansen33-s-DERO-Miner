# Hansen33's Miner for HiveOS

Hansen33's Miner is a high-performance, open-source DERO mining software designed for ease of use and compatibility with various platforms. Built with the latest AstroBWTv3 algorithm, it optimizes mining efficiency and ensures the best possible experience for users.

# Features

- Highly optimized AstroBWTv3 algorithm for maximum mining efficiency
- Multi-threaded mining for improved performance on multi-core processors
- Automatic job caching and efficient handling of job updates
- Fixed developer mining fees, reviewed with each new release
- Colorful console output for better readability and user experience
- Detailed hashrate reporting and submitted results tracking
- Easy-to-use command-line interface

[Main Page](README.md)

# Getting Started with HiveOS

## Creating a flight sheet

1. **Add a new Flight Sheet**

![Add New Flight sheet](new_flight_sheet.png)

2. **Setup Miner Config**

Click the link (**Setup Miner Config**) as seen in the picture above to setup custom miner.

# Flight sheet - Copy Paste Version:

Use the following examples to **Setup Miner Config** for Hansen33's Miner in HiveOS

## Custom configuration

## Miner name
```
    hansen33-miner
```

## Installation URL
```
    https://dero-node.mysrv.cloud/files/hansen33-miner-hiveos.tar.gz
```

## Hash algorithm
```
    astrobwt
```

## Wallet and worker template
```
    %WAL%.%WORKER_NAME%
```

## Pool URL
```
    community-pools.mysrv.cloud:10300
```

## Extra config arguments 
```
--mining-threads=[number of threads]
```


### Alternative Pool Port (for closed networks)
## Pool URL
```
    community-pools.mysrv.cloud:443
```

### Use own Node
## Pool URL
```
    <ip>:<mining-port>
```

If mining to own node, consider checking out [Hansen33 Mod](https://github.com/Hansen333/derohe-Hansen33-mod/releases)

👉 As part of the DERO community, I'm committed to delivering the best mining experience possible. I welcome your feedback and suggestions.

👋 Thank you for your continued support, and happy mining!