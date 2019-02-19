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

* ENS: [0xaC4Ac4801b50b74aa3222B5Ba282FF54407B3941](https://sidechain.aira.life/account/0xaC4Ac4801b50b74aa3222B5Ba282FF54407B3941)
* XRT: [xrt.5.robonomics.sid](https://sidechain.aira.life/account/0x966EbbFD7ECbCF44b1e05341976e0652CFA01360)
* Factory: [factory.5.robonomics.sid](https://sidechain.aira.life/account/0xd899994dbb31F46bccddb36FEd53209e43cF4d88)
* Lighthouse: [airalab.lighthouse.5.robonomics.sid](https://sidechain.aira.life/account/0x202a09a451de674d2d65bf1c90968a8d8f72cf7b)

### XRT bridge

Based on PoA Networks [Token Bridge](https://github.com/poanetwork/token-bridge) deployed XRT to BXRT token bridge.

* Token bride contract: [0x61EeAe897841cdB305B47Aa30D7b6Dd383CC6A76](https://etherscan.io/address/0x61EeAe897841cdB305B47Aa30D7b6Dd383CC6A76)

To get some XRT on sidechain just send `XRT Beta 4` tokens to bridge contract in Ethereum mainnet.

### Useful links 

* Explorer: https://sidechain.aira.life 
* Public JSON-RPC: https://sidechain.aira.life/rpc
* Public WS: wss://sidechain.aira.life/ws
