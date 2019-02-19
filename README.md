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

* ENS: [0x4e978ed8A05b516D8130Ff7dF54Fbc8b7ceB6442](https://sidechain.aira.life/account/0x4e978ed8a05b516d8130ff7df54fbc8b7ceb6442)
* XRT: [xrt.4.robonomics.sid](https://sidechain.aira.life/account/0x093ac06910f23570292fd5027a4fa558ed4cd010)
* Factory: [factory.4.robonomics.sid](https://sidechain.aira.life/account/0xB12255b705dAe406D142c19787aA77859FECe0c6)
* Lighthouse: [airalab.lighthouse.4.robonomics.sid](https://sidechain.aira.life/account/0xe85764e29583224c1d063639d2aeeed7c389df4d) 

### XRT bridge

Based on PoA Networks [Token Bridge](https://github.com/poanetwork/token-bridge) deployed XRT to BXRT token bridge.

* Token bride contract: [0x61EeAe897841cdB305B47Aa30D7b6Dd383CC6A76](https://etherscan.io/address/0x61EeAe897841cdB305B47Aa30D7b6Dd383CC6A76)

To get some XRT on sidechain just send `XRT Beta 4` tokens to bridge contract in Ethereum mainnet.

### Useful links 

* Explorer: https://sidechain.aira.life 
* Public JSON-RPC: https://sidechain.aira.life/rpc
* Public WS: wss://sidechain.aira.life/ws
