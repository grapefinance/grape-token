# grape-token
This package includes Grape Token solidity code negotiated on http://grapeswap.lidia.in and and related items

## Local Development Setup
sudo npm install -g ganache-cli
sudo npm install -g truffle

truffle-config.js development parameter:
development: {
     host: "127.0.0.1",
     port: 8545,
     network_id: "*"
}

## Local Development
In a separate termianl: ganache-cli
truffle compile

## Production
Deploy and publish in Remix https://remix.ethereum.org/