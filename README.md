# Truffle-Spacebear

# Common Commandline in Truffle

ganache -> Active ganache network http://172.31.96.1:8585/
ganache --fork.network sepolia -> Active ganache network with sepolia http://172.31.96.1:8585/
truffle develop -> Active truffle network http://127.0.0.1:9545/
truffle migrate -> execute migrations files, compile the contracts and deploy to default network http://127.0.0.1:7545
truffle dashboard -> open the dashboard truffle instead the HDwallet
truffle debug <txHash> --network <network> -> truffle debug 0x721e58b1b66c6223c30e0a25754804bbf2298a1e7d328ef213b42b58aa144a16 --url ws://172.31.96.1:8545 --fetch-external

NOTE: <txHash> is from the tx hash after the deploy to the network. it's visible in etherscan website