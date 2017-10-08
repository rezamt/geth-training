## Ethereum Private Network using Geth

```

geth --datadir=./firstnode --port 30303 init genesis.json
geth --datadir=./firstnode --port 30303  --networkid 100 --rpcapi personal,web3,eth --rpc  --rpccorsdomain "*"

```


