# Blockalizer Smart Contract

Try running some of the following tasks:

```shell
npx hardhat compile
npx hardhat test
npx hardhat clean
npx hardhat run scripts/deploy_blockalizer_v3.ts --network goerli
npx hardhat verify --network goerli <IMPLEMENTATION_CONTRACT_ADDRESS>
npx hardhat node
```

## For main net

```
npx hardhat run scripts/deploy_blockalizer_v3.ts --network mainnet
npx hardhat verify --network mainnet 0xf80bbc9d5058c5c1b4bf399d369a3b3a191d1361
```

CONTROLLER CONTRACT ADDRESS `0x6c75d96849f34304A2a1Bd14e047C1A7c40364cd`
IMPLEMENTATION ADDRESS V1 `0xf80bbc9d5058c5c1b4bf399d369a3b3a191d1361`
IMPLEMENTATION ADDRESS V2 `0x0fa9288d6f3090c3456d84267dcfe8bed245cdc3`

## To update

```
npx hardhat run scripts/update_blockalizer_v4.ts --network mainnet
npx hardhat verify --network mainnet 0x0fa9288d6f3090c3456d84267dcfe8bed245cdc3
```
