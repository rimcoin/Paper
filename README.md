# Rimcoin Protocol

So, while other currencies like Bitcoin, LiteCoin, and Ethereum do exist; Rimcoin is trying to do better. 

# Figure A

HTTP Server: 

contains, 
* a list of all balances
* a list of all other servers (AKA nodes)
* the ability to contact another node
* a target node


# Example

Alice has 5 Rimcoin.
Bob has 2.6 Rimcoin. 

Alice broadcasts to a random node, Node A, send 2 Rimcoin to Bob. And here is my proof ID, to prove I own these Rimcoin.

Next, Node A updates it's balance file, then contacts all other nodes with the same data. 

Now, the Rimcoin network agrees that this is the balance file:

Alice has 3 Rimcoin. 

Bob has 4.6 Rimcoin. 

# Notes

When a new node joins, they contact a random node, to get the current nodes, and adds itself. Then, it contacts all other nodes, informing them a new node has joined, and this is their data.  

# Distribution

Rimcoin uses mining. 

Rimcoin does not use a blockchain, so Rimcoin mining is simply finding a hash below a certain value. 

You will ALWAYS be rewarded 50 coins, when you find a hash. 
