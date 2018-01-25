# Cryptos / Blockchain

## Coins
* IOTA
	* [Whitepaper](Whitepapers/IOTA_Whitepaper.pdf)
	* Tangle network
	* Zero transation fees

* RaiBlocks
	* [Whitepaper](Whitepapers/raiblocks.pdf)
	* Every node has their own blockchain
	* Solve spam prevention by using PoW
		* The client (person sending money) needs to solve a easy crypto puzzle
		* This puzzle can be calculated pre-calculated before the transaction, this makes the transaction seem instant

* Bismuth
	* Read more

## Consensus Algorithm

* POW (Proof of Work)
	* Some computationally expensive algo that is trying to calculate the next block. There is only one possible next block. First person wins
	* Technically unfair, minors decide what transactions they pick. Based on TX fees

* POS (Proof of Stake)
	* You stake a certain amount of the currency, they you claim what the next block is, if you're wrong (lied) you loose you stake.

* HashGraph
	* Tech is patented
	* 'Trying to be a Voting Algorithm'
	*	250k TX/sec
	* Developed a Gossip Protocol
		* If you're a node, you randomly pick a node and tell them what you know
		* Eventually the information will spread through the network

