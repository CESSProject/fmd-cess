# fmd-cess

## Inspiration

With rapid advances of computing technologies such as AI and machine learning, the value of humanity's digital assets, the so-called "Digital Gold," is being discovered. Data, being one of the significant digital assets, will eventually be as important as the main production factors like land, labor, and capital in the progression of Web3.0. The inexorable rise of the digital economy has resulted in explosive growth in data generation. Nevertheless, data transparency issues inflicted by centralization have hindered the true potential of big data to boost production and efficiency, both economically and technologically. Solutions from conventional approaches are often complex and problematic. Hence it is imperative to call for a new data trading exchange using cutting-edge technologies to enhance data storage security, data sharing efficiency, and the protection of data owners' rights.

## Impact and Versatility

CESS Network provides friendly object storage and block storage by integrating existing resources using blockchain technology as a trust framework for data storage, enabling storage resources Tokenization which sets up the digital infrastructure. CESS Network seamlessly incorporates blockchain in cloud data storage, allowing data rights confirmation, storage distribution, and miners' activities verification and monitoring. The CESS Network can maximize the value of underutilized storage space and the data stored inside. To achieve both goals, first, the network collects unused disk space and distributes it to users who need to store data on the network; second, users have the freedom to set the data attributes (e.g., for sale or private, selling price), which facilitates efficient data trading. Data on the network can be shared and traded securely with clear information visible to clients.

Factor Trading Market for Data based on Cumulus Encrypted Storage System (FMD-CESS) is a decentralized application serving global users' needs in data purchasing and its storage on the CESS Network, supported by the Polkadot ecosystem. It provides data element sharing and trading services and ensures data safety holistically by implementing crucial technologies such as blockchain, distributed cloud storage, and data fingerprint extraction. FMD-CESS is an intelligent data platform serving users globally, integrating services in data storage, data encryption, data rights confirmation, data management, and data transactions.

## Creativity, Innovativeness, Originality

Decentralized blockchain data storage platforms such as Arweave, Filecoin, and Crust connect users who have storage needs to storage miners, allowing users to save data on the platforms. However, their storage services lack a comprehensive solution to fix all of the data safety issues. CESS Network has built a data storage platform and a one-step decentralized data trading exchange, delivering concrete solutions for problems caused by centralization, data breaches, and data rights ownership. CESS Network’s dedication to constructing a credible trading platform guarantees data storage security, privacy protection, and data storage confirmation, empowering users with confidence in data trading and uncovering the vast hidden potential of data!

## What it does

The overall system architecture is shown below. There are four components including the FMD-CESS data marketplace, the CESS blockchain, the CESS decentralized data storage, and the blockchain browser.

## We have completed the following tasks during the Hackathon

### 1. FMD-CESS data marketplace

**One-stop data exchange service**. It supports the entire data exchange lifecycle from data uploading, data ownership confirmation, data publishing to data finding, data purchase, and data downloading.

**Multiple data formats**. It supports all data formats including texts, images, audio, and video; and supports application fields including education, medical, and IT. In the future, more fields will be covered.

**Data finding service**. Users can browse all available public data on the platform, and search/filter data based on pre-defined criteria.

**Data recommendation**. The platform recommends trending data to users.

**Data value exploration**. The ultimate value of a data asset will be reached through free trading between data publishers and data consumers.

**Decentralization**. The free trading platform allows publishers and consumers to enter/exit the marketplace without restrictions. Data storage and exchange are powered by blockchain technology.

**Data right confirmation**. This function protects data ownership based on the algorithms we have been studying for years.

**Data security**. The client data are stored with multi-layered protection including reduplication and erasure coding. Data integrity is guaranteed at 99.9999%.

### 2. CESS blockchain

**On-chain meta-data storage**. Supports uploading of file meta-data to the blockchain, including the file owner, file name, file size, file characteristics, keywords, download fee, expiration date&time, etc.

**File path**. Provides file storage address.

**Registration with staking**. Provides a staking and registration function for storage miners. Only storage miners who successfully staking and registration are eligible to participate in storage mining.

**Data storage proofs submission and verification**. Storage miners need to provide data storage proofs to blockchain during the lifecycle of a stored data file. Both Proof-of-Replication and Proof-of-SpaceTime will be supported.

**Rewards and punishments for miners**. Rewards and punishments are based on storage proofs. Practical rewards and punishment rules need to be designed, in which rewards will be based on the ratio of the storage miners’ current storage power to the overall network storage power. If storage proofs are not submitted on time, corresponding punishment measures will be taken.

**BABE module integration**. Considering the security and robustness of the blockchain network, the BABE consensus module will be introduced.
Deployment of Wss and Docker. Provides a quick and convenient way to start.

