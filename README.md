# moechain-tx

 this module is based on ethereumjs-tx and moechain have changed many code.
 
 the origin module link: 
 [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)
 
 # Useage:
 
 ```
  var rawTx = {
    to: '0000000000000000000000000000000000000000',
    value: '00',
    data: '7f7465737432000000000000000000000000000000000000000000000000000000600057',
  }
 var tx = new Transaction(rawTx)
 ```
