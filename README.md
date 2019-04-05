Robonomics 1.0 sidechain
------------------------

This repository includes Airalab owned Ethereum sidechain for Robonomics network.

### Running a node

> Parity-ethereum should be installed before.

    git clone https://github.com/airalab/airalab-sidechain && cd airalab-sidechain
    ./start.sh

### Validator set

* `0xfc219ef10A1F7e958E3F4F609e8ABB3b98D22FF0`

### Robonomics instance

Robonomics are instantiated on Airalab sidechain with ENS prefix `sid` (like a Debian experimental :).

> In the sidechain lighthouse providers have no XRT emission, only fees.

Deployed contracts:

* ENS: [0xaC4Ac4801b50b74aa3222B5Ba282FF54407B3941](https://explorer.aira.life/addr/0xaC4Ac4801b50b74aa3222B5Ba282FF54407B3941)
* XRT: [xrt.5.robonomics.sid](https://explorer.aira.life/addr/0x966EbbFD7ECbCF44b1e05341976e0652CFA01360)
* Factory: [factory.5.robonomics.sid](https://explorer.aira.life/addr/0xd899994dbb31F46bccddb36FEd53209e43cF4d88)
* Lighthouse: [airalab.lighthouse.5.robonomics.sid](https://explorer.aira.life/addr/0x202a09a451de674d2d65bf1c90968a8d8f72cf7b)

### XRT bridge

Based on PoA Networks [Token Bridge](https://github.com/poanetwork/token-bridge) deployed for XRT to BXRT token bridge.

* Token bride contract: [Coming soon](https://etherscan.io/address/0x00)

To get some XRT on sidechain just send `XRT` tokens to bridge contract in Ethereum mainnet.

### Useful links 

* Stats: https://sidechain.aira.life 
* Explorer: https://explorer.aira.life 
* Public node:
    * JSON-RPC: `https://sidechain.aira.life/rpc`
    * WebSocket: `wss://sidechain.aira.life/ws`