### 3. Decentralized data storage network

Data synchronization mechanism for scheduling nodes.

Fault detection mechanism for scheduling nodes.

Node replacement mechanism for scheduling nodes.

Data recovery mechanism for scheduling nodes.

The communication mechanism between a scheduling node and its storage nodes.

Data reduplication and erasure coding. Generating multiple copies (flexible number of copies) and data recovery erasure codes for client data files.

Verification mechanism for data storage proofs. Stores data verification info on-chain, and supports scheduling nodes to fetch the verification info and to perform verification tasks towards data storage nodes.

Data right confirmation mechanism. Design similarity hash algorithms to calculate data similarities for multiple data formats including texts, images, and more.

### 4. Blockchain browser

Blockchain data stats

Account details

Extrinsic details

Node list

Node details

Searching

### 5. Wallet

Wallet creation

Wallet connection

Wallet recovery

### 6. Faucet

Get testing tokens

## How I built it

The project is done by a development team of 4 members:
Teh Sunn Liu, from India, Front end developer
Yeou Sunn Liu, from India, Blockchain developer
Jack Liu, from India, Blockchain developer
Ted Zhang, from Hong Kong, Go developer (decentralized storage)

## Challenges I ran into

We ran into many challenges, including but not limited to, the accuracy issue of data right confirmation algorithm, implementing interoperability between programs coded in different languages (e.g., JS, Go, and Java) and blockchain RPC functions, embedding of complicated modules, and optimization of blockchain speed and stability. We tackled these issues in various ways such as, testing with a large number of data samples, studying and debugging with the SDK interface of each programming language, fixing error reporting via divide-and-conquer, optimizing storage categories, and reducing frequent use of the “hook” function.

## Accomplishments that I'm proud of

We completed the project based on our past design and development experience of Substrate, Ethereum, Filecoin, and other blockchain projects. We hope that, in the future, the fully constructed and well-tested CESS network will become a valuable parachain of the Polkadot ecosystem. All the components that we have created can be put to use for decentralized systems. Our work meets the expectations of the Hackathon for the following reasons:

Contributions to decentralization and Web 3.0 (25%). From the supply side, the method of storage mining encourages excess or unused resources to join the decentralized network via a token incentive economy. The storage providers accept the data storage requests from clients. From the demand side, clients upload data files to a decentralized cloud data network, and the data files are distributed globally to different nodes. Clients pay for the data access service provided by miners.

Innovation and creativity (25%). CESS incentivizes unused or under-utilized storage resources to join the blockchain network, to create a secure and scalable global decentralized data ecosystem, which is secured by multiple storage proof schemes and multi-format data right confirmation mechanism. The multiple proof schemes are Proof of Data Reduplication and Recovery (PoDR²), Proof of Replications (PoRep), Proof of Space and Time (PoST), Proof of data Flow (PoF), and Proof of Available storage (PoAs). The multi-format data right confirmation (MDRC) mechanism consists of algorithms that process data files and confirm ownerships for texts, images, audio, video, and other data types.

Technical difficulties (25%). The project covers a wide range of substrate components such as Treasury, Polkadot-JS API, and GSRPC. These components change consistently and rapidly. It is very challenging to implement multiple storage proof schemes and multi-format data right confirmation mechanism under the Substrate framework.

User experience (25%). Early customers are storage miners and enterprises. We already demonstrated our testnet system to some clients and received very positive feedback.

## What I learned

Our team has learned a lot from the Hackathon project. First, we overcome the challenges in a fast-paced development environment with many dependencies. We quickly adapted to the new design and development model in the blockchain and decentralized world. We studied and gained skills in Rust, Cargo, etc. Also, we built a stronger team through teamwork and experience of communicating with organizations overseas.

## What is next for the CESS network

So far, our work and experience are limited to the CESS testnet. To be able to launch the mainnet, there are much more ahead. The plan is to continue developing the CESS blockchain, the CESS decentralized cloud data storage, the blockchain browser, and the data trading platform. The future functions include CESS random rotational selection consensus mechanism, proxy re-encryption, zero-knowledge storage proof, and storage miner and consensus miner staking. Regarding the data trading platform, future functions include data trading using API, design of data standard and trading standard, data trading risk control, etc.

## Mass Usability

The CESS network is built with the Substrate frame and is expected to become a Kusama or Polkadot parachain. CESS is committed to providing scalable decentralized data storage for the Polkadot ecosystem. Members of the ecosystem should be able to use CESS storage via API effortlessly (or with minor code changes), to obtain secure and trustworthy cloud data services.
