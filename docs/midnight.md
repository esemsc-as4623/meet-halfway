the privacy challenge
- ID contains a lot of data (multi-purpose)
- but not all data is relevant in all situations
- we want to show proof without revealing all parts of identity (selective disclosure)

blockchain
- 1st Gen = transact
- 2nd Gen = smart contracts
- 3rd Gen = governance
- 4th Gen = privacy (Midnight)

tokenomics
- NIGHT = governance / utility token (native blockchain token)
    - send, receive, vote
- DUST = network resource
    - produced by the amount of NIGHT held in wallet
    - when you create a transaction, you generate DUST
    - DUST is re-generated as long as NIGHT is held

zero-knowledge circuits
- verify info without revealing info
- convience a verifier by proving that all the other possibilities cannot be true
- mathematical tools that encode a program into a set of constraints
- circuits generate proofs for confidential computations and verifiability

smart contracts
- contracts are off-chain
- zero-knowledge proofs are on-chain
- compact smart contract language (TypeScript syntax)
- compact compiler
- GitHub example / awesome dapps
    - https://github.com/midnightntwrk/midnight-awesome-dapps

proof server
- available on Docker

midnight libraries
@midnight-ntwrk/compact-runtime // provide tools to interact with contract implementation
@midnight-ntwrk/dapp-connector-api // interact with wallet on browser
@midnight-ntwrk/ledger // work with the on-chain ledger
@midnight-ntwrk/midnight-js-contracts // tools to work on contracts
@midnight-ntwrk/zswap // create private transactions

workflow
- write a contract
- compiler creates JavaScript implementation
- compiler provides TypeScript types

example
- example-counter
- witness to ensure data provided stays private
- open zeppelin (N)FTs https://github.com/OpenZeppelin/compact-contracts
- midnight app https://www.npmjs.com/package/create-midnight-app

https://docs.midnight.network

BOUNTY TBD