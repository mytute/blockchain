# blockchain
blockchain tute

## money transfer method   

1. open ledger.

ledger is public.
everyone can see money have each one.
everyone can decide transaction valid or not.
invalid transaction can't add to open ledger.

2. distributed ledger.    
some person have copy of the full ledger.    
so is not centralized and it is distribute across node.  
now problem is the asynchronous the copy of ledger.

3. miners    
miners are special nodes.  
task of nodes   
1.validate the new transaction.
2.find special key.   


# video of ginesis block ru

to start nginx service    

```bash
$ /ect/init.d/nginx start
```   


to get cmd details

```bash
$ ./haqqd

# add-genesis-account    Add a genesis account to genesis.json
# add-wasm-genesis-message  wasm genesis subcommands    
# collect-gentxs    collect genesis txs and output a genesis.json file    
# debug   tool for helping with debugging your application
# export Export state to JSON
# gentx  Generate a genesis tx carrying a self delegation.
# help  Help about any command
# init Initialize private validator. p2p, genesis, and application configuration files
# keys  Manage your application keys.
# migrate migrate genesis to a specified target version.
# query  Querying subcommands
# start Run full node
# status  Query remote node for status    
# tendermint   Tendermint subcommands ()   
# tx  Transactions subcommands   
# unsafe-reset-all Reset the blockchain datebase, removes address bllk files. and reset data/priv_validator_state.json to the genesis state    
# validate-genesis validate the genesis file at the default location or at the location passed as an arg     
# version Print the application binary version information

```    

to see sub commands for transaction

```bash
$ ./haqqd tx

# bank  Bank transaction subcommands
# broadcast  Broadcast Transactions generate offline
# crisis Crisis transactions subcommands
# decode  Decode an binary encoded transaction string
# dex  dex transaction subcommands
# distribution distribution transactions subcommands
# encode  Encode transaction generated offline
# evidence Evidence transaction subcommands
# gov Governance transaction subcommands
# haqq haqq transaction subcommands  
# ibc IBC transaction subcommands (nter-module communication protocol that bridges different blockchains to facilitate communication and feature exchanges between networks with different infrastructure designs and consensus algorithms.)
# ibc-transfer IBC fungible token transfer transaction subcommands
# multisign Generate multisign signature for transactions generated offline.   
# sing Sign a transaction generated offline
# sign-batch Sign transaction batch files
# slashing Slashing transaction subcommands
# staking staking transaction subcommands (like fix deposit on bank but here in vallet)
# validate-signature Validate transactions signature    
# vesting vesting transaction subcommands    
# wasm  wasm transaction subcommands (WebAssembly)
#

```  

to get bank send command

```bash
$ ./haqqd bank send

# this will show all the commands
# haqqd tx bank send [from_key_or_address] [to_address] [amount] [flags]

# you can see "flags" in following text    
# --fees string Free to pay along with transaction eg:10oatom (commission)
# --memo string  Memo to send along with transaction (comment no limit of text )
```  

to get query commands

```bash
$ ./haqqd query   
# account Query for account by address   
# auth Querying commands for the auth module    
# bank Querying commands for the bank module   
# block Get verified data for a the block at given height   
# dex Querying commands for the dex module
#
```  

to get all the account that connected in our system

```bash
$ ./haqqd keys list    
```  


to get get account by address that got by above address

```bash
$ ./haqqd query account <account-address>
```  

to get bank commands  for balance

```bash
$ ./haqqd query bank  # get commands
$ ./haqqd query bank balance <account-address> # get balance
$ ./haqqd query bank total <account-address> # get total of account

# results >
# amount : "300012798"
# denom : state
# amount : "30000"
# denom : token
```  

 mint  cmd  

```bash
$ ./haqqd query mint  # get commands
$ ./haqqd query params # give annual details
```  

to send coin to address

```bash
$ ./haqqd query tx # get command list
$ ./haqqd query tx bank send <name> <account-address> <type-of-coin># you can find by "./haqqd keys list" cmd  
# confirm transaction before signing and broadcasting [y/N]:Y
# it will return "txhash" code

# to see infomation about above transaction
$ ./haqqd query tx <txhash>
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```  

to start nginx service

```bash
$ /ect/init.d/nginx start
```    
