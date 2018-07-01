# geos

## What is geos?
`geos` is a command line generator for eos contracts. Written entirely in bash, `geos` allows for one to create and build eos smart contracts.

## How to use
`geos` can be added to your path, or you can call it directly from the command line.

To create a smart contract in your current directory, run:
```bash
geos create mycontract
```

After a project has been created, go into the directory and type `geos`. This will build the contract as well as the abi. In the future, I would also like to add a feature that tests the smart contract.

```
cd mycontract
geos
```
