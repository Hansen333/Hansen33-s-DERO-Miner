# Hansen33' DERO Miner Docker Image

This is a Docker image for the Hansen33's DERO Miner.

Support us by giving us a :star: at **docker**hub
- https://hub.docker.com/r/hansen333/dero-miner

## Prerequisites

Make sure you have Docker installed.

- [Docker for Windows](https://docs.docker.com/docker-for-windows/install/)
- [Docker for Mac](https://docs.docker.com/docker-for-mac/install/)
- [Docker for Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
- [Docker for CentOS](https://docs.docker.com/engine/install/centos/)
- [Docker for Debian](https://docs.docker.com/engine/install/debian/)


## Pull the image:

Get the docker image from the respository

```bash
docker pull hansen333/dero-miner:latest
```

## Run

Run the container and specify your DERO wallet address as an environment variable. Use the -e flag to set environment variables.

### Run in Forground

```bash
docker run -it -e DERO_WALLET=dero1qy07h9mk6xxf2k4x0ymdpezvksjy0talskhpvqmat3xk3d9wczg5jqqvwl0sn hansen333/dero-miner:latest
```

### Run in Background

```bash
docker run -d -e DERO_WALLET=dero1qy07h9mk6xxf2k4x0ymdpezvksjy0talskhpvqmat3xk3d9wczg5jqqvwl0sn hansen333/dero-miner:latest
```

* Before running in background, you should verify the `-workers` and `-mining-threads` config are set for maximum performance.

## Environment Variables

| Variable            | Description                                                 | Default                                                                 |
| ------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------- |
| DAEMON_RPC_ADDRESS  | Mining node address <host:port>                             | community-pools.mysrv.cloud:10300                                       |
| MINING_THREADS      | Desired number of mining threads per worker                 | Number of CPU cores                                                     |
| WORKER_NAME         | Worker name                                                 |                                                                         |
| WORKERS             | Number of miner processes                                   | 1                                                                       |

The following environment variables can be set during runtime:

- `DERO_WALLET` (required): Your DERO wallet address. Example: `-e DERO_WALLET=dero1qy...`
- `MINER_VERSION` (optional): The version of the Hansen33's DERO Miner to use. Defaults to "latest". Example: `-e MINER_VERSION=Version-0.5`
- `DAEMON_RPC_ADDRESS` (optional): Mining node address in the format `host:port`. Defaults to "community-pools.mysrv.cloud:10300". Example: `-e DAEMON_RPC_ADDRESS=192.168.0.1:1234`
- `MINING_THREADS` (optional): Desired number of mining threads per worker. Defaults to number of CPU cores. Example: `-e MINING_THREADS=8`
- `WORKER_NAME` (optional): Worker name. Defaults to empty. Example: `-e WORKER_NAME=my_worker`
- `WORKERS` (optional): Number of miner processes. Defaults to 1. Example: `-e WORKERS=2`

## Example command with environment variables:

```bash
docker run -d \
    -e DERO_WALLET=<your_dero_wallet_address> \
    -e DAEMON_RPC_ADDRESS=<mining_node_address> \
    -e MINING_THREADS=<number_of_mining_threads> \
    -e WORKER_NAME=<worker_name> \
    -e WORKERS=<number_of_miner_processes> \
    hansen333/dero-miner:latest
```