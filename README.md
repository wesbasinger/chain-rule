# Chain Rule - An Equation Based Blockchain

## Block Schema

```
{
    index: auto created value,
    equation: string,
    answer: int,
    previous: hash,
    next: hash,
    confirmers: [address],
    creator: address,
    creationTime: timestamp,
    confirmationTime: timestamp
}
```

## Block Creation

Every node runs a program that downloads the entire blockchain history and verifies it.  If there a block to be confirmed, it will alert user to solve and try to confirm it.  Otherwise it will create a block and broadcast it to all connected nodes.

## Block Rewards

Rewards are paid for all types of participation and are not transferable.  You are rewarded for the following actions.

1. Creating a block
2. Submitting a solution to a block that leads to the block being confirmed

## Security

A majority of the participating nodes must agree on next block for it to be added to the blockchain.