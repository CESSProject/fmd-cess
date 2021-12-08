![Image](https://raw.githubusercontent.com/CESSProject/W3F-illustration/main/hackathon/banner.png)
# Factor Trading Market for Data Based on CESS Cloud Data Network (FMD-CESS)

## Inspiration

With rapid advances of computing technologies such as AI and machine learning, the value of humanity's digital assets, the so-called "Digital Gold", is being discovered. Data, being one of the significant digital assets, will eventually be as important as the main production factors like land, labor, and capital in the progression of Web3.0. The inexorable rise of the digital economy has resulted in explosive growth in data generation.

Nevertheless, data transparency issues inflicted by centralization have hindered the true potential of big data to boost production and efficiency, both economically and technologically. There are some problems in the existing data market:

**Data Security**：prone to data breach, data loss.

**Privacy**：data disclosure to third parties,  data altercation.

**Data ownership**: no protection.

Hence it is imperative to call for a new data trading exchange using cutting-edge technologies to enhance data storage security, data sharing efficiency, and the protection of data owners' rights.

Factor Trading Market for Data Based on CESS Cloud Data Network (FMD-CESS) is a one-stop decentralized data transaction platform based on CESS, dedicated to promoting the value interconnection of data!

## Impact and Versatility

FMD-CESS  is a decentralized application serving global users' needs in data purchasing and its storage on the CESS Cloud Data Network, supported by the Polkadot ecosystem. It provides data sharing and trading services and ensures data safety holistically by implementing crucial technologies such as blockchain, distributed cloud storage, and data fingerprint extraction.

FMD-CESS is an intelligent data platform serving users globally, integrating services in data storage, data encryption, data rights confirmation, data management, and data transactions.

## Creativity, Innovativeness, Originality

**Completely decentralized**

Decentralized network--CESS Cloud Data Network.

Decentralized storage --Cumulus Encrypted Storage System.

Decentralized data transactions --FMD-CESS (Node-to-node trading).

**Data security**

the Proof of Data Reduplication and Recovery (PoDR²).

Data is never lost.

Data multi copy replication.

data encryption.

Data availability.

Data integrity.

Data privacy.

**Data ownership**

the Multi-format Data Rights Confirmation Mechanism (MDRC).

CESS extracts data fingerprints from each data file to generate a data certificate ID.

By comparing similarities between data fingerprints, the system identifies lineages of data files and provides strong evidence for ownership protection.

## What it does

The overall system architecture is shown in the figure. There are four components including the FMD-CESS,  The CESS Cloud Data Network , Cumulus Encrypted Storage System and the blockchain explorer.

<div align=center><img width="80%" height="80%" src="https://raw.githubusercontent.com/CESSProject/W3F-illustration/main/hackathon/banner3.png"/></div>

- **The FMD-CESS (web-app)**: An web platform for users to upload, search, purchase, download data and such operations. In addition, a *data confirmation mechanism* is also implemented. (*Jump into it!*)
- **The CESS Cloud Data Network (cess-node)**: It's developed based on the *Substrate*. The CESS Cloud Data Network will store the meta-information of all data uploaded by users. In order to support the features of FMD-CESS, it includes sminer, segment book, and file bank pallets.
- **Cumulus Encrypted Storage System**: The system consists of storage-mining-tool and scheduler-mining-tool. The data will be distributed to different storage miners through scheduler node as users upload data. Similarly, the data will also be obtained from storage miners through scheduler node as users download data.
- **Blockchain explorer (cess-ui-js)**: It was tailored for the CESS Cloud Data Network, modified from *polkadot-js-app*. You can obtain info on the blockchain from multiple dimensions. (*Jump into it!*)

## We have completed the following tasks during the Hackathon

### 1. FMD-CESS data marketplace is built, which can realize:

- **One-stop data exchange service**. It supports the entire data exchange lifecycle from data uploading, data ownership confirmation, data publishing to data finding, data purchase, and data downloading.

- **Multiple data formats**. It supports all data formats including texts, images, audio, and video; and supports application fields including education, medical, and IT. In the future, more fields will be covered.

- **Data finding service**. Users can browse all available public data on the platform, and search/filter data based on pre-defined criteria.

- **Data recommendation**. The platform recommends trending data to users.

- **Data value exploration**. The ultimate value of a data asset will be reached through free trading between data publishers and data consumers.

- **Decentralization**. The free trading platform allows publishers and consumers to enter/exit the marketplace without restrictions. Data storage and exchange are powered by blockchain technology.

- **Data right confirmation**. This function protects data ownership based on the algorithms we have been studying for years.

- **Data security**. The client data are stored with multi-layered protection including reduplication and erasure coding. Data integrity is guaranteed at 99.9999%.

### 2. CESS Cloud Data Network

CESS builds a stable and reliable underlying infrastructure, CESS Cloud Data Network has unlimited "scalability" attributes. Various nodes can form a huge decentralized cloud storage system to support FMD-CESS to access storage resources stably and safely.

CESS Cloud Data Network is built, which can realize:

- **On-chain meta-data storage**. Supports uploading of file meta-data to the blockchain, including the file owner, file name, file size, file characteristics, keywords, download fee, expiration date&time, etc.

- **Registration with staking**. Provides a staking and registration function for storage miners. Only storage miners who successfully staking and registration are eligible to participate in storage mining.

- **Data storage proofs submission and verification**. Storage miners need to provide data storage proofs to blockchain during the lifecycle of a stored data file. Both Proof-of-Replication and Proof-of-SpaceTime will be supported.

- **Rewards and punishments for miners**. Rewards and punishments are based on storage proofs. Practical rewards and punishment rules need to be designed, in which rewards will be based on the ratio of the storage miners’ current storage power to the overall network storage power. If storage proofs are not submitted on time, corresponding punishment measures will be taken.

- **BABE module integration**. Considering the security and robustness of the blockchain network, the BABE consensus module will be introduced.
- **Deployment of Wss and Docker**. Provides a quick and convenient way to start.

### 3. Cumulus Encrypted Storage System

In order to realize the security, efficiency and privacy protection of data storage and transactions, we built Cumulus Encrypted Storage System, which is a high-speed, secure and scalable decentralized cloud storage data network, including:

- Data synchronization mechanism for scheduling nodes.

- Fault detection mechanism for scheduling nodes.

- Node replacement mechanism for scheduling nodes.

- Data recovery mechanism for scheduling nodes.

- The communication mechanism between a scheduling node and its storage miners.

- Data reduplication and erasure coding. Generating multiple copies (flexible number of copies) and data recovery erasure codes for client data files.

- Verification mechanism for data storage proofs. Stores proof data info on-chain, and supports scheduling nodes to fetch the proofs from sotrage miner and to perform verification tasks towards storage miners.

- Data right confirmation mechanism. Design similarity hash algorithms to calculate data similarities for multiple data formats including texts, images, and more.

At the same time, blockchain explorer, wallet and faucet are developed to facilitate users to use and experience FMD-CESS data trading market. You can view data trading details through web pages.

### 4. Blockchain explorer

- **Account details**. In addition to displaying basic content such as balance and account address, it also supports displaying the stored data info of the account.

- **Extrinsic details**. Ability to display detailed info about individual Extrinsic.

- **Miner node list**. Display the general info of all storage miners in the form of a table.

- **Miner node details**. Show the info of storage miners, including beneficiary address, storage space offered, and storage rewards and other info.

- **Searching**. Support search by block hash, extrinsic hash, address and miner ID.

### 5. Faucet

- **Get testing tokens**. Support users to minter tokens.

## Team

The project is done by a development team of 4 members:
- **Teh Sunn Liu**, from India, Front end developer
- **Yeou Sunn Liu**, from India, Blockchain developer
- **Jack Liu**, from India, Blockchain developer
- **Ted Zhang**, from China, Go developer (decentralized storage)

## Challenges we ran into

We ran into many challenges, including but not limited to, the accuracy issue of data right confirmation algorithm, implementing interoperability between programs coded in different languages (e.g., JS, Go, and Java) and blockchain RPC functions, embedding of complicated modules, and optimization of blockchain speed and stability. We tackled these issues in various ways such as, testing with a large number of data samples, studying and debugging with the SDK interface of each programming language, fixing error reporting via divide-and-conquer, optimizing storage categories, and reducing frequent use of the “hook” function.

## Accomplishments that I'm proud of

We completed the project based on our past design and development experience of Substrate, Ethereum, Filecoin, and other blockchain projects. We hope that, in the future, the fully constructed and well-tested CESS network will become a valuable parachain of the Polkadot ecosystem. All the components that we have created can be put to use for decentralized systems. Our work meets the expectations of the Hackathon for the following reasons:

Contributions to decentralization and Web 3.0 (25%). From the supply side, the method of storage mining encourages excess or unused resources to join the decentralized network via a token incentive economy. The storage providers accept the data storage requests from clients. From the demand side, clients upload data files to a decentralized cloud data network, and the data files are distributed globally to different nodes. Clients pay for the data access service provided by miners.

Innovation and creativity (25%). CESS incentivizes unused or under-utilized storage resources to join the blockchain network, to create a secure and scalable global decentralized data ecosystem, which is secured by multiple storage proof schemes and multi-format data right confirmation mechanism. The multiple proof schemes are Proof of Data Reduplication and Recovery (PoDR²), Proof of Replications (PoRep), Proof of Space and Time (PoST), Proof of data Flow (PoF), and Proof of Available storage (PoAs). The multi-format data right confirmation (MDRC) mechanism consists of algorithms that process data files and confirm ownerships for texts, images, audio, video, and other data types.

Technical difficulties (25%). The project covers a wide range of substrate components such as Treasury, Polkadot-JS API, and GSRPC. These components change consistently and rapidly. It is very challenging to implement multiple storage proof schemes and multi-format data right confirmation mechanism under the Substrate framework.

User experience (25%). Early customers are storage miners and enterprises. We already demonstrated our testnet system to some clients and received very positive feedback.

## What I learned

Our team has learned a lot from the Hackathon project. First, we overcome the challenges in a fast-paced development environment with many dependencies. We quickly adapted to the new design and development model in the blockchain and decentralized world. We studied and gained skills in Rust, Cargo, etc. Also, we built a stronger team through teamwork and experience of communicating with organizations overseas.

## What is next for the FDM-CESS?

Regarding the data trading platform, future functions include: data trading using API, design of data standard and trading standard, data trading risk control, etc.

## Mass Usability

FMD-CESS will provide all-round solutions for data transactions based on Polkadot ecology developed by Substrate, and can also provide services for data transactions requiring commercial use, such as medical big data, real estate transactions, financial transaction market, industrial data, etc.
