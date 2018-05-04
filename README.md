# Rimcoin Protocol

Digital payments are not how they should be. You have to trust other individuals to handle YOUR transaction. 

So, while other currencies like LiteCoin, Bitcoin, and Ethereum do exist;
I thought I should make my own. 

Here's how Rimcoin works. 

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

Alice broadcasts to a random node, Node A, send 2 Rimcoin to Bob. And here is a digital signature, to prove I own these Rimcoin.

Next, Node A updates it's balance file, then contacts all other nodes with the same data. 

Now, the Rimcoin network agrees that this is the balance file:

Alice has 3 Rimcoin. 

Bob has 4.6 Rimcoin. 

# Notes

When a new node joins, they contact a random node, to get the current nodes, and adds itself. Then, it contacts all other nodes, informing them a new node has joined, and this is their data.  

# Distribution

Every 10 minutes, a random user is selected, and is rewarded 50 coins. 

After 840000 rewards, it is reduced to 25. 

Then 12.5, 6.25, 3.125, etc. 

There is a cap of 21000000 coins. 

# Signing

For a tx to be verified, it must be signed by the private key, associated with the public key, with a 512 bit digital signature. 

However, early builds, to focus on getting the actual code functional, have signing disabled. 


\* NOTE: CURRENTLY, IT USES A 160 BIT RANDOM ID. NOT SIGNING! 
