# CW20-ICS20-IBC-Transfer
Testnet CW20-ICS20 IBC Relayer

[![Testnet CW20 transfer from Juno to Sei](https://www.synergynodes.com/youtube/Synergy_Nodes_CW20_transfer.jpg)]

[![Testnet CW20 transfer from Juno to Sei](https://www.synergynodes.com/youtube/Synergy_Nodes_CW20-ICS20.jpg)]

## Links

```
https://blueprints.juno.giansalex.dev/#/contracts/juno16gckhheyql9f85r9ydmazdccc0pnwxx5xxxrwltygtx3kxjg57ksamkpym
https://junomint.com/
https://www.base64encode.org/
https://github.com/CosmWasm/cw-plus/tree/main/contracts
https://testnets.cosmosrun.info/
```

## Allow Code

```
{
  "allow": {
    "contract": "<cw-20-token-contract-address>"
  }
}
```

```
# Example 

{
  "allow": {
    "contract": "juno1d3pnlc086evh7d277vak6tpz6gmvw6gr6plwxzf5n2tl9zdtwf7qrdsn44"
  }
}
```

## Send Code

```
{
  "send": {
    "contract": "juno1qrhrjhln673kf0v4r2yn4d0nuh029gacp2zjk74nen27wh7xw48spl4an8",
    "amount": "100000000",
    "msg": "<encoded-message>"
  }
}
```

```
# Example

{
  "send": {
    "contract": "juno1qrhrjhln673kf0v4r2yn4d0nuh029gacp2zjk74nen27wh7xw48spl4an8",
    "amount": "100000000",
    "msg": "eyJjaGFubmVsIjoiY2hhbm5lbC03NiIsInJlbW90ZV9hZGRyZXNzIjoia3VqaXJhMXhlc3FyOHZqdnkzNGpodTAyN3pkNzB5cGwwbm5ldjVlaDQycHJwIn0="
  }
}
```
