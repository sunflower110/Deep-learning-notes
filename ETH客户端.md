### 初始化区块链

``` geth --datadir D:\private-blockchain\my-chain init D:\private-blockchain\genesis.json ```

```geth --datadir D:\private-blockchain\my-chain init D:\private-blockchain\genesis-block_1.json```

```
geth --allow-insecure-unlock --datadir .  --networkid 15 console 2>>geth.log --mine --miner.etherbase=0xA78DD939E18EDB66dac7eCFAAE5E6E8b429b8075
 --dev --password "password.txt" --dev.period 1

```



``` geth --allow-insecure-unlock --datadir .  --networkid 15 console 2>>geth.log --mine --miner.etherbase=YOUR_ETHEREUM_ADDRESS_HERE
 --dev --password "password.txt" --dev.period 1 ```

