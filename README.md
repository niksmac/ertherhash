# ertherhash
Simple website to show current Ethereum Ether Hash

## API
Using [etherchain.org](https://etherchain.org/frontier) as API

## When to Use
When you want to generate the Ethereum Genesis block

### Genesis block generator

[mk_genesis_block.py](https://github.com/ethereum/genesis_block_generator)

```
python mk_genesis_block.py --extradata <hash_from_#1028201> > genesis.json
```

here the `<hash_from_#1028201>` can be found
