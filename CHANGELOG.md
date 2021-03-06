# Changelog
## v1.2.0
* [\#93](https://github.com/Robbin-Liu/go-binance-sdk/pull/93) [BREAKING] uprade to binance chain release 0.6.3

## v1.1.3
* [\#81](https://github.com/Robbin-Liu/go-binance-sdk/pull/81) [TX] support swap on a single chain 


## v1.1.2
* [\#88](https://github.com/Robbin-Liu/go-binance-sdk/pull/88) [RPC] wrap error for abci query when abci code is not 0

## v1.1.1
IMPROVEMENT
* [\#87](https://github.com/Robbin-Liu/go-binance-sdk/pull/87) [RPC] distinguish not found error for get timelock rpc
* [\#84](https://github.com/Robbin-Liu/go-binance-sdk/pull/84) [RPC] change interface of get timelock


## v1.1.0
IMPROVEMENT
* [\#82](https://github.com/Robbin-Liu/go-binance-sdk/pull/82) [RPC] refactor reconnection

## v1.0.9

FEATURES
* [\#71](https://github.com/Robbin-Liu/go-binance-sdk/pull/71) [RPC] add timelock query support 
* [\#73](https://github.com/Robbin-Liu/go-binance-sdk/pull/73) [RPC] add limit param to get depth api for RPC


## v1.0.8
IMPROVEMENTS
* [\#53](https://github.com/Robbin-Liu/go-binance-sdk/pull/53) [SOURCE] change the default source into 0
* [\#56](https://github.com/Robbin-Liu/go-binance-sdk/pull/56) [RPC] add reconnect strategy when timeout to receive response
* [\#61](https://github.com/Robbin-Liu/go-binance-sdk/pull/61) [KEY] support bip44 to derive many address from same seed phase

FEATURES
* [\#66](https://github.com/Robbin-Liu/go-binance-sdk/pull/66)  [API]  support set account flag transaction
* [\#70](https://github.com/Robbin-Liu/go-binance-sdk/pull/70)  [API]  support atomic swap transactions

BREAKING
* [\#57](https://github.com/Robbin-Liu/go-binance-sdk/pull/57) [API] add query option to getTokens api
