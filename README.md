![Image](https://raw.githubusercontent.com/CESSProject/W3F-illustration/main/hackathon/banner4.jpg)

# Factor Trading Market for Data Based on CESS Cloud Data Network (FMD-CESS)

## 🌠 Inspiration

With rapid advances of computing technologies such as AI and machine learning, the value of humanity's digital assets, the so-called "Digital Gold", is being discovered. Data, being one of the significant digital assets, will eventually be as important as the main production factors like land, labor, and capital in the progression of Web3.0. The inexorable rise of the digital economy has resulted in explosive growth in data generation.

Nevertheless, data transparency issues inflicted by centralization have hindered the true potential of big data to boost production and efficiency, both economically and technologically. 

There are some problems in the existing data market:

**Data Security**：prone to data breach, data loss.

**Privacy**：data disclosure to third parties,  data altercation.

**Data ownership**: no protection.

Approaches to enhance data storage security, data sharing efficiency, and the protection of data owners' rights are often complex and problematic.

Factor Trading Market for Data Based on CESS Cloud Data Network (FMD-CESS) realizes point-to-point trusted transactions of decentralized data, data rights confirmation, and privacy protection based on blockchain technology.

## 🎑 Impact and Versatility

FMD-CESS  is a decentralized application serving global users' needs in data purchasing and its storage on the CESS Cloud Data Network, supported by the Polkadot ecosystem. It provides data sharing and trading services and ensures data safety holistically by implementing crucial technologies such as blockchain, distributed cloud storage, and data fingerprint extraction.

FMD-CESS is an intelligent data platform serving users globally, integrating services in data storage, data encryption, data rights confirmation, data management, and data transactions.

FMD-CESS will become a decentralized data trading market in the Web 3.0 and is committed to promoting the value interconnection of human data assets!

## 💡 Creativity, Innovativeness, Originality

**Completely decentralized**

- Decentralized network--CESS Cloud Data Network.

- Decentralized storage --Cumulus Encrypted Storage System.

- Decentralized data transactions --FMD-CESS (Node-to-node trading).

**Data security**

- The Proof of Data Reduplication and Recovery (PoDR²).

- Data is never lost.

- Data multi copy replication.

- Data encryption.

- Data availability.

- Data integrity.

- Data privacy.

**Data ownership**

- The Multi-format Data Rights Confirmation Mechanism (MDRC).

- CESS extracts data fingerprints from each data file to generate a data certificate ID.

- By comparing similarities between data fingerprints, the system identifies lineages of data files and provides strong evidence for ownership protection.

## ✏️ What it does

The overall system architecture is shown in the figure. There are four components including the FMD-CESS,  The CESS Cloud Data Network , Cumulus Encrypted Storage System and the blockchain explorer.

<div align=center><img width="80%" height="80%" src="https://raw.githubusercontent.com/CESSProject/W3F-illustration/main/hackathon/banner3.png"/></div>

- **The FMD-CESS ([*web-app*](https://github.com/CESSProject/web-app))**: An web platform for users to upload, search, purchase, download data and such operations. In addition, a *data rights confirmation mechanism* is also implemented. ([*Jump into it!*](http://data.cesslab.co.uk/data/))
- **The CESS Cloud Data Network ([*cess-node*](https://github.com/CESSProject/cess-node))**: is developed based on the [*Substrate*](https://github.com/paritytech/substrate). The CESS Cloud Data Network will store the meta-information of all data uploaded by users. In order to support the features of FMD-CESS, it includes sminer, segment book, and file bank pallets.
- **Cumulus Encrypted Storage System**: consists of [*storage-mining-tool*](https://github.com/CESSProject/storage-mining-tool) and scheduler-mining-tool. The data will be distributed to different storage miners through scheduler node as users upload data. Similarly, the data will also be obtained from storage miners through scheduler node as users download data.
- **Blockchain explorer ([*cess-ui-js*](https://github.com/CESSProject/cess-ui-js))**: is tailored for the CESS Cloud Data Network, modified from [*polkadot-js-app*](https://github.com/polkadot-js/apps). You can obtain info on the blockchain from multiple dimensions. ([*Jump into it!*](http://data.cesslab.co.uk/browser))

## 🍁 We have completed the following tasks during the Hackathon

### 1. FMD-CESS data marketplace has been developed, which features

- **One-stop data exchange service**. It supports the entire data exchange lifecycle from data uploading, data publishing to data finding, data purchase, and data downloading.

- **Supports multiple data formats**. It supports all data formats including texts, images, audio and video; data categories in various industries including education, medical, and IT. More industry fields will be covered in the future.

- **Public data searching function**. Users can browse and search all available public data on the platform, and filter data based on pre-defined criteria.

- **Data recommendation**. The platform recommends trending data to users.

- **Data value exploration**. The ultimate value of a data asset will be reached through free trading between data providers and users.

- **Decentralization**. The free trading platform allows providers and consumers to enter/exit the marketplace without restrictions. Data storage and exchange are powered by blockchain technology.

- **Data rights confirmation**. Our refined technology protects data ownership based on the well tested algorithms.

- **Data security**. Client data are stored with protection from the Proof of Data Reduplication and Recovery (PoDR²) technology, protection including  reduplication and erasure coding. 99.9999% data integrity is guaranteed.

### 2. CESS Cloud Data Network

CESS constructed a stable and reliable underlying infrastructure. CESS Cloud Data Network has unlimited scalability, supporting the stability of FMD-CESS and allowing users securely visiting the storage resources. In addition, every node can become a massive decentralized cloud storage system individually.

CESS Cloud Data Network has been developed, which features

- **On-chain meta-data storage**. Supports uploading of file meta-data to the blockchain, including the file owner, file name, file size, file characteristics, keywords, download fee, expiration date&time, etc.

- **Registration with staking**. Provides a staking and registration function for storage miners. Only storage miners who successfully staking and registration are eligible to participate in storage mining.

- **Data storage proofs submission and verification**. Storage miners need to provide data storage proofs to blockchain during the lifecycle of a stored data file. Both Proof-of-Replication and Proof-of-SpaceTime will be supported.

- **Rewards and punishments for miners**. Rewards and punishments are based on storage proofs. Practical rewards and punishment rules need to be designed, in which rewards will be based on the ratio of the storage miners’ current storage power to the overall network storage power. If storage proofs are not submitted on time, corresponding punishment measures will be taken.

- **Deployment of wss and Docker**. Provides a quick and convenient way to start.

### 3. Cumulus Encrypted Storage System

Cumulus Encrypted Storage System is a decentralized cloud data network that provides data services protecting users' privacy and data ownership rights at a low cost. CESS is dedicated to building a trustworthy, secure, transparent, and scalable data-sharing ecosystem,including:

- Data synchronization mechanism for scheduling nodes.

- Fault detection mechanism for scheduling nodes.

- Node replacement mechanism for scheduling nodes.

- Data recovery mechanism for scheduling nodes.

- The communication mechanism between a scheduling node and its storage miners.

- Data reduplication and erasure coding. Generating multiple copies (flexible number of copies) and data recovery erasure codes for client data files.

- Verification mechanism for data storage proofs. Stores proof data info on-chain, and supports scheduling nodes to fetch the proofs from sotrage miner and to perform verification tasks towards storage miners.

- Data rights confirmation mechanism. Design similarity hash algorithms to calculate data similarities for multiple data formats including texts, images, and more.

At the same time, blockchain explorer, wallet and faucet are developed to facilitate users to use and experience FMD-CESS data trading market. You can view data trading details through web pages.

### 4. Blockchain Explorer

- **Account details**. In addition to displaying basic content such as balance and account address, it also supports displaying the stored data info of the account.

- **Extrinsic details**. Ability to display detailed info about individual extrinsic.

- **Miner node list**. Display the general info of all storage miners in the form of a table.

- **Miner node details**. Show the info of storage miners, including beneficiary address, storage space offered, and storage rewards and other info.

- **Searching**. Support search by block hash, extrinsic hash, address and miner ID.

### 5. Faucet

- **Get testing tokens**. Support users to minter tokens.

## 🐥 Team

The project is developed by the engineering team of 4 members:

- **Teh Sunn Liu**, front end developer, India
- **Yeou Sunn Liu**, blockchain developer, India
- **Jack Liu**, blockchain developer, India
- **Ted Zhang**,Go developer (decentralized storage), China

## 🎢 Challenges we ran into

We ran into many challenges, including but not limited to, the accuracy issue of data rights confirmation algorithm, implementing interoperability between programs coded in different languages (e.g., JS, Go, and Java) and blockchain RPC methods, embedding of complicated modules, and optimization of blockchain speed and stability. We tackled these issues in various ways such as, testing with a large number of data samples, studying and debugging with the SDK interface of each programming language, fixing error reporting via divide-and-conquer, optimizing storage categories, and reducing frequent use of the hooks attribute.

## 🏆 Accomplishments that I'm proud of

We completed the project based on our past design and development experience of Substrate, Ethereum, Filecoin, and other blockchain projects. We hope that, in the future, the fully constructed and well-tested CESS network will become a valuable parachain of the Polkadot ecosystem. All the components that we have created can be put to use for decentralized systems. Our work meets the expectations of the Hackathon for the following reasons:

**Contributions to decentralization and Web 3.0 (25%)**. From the supply side, the method of storage mining encourages excess or unused resources to join the decentralized network via a token incentive economy. The storage providers accept the data storage requests from clients. From the demand side, clients upload data files to a decentralized cloud data network, and the data files are distributed globally to different nodes. Clients pay for the data access service provided by miners.

**Innovation and creativity (25%)**. CESS incentivizes unused or under-utilized storage resources to join the blockchain network, to create a secure and scalable global decentralized data ecosystem, which is secured by multiple storage proof schemes and multi-format data rights confirmation mechanism. The multiple proof schemes are Proof of Data Reduplication and Recovery (PoDR²), Proof of Replications (PoRep), Proof of Spacetime (PoSt). The multi-format data rights confirmation (MDRC) mechanism consists of algorithms that process data files and currently confirm ownerships for texts, images.

**Technical difficulties (25%)**. The project covers a wide range of substrate built-in components such as BABE, Staking, Scheduler, Polkadot-JS API, and GSRPC. These components change consistently and rapidly. It is very challenging to implement multiple storage proof schemes as pallets under the Substrate framework.  In addition, It is not easy to choose a similarity algorithm to achieve a high-accuracy data rights confirmation. Designing workflow for proof of storage to integrate into the blockchain system is also a major difficulty.

**User experience (25%)**. Early customers are storage miners and enterprises. We already demonstrated our testnet system to some clients and received very positive feedback.

## 🎣 What I learned

Our team has learned a lot from the Hackathon project. First, we overcome the challenges in a fast-paced development environment with many dependencies. We quickly adapted to the new design and development model in the blockchain and decentralized world. We studied and gained skills in Rust, Cargo, etc. Also, we built a stronger team through teamwork and experience of communicating with organizations overseas.

## 📐 What is next for the FMD-CESS?

The upcoming functions for the data trading platform include: data trading on API, the design of data standard and trading standard, and data tracking risk control, etc.

## 📯 Mass Usability

FMD-CESS provides comprehensive solutions for data trading in the Polkadot ecosystem built on Substrate.

It is a one-stop decentralized data trading platform that provides data services for both private and commercial use. 

It is capable of processing big data in healthcare, real estate, financial, industrial sectors, etc.

## 🚁 Related Links

Data Trading Market: http://data.cesslab.co.uk/data/

Blockchain Explorer: http://data.cesslab.co.uk/browser or https://polkadot.js.org/apps/ with *wss://cesslab.co.uk/rpc2-hacknet/ws/*

Faucet: http://data.cesslab.co.uk/faucet/

