# Rust eth crypto wallet

In order to run the project a .env file is required containing an endpoint for connecting to an Ethereum network using WebSockets. 

For example:
```
INFURA_RINKEBY_WS=wss://rinkeby.infura.io/ws/v3/08xxxxxxxxx
```
The INFURA_RINKEBY value is an endpoint address from infura.io, however it can be any valid address to an Ethereum network WebSocket endpoint. Infura.io is an easy way to gain access to an Ethereum node endpoint.