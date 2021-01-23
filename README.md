# MTP-Tradehub-Testnet
Mai Te Pora Testnet Image for installing an MTP Switcheo Tradehub testnet node

This testnet is intended to be an "Always available" testnet, which mirrors the latest production Tradehub version.

## Installation
1. From your node's shell, download the appropriate package tarball (releases are [here](https://github.com/Mai-Te-Pora/MTP-Tradehub-Testnet/releases))

The current release is `v1.11.0`

```bash
curl -L https://github.com/Mai-Te-Pora/MTP-Tradehub-Testnet/releases/download/<release tag>/install-testnet.tar.gz | tar -xz
```

2. Follow the official installation instructions from [here](https://github.com/Switcheo/tradehub#install-switcheoctl).

   **NOTE:** In step 1 of the installation procedure, use the following node info for persistent peers
   ```bash
   f04611ca2f10284553e16c817d1df7832604fb52@128.199.183.3,1c57adf4b5e60b630748b5125a2b4a11e036d7da@188.166.191.195
   ```

## Nodes/Ports
Initial nodes for accessting the MTP blockchain are:
- 128.199.183.3
- 188.166.191.195

The usual tradehub/tendermint services are available on the following ports:
* 5001  - Cosmos SDK API and REST API
* 1317  - Cosmos SDK API
* 5000  - REST WS
* 26657 - Tendermint API 
