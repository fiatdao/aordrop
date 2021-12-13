# FIAT DAO - ERC1155 Airdrop MerkleTree distributor

### 1. Clone this repo
```shell
git clone https://github.com/fiatdao/airdrop-erc1155
```

### 2. Install dependencies
```shell
yarn install
```

### 3. Run tests
```shell
npx hardhat test
```

### 4. Deployment
```shell
// Rinkeby
npx hardhat --network rinkeby deploy-airdrop-test --erc1155token "" --tokenid "" --emergencyreceiver "" --weeksemergency ""

// Mainnet
npx hardhat --network rinkeby deploy-airdrop --erc1155token "" --tokenid "" --emergencyreceiver "" --weeksemergency ""
```

# Airdrop lists

The lists of entitled wallets in the Age of Romulus NFT airdrop program can be found [here](https://github.com/fiatdao/airdrop-erc1155/tree/main/data):
- [Amphora](https://github.com/fiatdao/airdrop-erc1155/blob/main/data/fiatdao_amphora_airdrop.json): [python script](https://colab.research.google.com/drive/13woncFVJ7KR29bLidRPMU-30QMp8v2GJ?usp=sharing)
- [Kithara](https://github.com/fiatdao/airdrop-erc1155/blob/main/data/fiatdao_kithara_airdrop.json): [python script](https://colab.research.google.com/drive/1Ffl-YsrvK5ganMV4A7aIOm7y31838GG_?usp=sharing)
- [Galea](https://github.com/fiatdao/airdrop-erc1155/blob/main/data/fiatdao_galea_airdrop.json): [python script](https://colab.research.google.com/drive/1HNu9r9tfAYKpJ7xLOJXMtbTEU8symVdV?usp=sharing)
- [Gladius](https://github.com/fiatdao/airdrop-erc1155/blob/main/data/fiatdao_gladius_airdrop.json): [python script](https://colab.research.google.com/drive/1rg4mjh1R6CuOcbgHteWaAuDd97AAmDGW?usp=sharing)
- Corona: Not yet dropped


# Active Contracts

## Mainnet Contracts

### Addresses

[MerkleDistributor Amphora](https://etherscan.io/address/0x3658D9be7eADadD55aCCBc31a6fD232aEC1719Ed#code) - `0x3658D9be7eADadD55aCCBc31a6fD232aEC1719Ed`

[MerkleDistributor Kithara](https://etherscan.io/address/0xe6052737E294E2C0c2D2f1160614eDD0b37f34A8#code) - `0xe6052737E294E2C0c2D2f1160614eDD0b37f34A8`

[MerkleDistributor Galea](https://etherscan.io/address/0xC914059e7742B8A2bdd750d8d26928A2E8db3A1d#code) - `0xC914059e7742B8A2bdd750d8d26928A2E8db3A1d`

`Amphora Merkle root hash: 0x802133371213b3157410bbda5c614b24be5130233817b77507f11664f32c2773`

`Kithara Merkle root hash: 0x93969ff1e8581377b49ff1578b7f1b1f44bcec01568f0e5928605dc04cd022b9`

`Galea Merkle root hash: 0x4fbf57a981dc20a1474f621a6a24e55b6748ddda0071d041b6bbdac7d3b33157`

### Distribution File
**Note:** The file used in the last deployment and root generation is [here](./scripts/airdrop.json). For the files from previous deployments, see the [data folder](https://github.com/fiatdao/airdrop-erc1155/blob/main/data).

## Rinkeby Contracts

### Addresses

[Rinkeby-FDT](https://rinkeby.etherscan.io/address/0xb9e8d9890b41eb4b21b52353a5d4671f48b9840f)
[ERC1155 Token](https://rinkeby.etherscan.io/address/0x53c319038c19820a50e07a8ac305fb9d641948d2)

[MerkleDistributor](https://rinkeby.etherscan.io/address/0xE3D597f96df4A499EA676A65913905054d9cB14F#code)

`Merkle root hash: 0x957731ff8ac28b02a89fa4821ca837e8846025eb75778176689062b0732390d7`

### Distribution File
**Note:** The file used in the deployment and root generation is [here](./scripts/airdrop-test.json).
