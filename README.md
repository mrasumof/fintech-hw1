# Unit 1 Homework Assignment: FinTech Case Study

<h2>FinTech Domain</h2>:

<b>* Blockchain and Cryptocurrencies</b>


Cosmos Network - https://cosmos.network/</b>


<h2>Project Cosmos Technology</h2> 

* Name of company
Cosmos Network

* When was the company incorporated? * Who are the founders of the company?
The company is formed by two main parties: the firts one is a non-for-profit ofrganization (NGO) based in Genevan, Switzerland called ICF (Inter-change found).  This NGO was created with the objective of execute the plans of creation of this Internet of Blockchains. This was going to be called as the COSMOS network later. 

Together with ICF, there was a software development company calles "All in Bits", which was also known as Tendermint Inc. This software development company was hired by the ICF in order to develop and deploy the firsts versions of this network.

In 2015, COSMOS co-founders, Ethan Buchman and Jae Kwon started developing Tendermint. This was the implementation of the tools and platforms required for this network of blackchains to inteconnect.  Tendermint, was the first application that used Byzantine Fault Tolerance (BFT) in a world of "Proof of Stake" (PoS) blockchains.
 
* How did the idea for the company (or project) come about?
Cosmos came to make sure that Blockchains can talk to each other, keeping the consistency (no double-spend problem) as well as the descentralization of storing and processing of transactions.

In order to understand this, we need first to understand a little bit of what is Blockchain technology. Broadly speaking, Blockchain was first created in 2018 (Bitcoin Blockchain) and is a set of technologies that allow to have a ledger-type data structure  (credits-debits) in a decentralized and consistent way. Blockchain data structure (the "ledger") is immutable, meaning that can not be changed. 

Each Blockchain, in turn, is replicated several times, creating identical copies, that "live" in different locations. This is what is called as the decentralization feature of this technology. Each individual Blockchain also uses decentralized workers (aka "miners") to validate and incorporate each transaction into the chain. A consensus safety mechanism is used for the miners to decide which transactions goes first and when the blockchain is ready processing that transaction and is ready for a new one. The consensus safety stays while at least two-thirds of miners agree that the transaction is valid.  

Transactions are linked with the previous one and with the next one using keys. These keys, tightly-linked with each other, the replication of identical copies of the Blockchain, and the consensus mechanism, makes it quasi-impossible to fake an entry in the ledger.

<b>Architecture Description</b>
In terms of architecture, we can see that Blockchain is split into 3 separate layers: application, netowrking and consensus.

[Figure 1](./images/fig1.jpg)

The application layer is the one that is in charge of actually processing the transactions. Networking, in turn, is the layer that distributes the transactions and all the required messaging among the nodes. Lastly, and very importantly, the consensus layer is the one that runs in each node and decides if the transaction is valid, and therefore add it to the Blockchain.

An important aspect to understand is that Blockchain technology has been originally developed for working independently, more in a siloed way, with its own resources and without talking to each other. There is no way to develop functionality on top of it, without having to fork the Blockchain, which basically is creating a copy and work on that copy. This is due to the fact that the first architecture of Blockchain technologies had the three layers built into the Blockchain and interconnected.

This technology soon was recognized to have tremendous potential but was too rigid. Ethereum, in 2014, was developed to mitigate some of its predecessor's weaknesses. Ethereum architecture split the Application layer from the networking and consensus, giving the public freedom to create new applications and functionality in that layer. This new layer was called Ethereum Virtual Machine (EVM), this virtual machine is capable of processing programs (Smart Contracts). This was a promising evolution as more and more people could use the Blockchain technology to create distributed applications.

Although this was a great progress, the Ethereum solution also have its flaws, which would slow down the adoption of this technology. Limitations included scalability (maximum number of transaction per second to be processed), usability (being an one-size-fits-all framework, it allowed for some flexibility and its design was more oriented to the average use-case) and governance-related, because it added the application layer governance needed in order to run decentralized.

Ethereum also was not designed nor built to interact with other Blockchains, making its use isolated to one solution per blockchain. This technologies got a lot of attention and big amounts of money were invested in research and development of decentralized applications. Number of Blockchains grew significantly but still, these Blockchains could not talk natively to each other.

Why Project Cosmos?
Cosmos was created to architect that needed communication and interoperability between Blockchains. This is achieved through the provision of Open Source tools, such as Tendermint, the Cosmos SDK and the Application Blockchain Interface, also known as ABCI. This set of tools are aimed to allow developers to create decenstralized applications that talk to each other in a simpler way.

Tendermint abstract the Network and Consensus layers into a generic engine that is fully maintained by the Open Source project. That way, developers can use more time developing the application use cases over spending time in the underlying Blockchain engine. In turn, Tendermint is connected to the application via ABCI, which allows developers to use a good number of programming languages to interact with Tendermint.

[Figure 2](./images/fig3.jpg)

This way, Project Cosmos aims to create an ecosystem of Blockchains that naturally communicates with each other. Tackling the next big technological challenge of Blockchain isolation. There are also solutions that allow non-Tendermints Blockchains to interact with Tendermint, so the idea is incorporating other technologies, not creating an isolated ecosystem of blockchains.

I consider this technology as very promising as it is going to be needed more due to the implementation of decentralized applications. Today we also see processing performance limitations that can be addressed with Tendermint.

Among current users of this technology we have Binance, OKEX, KIRA networks among another hundred of projects. This area will be addressed by other players in the future as this infrastructure is needed like a car needs a highway.

Sources: Cosmos Network (https://cosmos.network/intro)

<b>Author</b>: Martin Rasumoff
<b>Date</b>: 3/5/2021