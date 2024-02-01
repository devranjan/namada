## Overview

Namada serves as a Proof-of-Stake Layer 1 (L1) platform designed for interchain asset-agnostic privacy. Utilizing the CometBFT consensus, Namada empowers multi-asset shielded transfers for both native and non-native assets. The platform boasts comprehensive support for the Inter-Blockchain Communication (IBC) protocol, along with a seamlessly integrated Ethereum bridge.

Namada operates on a contemporary proof-of-stake system featuring automatic reward compounding and cubic slashing. Additionally, it incorporates a stake-weighted governance signaling mechanism. Users engaged in shielded transfers receive rewards in native protocol tokens as acknowledgment for their contributions to the privacy set.

To enhance user interaction with the protocol, Namada offers a dedicated multi-asset shielded transfer wallet, ensuring a secure and private experience for users.



## Warning

This is A Experimental code, try at your own risk!

## 💾 Installing

1. Install Pre-requisites:


```shell
sudo apt install curl tar wget clang pkg-config libssl-dev jq build-essential bsdmainutils git make libudev-dev protobuf-compiler ncdu -y
```

2. Install Rust and Setup:
   

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
To configure shell you may need to run this command: 

```shell
source "$HOME/.cargo/env"
```

3. Copy Namada repo from Github:


```shell
git clone https://github.com/anoma/namada
```

4. Set Namada as Directory.

```shell
cd namada
```

 
5. Run this command, this will Install from Source and compile a executable : "namada" : 


```shell
make install
```


After installation, the main `namada` executable will be available on path.

To find how to use it, check out the [User Guide section of the docs](https://docs.namada.net/user-guide/index.html).

For more detailed instructions and more install options, see the [Install
section](https://docs.namada.net/user-guide/install/index.html) of the User
Guide.

## ⚙️ Node Setup



### Dependencies

The ledger currently requires [CometBFT v0.37.2](https://github.com/cometbft/cometbft/releases/tag/v0.37.2) is installed and available on path. This can be achieved through following [these instructions](https://github.com/cometbft/cometbft/blob/main/docs/guides/install.md)
