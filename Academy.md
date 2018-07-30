# Index

- [Introduction](#introduction)
- [1.0 Background](#10-background)
  * [1.1 A group of hacktivists tried to improve their country](#11-a-group-of-hacktivists-tried-to-improve-their-country)
  * [1.2 Silicon Valley](#12-silicon-valley)
  * [1.3 Sovereign](#13-sovereign)
- [2.0 Blockchain Basics](#20-blockchain-basics)
  * [2.1 Origins of Bitcoin and blockchain technology.](#21-origins-of-bitcoin-and-blockchain-technology)
  * [2.2 Peer-to-peer networks](#22-peer-to-peer-networks)
  * [2.3 How can a truly peer-to-peer Internet of Value be enabled?  What is the double-spend dilemma?](#23-how-can-a-truly-peer-to-peer-internet-of-value-be-enabled---what-is-the-double-spend-dilemma-)
    + [2.3.1 The Double-Spend Dilemma:](#231-the-double-spend-dilemma-)
  * [2.4 What is a hash function and why are hashes important in peer-to-peer networks?](#24-what-is-a-hash-function-and-why-are-hashes-important-in-peer-to-peer-networks-)
    + [2.4.1 Hash & Hash Function](#241-hash---hash-function)
  * [2.5 What is public key cryptography? How do digital signatures enable peer-to-peer value transfer?](#25-what-is-public-key-cryptography--how-do-digital-signatures-enable-peer-to-peer-value-transfer-)
    + [2.5.1 Trusted Third Party](#251-trusted-third-party)
    + [2.5.2 Digital Signatures](#252-digital-signatures)
  * [2.6 How do all of these pieces of technology combine to create a peer-to-peer network that solves the double-spend dilemma?](#26-how-do-all-of-these-pieces-of-technology-combine-to-create-a-peer-to-peer-network-that-solves-the-double-spend-dilemma-)
    + [2.6.1 Nodes](#261-nodes)
    + [2.6.2 Protocol](#262-protocol)
    + [2.6.3 Proof of Work and Miners](#263-proof-of-work-and-miners)
    + [2.6.4 How does mining work?](#264-how-does-mining-work-)
   - [3.0 Global Decision-Making & Universal Basic Income](#Global)
    
- [References](#references)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Introduction

The Democracy Earth Foundation is working to update government for the 21st century by building a blockchain-based liquid-democracy platform. In that pursuit, the foundation has spent the past 6 years researching, experimenting, learning and building at the intersection of technology and politics. In our white paper, [The Social Smart Contract](https://github.com/DemocracyEarth/paper/blob/master/README.mediawiki), we explore in detail how a blockchain-based liquid democracy can help the world solve some of the most pressing challenges facing democracy, such as rising authoritarianism and a lack of voter participation.

While Democracy Earth is focused on building civic tech designed to be easy to use on an everyday basis, we also view it as important to provide education regarding the ideas and technology that have made this possible. Due to the fact that The Social Smart Contract contains some technical vocabulary and information that require background expertise not possessed by the typical reader, we are launching this companion curriculum, the Democracy Academy. Our goal is to give readers the foundational knowledge needed to understand the content of The Social Smart Contract, provide a sound understanding of blockchains, liquid democracy and other technical information it contains, and with it help foster a global movement that enables everyone to claim civic participation as their right.


The content of Democracy Academy was developed collaboratively by students for students, but will be helpful to anyone curious about these topics. Our goal is for everyone following this curriculum to emerge with a strong grasp of essential blockchain technology concepts, as well as the history and context around the founding and development of the Democracy Earth governance platform. It is our hope that in doing so we can help a new generation of leaders effectively learn as much as possible about the intersection of technology and politics - and Democracy Earth’s crowd-sourced proposal - so they are fully equipped to advocate for it, contribute to it, and promote it around the world.

Neither the white paper nor the Democracy Academy curriculum are intended to remain static and we welcome contributions from readers to continue improving them. Like Democracy itself, Democracy Academy must always be a work in progress. 

*This content will be updated regularly, with a new unit being added every week. The full content will be posted by September 1st.


<a name="Background"></a>
# 1.0 Background

In Week One, we discuss the emergence of civic tech/democracy tech and the history of the Democracy Earth Foundation. We will provide an overview of the vision and journey of Democracy Earth founders, and how their experiences and lessons shape our software development and movement.

##  1.1 A group of hacktivists tried to improve their country

[<img width="597" alt="screen shot 2018-07-22 at 10 50 07" src="https://user-images.githubusercontent.com/18194034/43046851-085ef7d2-8d9d-11e8-987e-47ffd9941e1c.png">](https://www.ted.com/talks/pia_mancini_how_to_upgrade_democracy_for_the_internet_era)

Before co-founders Pia Mancini and Santiago Siri launched Democracy Earth and the Sovereign platform, they created a software called Democracy OS, one of the earliest civic tech projects of its kind. As Pia stated in a 2016 interview with The Guardian [1], Democracy OS could not have emerged in a stable country like the US or UK, but only in a country where politics were bad enough that people were willing to take risks. In many ways, their native Argentina - with some of the highest internet access in Latin America, yet some of the most corrupt and unresponsive politics - offered the perfect birthplace for this historic civic tech. 

Pia's political education included years spent developing training programs to teach democratic values, preparing civil leaders for public office - efforts that were succcessful in getting candidates elected as mayors and governonrs. Yet systemic corruption made it clear that working in traditional politics would not be effective in fixing pervasive social issues. Eventually Pia and Santi concluded that it was not enough to try to place better people in the same system, but that the very system itself was an issue. It distanced the voters from decision-making, creating a breakdown in communication between political leaders and ordinary citizens. That inspired them to create Democracy OS, where citizens could learn about current congressional policy proposals, as well as make their own proposals, debate and vote on them. The software translated all proposals into plain language, and was accessible to anyone with a smartphone. Though Pia, Santi and their collaborators offered the Democracy OS platform to political parties, they had no takers; instead, they were "sent away like little kids", as she noted in her [2014 TED Talk](https://www.ted.com/talks/pia_mancini_how_to_upgrade_democracy_for_the_internet_era). 

They were not the first civic technologists to learn the lesson that software alone could not solve the deep divide between politicians and citizens – although better technology was needed, the main barrier was still a cultural one. Undaunted by this rejection, Pia and Santi decided to take a different path, and form their own political party called  “Partido de la Red,” or the “Net Party” in English. The party promised to vote in line with how citizens voted on the DemocracyOS application. In 2013, they campaigned with a large Trojan Horse made of wood, driving it around the neighbourhoods of Buenos Aires. The Trojan Horse signified that while the Net Party was participating in the familiar process of campaigning like a typical political party, it was only a front - they had no intention to behave like one. Unlike the other parties, they intended to actually let citizens guide their decisions directly through their app. While Partido de la Red candidates did not win an elected seat in the parliament, they received 22,000 votes. It was enough for the Congress to take notice and to launch an instance of DemocracyOS to discuss three issues, two on public transport and one on the use of public space.

Partido de la Red and DemocracyOS taught Pia and Santi three important lessons that still ring true today:

1. Civic tech has the potential to revolutionize government. Though it failed to gain a Parliamentary seat, Partido de la Red forced the government to take notice of, and even use, Democracy OS civic tech. Clearly, the idea of online participation had power - it resonated with people. But even with this success, the government did not promise to vote in alignment with the decisions made by citizens on the Democracy OS platform, which led to the second lesson:

2.  While civic tech has a true potential to change government, this change is far from inevitable -  and a simple app that serves as an interface with Congress is not enough in and of itself to make change happen.

3. The third and most painful lesson was about corruption. [Spies infiltrated party meetings](https://medium.com/@santisiri/baptism-of-fire-100392b05726) to generate confusion; they were attacked online, and were even asked to bribe a judge in order to be able to run for the 2015 elections. This first-hand contact with corruption taught them how difficult it is to change the system from within. As Santi has remarked, “it is much more likely that the system will change you first.”  

## 1.2 Silicon Valley

[<img width="598" alt="screen shot 2018-07-22 at 11 32 27" src="https://user-images.githubusercontent.com/18194034/43047283-f9d4cbfa-8da2-11e8-945d-c8ea051dd44a.png">](https://www.youtube.com/watch?v=UajbQTHnTfM) 

In 2015 the Silicon Valley accelerator YCombinator - backer of Reddit and AirBnb, among others - invited Pia and Santi to join the Y15 class of nonprofit startups, selected for their potential for global impact. It was here they met Herb Stephens, a former GE auditor and serial software entrepreneur with a 25-year history of building disintermediating systems that shifted power to the user through technology. Since learning of blockchain technology in 2012 and considering it “the best invention since the Internet itself”, Herb dedicated the rest of his career to social entrepreneurism, readily joining the foundation in the role of president and treasurer.

Together Herb, Santi, Pia and Virgile Devile - the Paris-based co-founder of Open Source Politics and one-time team lead for Democracy OS Europe- formed the Democracy Earth Foundation, a U.S. (CA) 501©(3) non-profit.

With these early civic tech experiences, the team was prepared to go well beyond the constraints of the political status quo. They adopted a theory of change best summarized by architect Buckminster Fullers’ famous quote: **“You don’t change the existing reality by fighting against it. To change something, build a new model that makes the existing model obsolete.”** In other words, building an app to interface with existing political systems won’t create change; what is needed is a tool that brings about such an obvious and enormous improvement to governance it renders the current system outdated.

Their new approach was to use blockchains - the same technology underlying Bitcoin - to create a censorship resistant peer-to-peer democracy (terms that will be explained in greater detail later in the curriculum). This new focus would bring massive improvements to three fundamental pillars of governance: 

**Voting**: The current system for voting is both insecure and difficult to audit because it is highly centralized. It can be hacked and manipulated in many ways, and the only people able to verify voting rolls are a very small group of election officials. With a blockchain-based system, manipulating results is functionally impossible as all votes are recorded in an immutable public ledger that anyone can audit.

**Identity**: Today we receive identity from centralized authorities such as governments providing passports and ID cards, and from websites providing passwords, logins and profiles. The Democracy Earth platform will employ a decentralized ID system, allowing citizens to have a secure form of identification beyond the influence of any third party. Democracy Earth will help citizens own their data and identity through the use of new cryptographic technologies, which will be explained in-depth later in the curriculum.

**Representation**: Our system does not provide the right incentives for our representatives to represent us very well. If we disagree with how they voted, we have to wait until the next election cycle to try to remove them which could be many years. We are forced to choose a single representative to represent us on all issues, rather than be able to choose multiple experts from different fields to represent us on different issues. This is why Democracy Earth is building a liquid democracy platform that allows for users to propose, debate, and vote directly on issues, or to *delegate* their vote to someone they trust to vote for them. Representation will be more responsive when you can delegate your vote to anyone and immediately revoke it if they vote incorrectly or behave unethically.

## 1.3 Sovereign

[<img width="584" alt="screen shot 2018-07-22 at 11 36 00" src="https://user-images.githubusercontent.com/18194034/43047318-9074409a-8da3-11e8-9305-8a33dbcfc94e.png">
](https://youtu.be/FwGF9g3t3Vw) 

There are three main strategic components to the Democracy Earth governance platform, Sovereign: it is blockchain based, open source, and designed to be as simple to use as a social media platform.

**Why blockchain and not just an online platform?** 

In the next section we will learn exactly how a blockchain works to store information in an incorruptible way. Until then, what is important to know now is that blockchain technology is necessary for security and censorship resistance. In order for election results to be trusted on this platform, it has to be blockchain-based, so that all users are able to see that votes have been tallied accurately. 

Web-based voting platforms are centrally run. They have one organization that manages the platform, and this centralization makes it easier to tamper with or even shut them down. Blockchain based platforms are decentralized and maintained by nodes – essentially people running a program on their computer – making them much harder to shut down. Alternative governance platforms like Democracy Earth are most necessary where  governments are repressive, where transparency is nonexistent and where voters face the greatest threat of censorship. By using blockchain technology, the Sovereign platform is resistant to both hacking and censorship.

**Why must the platform be open source?** 

Open source describes software with source code that anyone can freely inspect or use. Another property of open source is that anyone is able to contribute code, so it is a truly open and transparent process of creation. For Democracy Earth, the open source ethos extends beyond code, carrying into decision-making too. For example, topics concerning the platform are regularly debated on the Democracy Earth Github [repository](code.democracy.earth). Even our white paper The Social Smart Contract was created in open source, with contributors adding to it from around the world.

**Why a “social media feel”?**

Good civic tech needs to be something people will want to use everyday. Although people should be encouraged to participate in their own governance, too often are actively shut out by densely written, legalistic policy language or by practices that are difficult to understand without a political science or law degree.  At Democracy Earth we aim for the exact opposite – to use clear, simple, everyday language and an easy, user-friendly interface that allows anyone to propose a topic of discussion, vote, or delegate their votes to someone else to vote on their behalf. People can use the app for other types of organizing - not only for political decision-making but for day-to-day uses, like deciding on a weekend gathering or what kind of food they want at their office. It is a design enabling simple governance that is inclusive and as easy as clicking “like”.

While Democracy Earth will have a social media look and feel, other features will vary widely relative to typical social media platforms. Unlike Facebook, Twitter, Instagram and other platforms, actions taken on on Sovereign will not be aggregated and sold to advertisers. Users will not be put into ideological boxes where they are limited to viewing topics and votes that they agree with. Right now, users are the *products* of most social media platforms: most do not realize to what degree their information is being sold to researchers and advertisers, or to what degree their consumer, political, and cultural preferences are being manipulated. With the revelations of how user data were improperly shared during the 2016 US election by data consultants Cambridge Analytica -  enabling its clients to influence the outcome through targeted campaign advertising -  it is clear that data ownership is a critical issue for protecting free thinking and democracies. With Democracy Earth, it will be impossible to collect data to manipulate users, enabling it to become a forum for true discussion and decision-making rather than an algorithmically curated echo chamber.

Our mission at Democracy Earth is to create a governance platform with all the good qualities of social media – the accessibility, usability, the global facilitation of discussion and the sharing of stories. Given the decentralized nature of blockchains, there will be no governing body with the ability to collect data or manipulate feeds; Sovereign would not be able to mirror any of social media’s negative aspects. Most importantly, users will own their data, meaning they cannot be exposed to the kinds of psychological manipulation enabled by centralized applications like Facebook.

Another key difference from centralized social media: while a “like” or a “retweet” on centralized platforms might show support for a person or idea, in practical terms these signals serve the purpose of feeding attention-mining algorithms that generate profit to the private organizations controlling the apps. With Sovereign, because there is no middleman, all benefits from the use of the platform go to the users. They keep their data, they make meaningful decisions about their own lives.

Ultimately, Sovereign will help realize the principles expressed in the Universal Declaration of Human Rights:

*“Everyone has the right to freedom of opinion and expression; this right includes freedom to hold opinions without interference and to seek, receive and impart information and ideas through any media and regardless of frontiers. Everyone has the right to freedom of peaceful assembly and association. Everyone has the right to take part in the government of his country, directly or through freely chosen representatives.”*

<a name="Blockchain"></a>
# 2.0 Blockchain Basics

In this section we will learn about the technology and history behind blockchains, in order to understand how blockchain networks provide censorship resistance and security for the Democracy Earth platform.

## 2.1 Origins of Bitcoin and blockchain technology.
### "Privacy is necessary for an open society in the electronic age.”
Eric Hughes | *The Cypherpunk Manifesto*

Bitcoin and blockchains are products of a particular intellectual ecosystem, one that arose from a series of technological innovations and far-seeing individuals. Though these seem like new innovations, in fact the fundamental cryptographic technologies underlying the Bitcoin blockchain were created in response to a collection of important political and mathematical developments in the second half of the twentieth century.

Throughout World War II, the Allied and Axis powers secretly developed systems of mathematic codes and ciphers to relay sensitive wartime information between field commanders and their superiors. Only those who possessed the proper key could read the information – so the key was only shared between the two parties communicating. These messages were sometimes called cryptographs. Some of the Allied nations - namely the U.S. and Britain - created their own ways of using cryptography (the codes and ciphers) to securely send messages.

However, these nations also needed to pioneer ways of decrypting the cryptographs sent by their enemies (Germany and Japan) without knowing the keys. This process is called cryptanalysis. Several major battles were won by the Allies through the efforts of early cryptanalysts who worked tirelessly and in complete anonymity from the public to crack the ciphers used by the Axis powers - the most renowned one being Alan Turing for his breakthrough accomplishments in the field.


![10926282_827780993955768_6579335784379262103_o](https://user-images.githubusercontent.com/40152411/41207409-69abcc16-6cca-11e8-9e51-40a4f7391a9c.jpg)
 
 At the end of the war, military shifted its focus to the maintenance of national security. The Cold War political climate ushered in an era of information warfare and espionage between the United States and Russia. This led the United States executive branch to leverage the powers of Congress to allow the FBI and other intelligence agencies to use wiretaps and digital surveillance methods on U.S. citizens. Around the same time, [two publications](https://www.codesandciphers.org.uk/heritage/ModSec.htm), the US Government Publication of the *Data Encryption Standard* and Dr. Martin Hellman’s *New Directions in Cryptography*, demonstrated the value of cryptography for secure data communication. More importantly, these publications revealed new forms of cryptographic technologies that otherwise would not have been available for use by the general public. 

In fact, Dr. Hellman’s writing on “public-key cryptography,” also known as asymmetric cryptography, was the first of its kind, and later inspired the work of individuals such as Eric Hughes. In 1992, Eric Hughes, Timothy May, and John Gilmore founded a small group of mathematically savvy firebrands to share ideas about increasing individual privacy through the use of cryptography. Jude Milhon, an attendee of the first group meeting, was credited with naming the group “Cypherpunks”, a clever combination of cipher and cyberpunk. More like-minded individuals began to attend the group’s meetings and this free flowing sharing of thoughts eventually culminated into Eric Hughes’  [*A Cypherpunk's Manifesto*](https://www.activism.net/cypherpunk/manifesto.html).


![41207401-484bcc06-6cca-11e8-991c-7e4c274f8641](https://user-images.githubusercontent.com/18194034/42785958-5ea84208-8922-11e8-8b34-b01585712430.jpg)

The document outlined the beliefs and vision of the Cypherpunk movement. Hughes explained the distinction between privacy and secrecy throughout the manifesto, famously writing that 

***"Privacy is necessary for an open society in the electronic age. Privacy is not secrecy. A private matter is something one doesn't want the whole world to know, but a secret matter is something one doesn't want anybody to know. Privacy is the power to selectively reveal oneself to the world.”***

Yet perhaps the most powerful message of the manifesto was that in order for society to successfully enter into the electronic era, it would be necessary to increase individual privacy. The Cypherpunk movement and its vision of an electronic era that guaranteed the human right to privacy has inspired generations of new dreamers to continue using cryptography in pioneering ways. Blockchain technology was one of these ways. Throughout the next sections of this unit we will explore the various components that were combined to create the Bitcoin network. 

## 2.2 Peer-to-peer networks
### “A purely  peer-to-peer   version   of  electronic  cash  would  allow  online payments  to be sent  directly from one party to another without  going through a financial institution.” 
Satoshi Nakamoto | [*Excerpt from Bitcoin Whitepaper*](https://bitcoin.org/bitcoin.pdf)

Bitcoin, and the underlying blockchain technology, was created by an anonymous individual or group called "Satoshi Nakamoto." Satoshi wanted to create a "peer-to-peer version of electronic cash." **Peer-to-peer** basically means person-to-person or without intermediaries. In other words, no intermediaries. It's a term used to describe a network in which participants can communicate with each other *directly*, without the need for centralized **[trusted third parties](https://users.soe.ucsc.edu/~abadi/Papers/verif.pdf)** (TTPs) to intermediate the exchange of services or the transfer of data.  Peer-to-peer networks are becoming a staple of the 21st century “sharing economy” business model. Uber and AirBnB are partial examples of a peer-to-peer because while the services are provided in a peer-to-peer manner the payment and governance still happens through a centralized company. The bitcoin blockchain is an example of a truly peer-to-peer network. 

## 2.3 How can a truly peer-to-peer Internet of Value be enabled?  What is the double-spend dilemma?

### “We propose a solution to the double-spending problem using a peer-to-peer network.”
Satoshi Nakamoto | *Excerpt from Bitcoin Whitepaper* 

A peer-to-peer network in the physical world is slightly simpler to create, where individuals can directly exchange cars, rent their rooms, or trade services. But Satoshi was not trying to create any sort of physical peer-to-peer network; instead, his goal was a completely digital network where individuals could send money to each other. In the physical world, someone either hands you cash or they do not. In contrast, a digital exchange of digital money creates a host of issues, not least of them requiring trusted organizations – usually banks – to serve as intermediaries. Creating a peer-to-peer network that can operate without the need for centralized intermediaries is the first step towards democratizing the way we share data. It also happens to be a difficult task because this network must be able to communicate valuable data (such as money, or votes) **without allowing it to be replicated**. How to create such a network had baffled the worlds best cryptographers and cypherpunks until the release of the bitcoin whitepaper in 2008.


#### 2.3.1 The Double-Spend Dilemma:

This brings us to the difference between the internet of information and the internet of value. The **internet of information** contains websites and digital communication protocols that allow for the sharing of materials such as emails, photos, or documents. Right now on the internet of information, when you want to send some piece of information you are not sending the original but rather a duplicate (copy) of the data.  The sender of information still retains the original photo or document when a message or email is sent. **The internet of value** deals with the sending of a different class of things -- things that have value due to their scarcity such as a vote, intellectual property, or money.  In these type of transfers of valuable digital items it is crucial that the sender relinquish ownership of the data - this is the concept of [*digital scarcity*](https://www.vox.com/videos/2018/5/24/17390778/cryptokitties-blockchain-explainer). The sender must send the original and not a copy - this is so that the original sender cannot use the same valuable data to make the same transfer to a new party -- a practice known as "double spending." In the Bitcoin whitepaper Satoshi Nakamoto explains a solution to this double spend dilemma -- one that used peer-to-peer networks -- as well as several other technical elements that we explain below.


## 2.4 What is a hash function and why are hashes important in peer-to-peer networks?

#### 2.4.1 Hash & Hash Function
A **[hash function](https://learncryptography.com/hash-functions/what-are-hash-functions)** is a mathematical process that takes any kind of digital message and turns it into a unique sequence of letters and numbers *that always has a fixed amount of characters*. For example, it could take my digital image of an apple and turn it into 256 bits. It would also take something much longer and more complex -  say, the draft of a novel - and turn it into a different 256 bits. It can be thought of as a mathematical operation that transforms any input of arbitrary data into a fixed-length numerical value. This numerical value is called a **Hash**.  This hash value is represented by a string of characters that includes numbers and letters.  The Hash can be described as a **digital fingerprint** that is unique to a single input of value. No input can have more than one unique hash, and no hash can refer to more than one unique input. If there is any change in the value of the input then *the hash itself must change completely*. Adding a leaf to our earlier example of digital image of an apple would result in a completely new and different hash. Hence the term digital “fingerprint” - no two hashes (of different input data) are ever alike.

So what is the purpose of utilizing hash functions in a blockchain network? As described above, hash functions will only return a single unique output given the same input.  If there is any change to the message being hashed, then the hash of the message changes completely.  This fundamental property of hash functions is exactly what blockchain networks leverage to make the ledger **immutable**. On the bitcoin network, people make transactions -- essentially sending bitcoin to each other in exchange for some good or service. Groups of transactions (called **blocks**) are periodically (for the Bitcoin blockchain, every ten minutes) pooled together and all of the data that comprise each transaction are combined and hashed.  When the new block of transactions is ready, the hash of the previous block is included as part of the transaction data to be hashed for this new block.  This creates a chain of hashes, meaning all of the transactions that come before a new block are inextricably linked to the hash of the new block.  This prevents anyone from going back and changing a transaction -- even if it were one transaction thousands of blocks back -- because when the new block is hashed, the slight change would cause that hash to look entirely different than the hash of the legitimate blocks. This means that any attempt to alter the network is **immediately detectable and will be rejected** by other people using the network who have the hash of the true transaction history.

## 2.5 What is public key cryptography? How do digital signatures enable peer-to-peer value transfer?

[<img width="667" alt="screen shot 2018-07-16 at 17 29 28" src="https://user-images.githubusercontent.com/18194034/42784813-57001d7c-891e-11e8-9d76-5cd4c26378d5.png">](https://www.youtube.com/watch?v=SOW9i4cd-Qk)


#### 2.5.1 Trusted Third Party
Traditional computer networks use what is known as a **client/server architecture**.  **The clients** are the individual computers that access the network.  **The servers** are the computers which host the data that is accessed by the client computers. 

In networks where valuable data such as money or sensitive personal information is transferred, the use of [trusted third parties](https://users.soe.ucsc.edu/~abadi/Papers/verif.pdf) is required to relay data between users securely.  These TTPs act as _servers_ that (1) **verify the identities** of the network participants, essentially making sure that users attempting to transfer valuable information cannot send information as someone else, and (2) ensure that the data being communicated is **authentic and trustworthy**. As we mentioned before, banks are a great example of a trusted third party, acting as an enabler of transactions between its clients.

However, in peer-to-peer networks the need for TTP’s is replaced by the clever use of cryptographic technologies, one of them being public key cryptography.  Digital signature schemes are an application of public key cryptography that allow for anonymous actors to verify each others’ identities without the need for TTPs. 

### 2.5.2 Digital Signatures

[Digital signature schemes](https://ee.stanford.edu/~hellman/publications/24.pdf) are one of the applications of the public-key cryptography method proposed by Dr. Hellman. This method enables two parties to exchange encrypted messages and verify each other's identities without needing to communicate or share the key required to decrypt the message. It's one of the underlying technologies of blockchains that allow users to circumvent the need for TTPs (trusted third parties) to verify the identity and authenticity of their messages in computer networks - meaning that the receiver knows both who the message came from, and that the information is directly coming from the sender and has not been tampered with. 

**Here's how it works:**  

An algorithm generates two keys. One key is a **private key**, which as the name suggests, should always be kept private. The other is a **public key** which can be made publicly available for all to see. 

The two keys are mathematically linked to each other. This means **everything that is encrypted with your public key, can only be decrypted with your private key. And everything that is encrypted with your private key can only be decrypted with your public key.** This allows you to both **encrypt** and **sign** messages.

When **encrypting**, you use the recipient's public key to encrypt a message, so you can be assured that only he can read it because only he has the private key that will allow him to decrypt it.

When **signing**, you use your private key to encrypt your message's signature. This way, anyone can use your public key to verify that that signature came from you, because your public key could only decrypt a signature that was made with your private key.   

How is this employed in bitcoin? You use your private key to sign/send transactions, and they are addressed to someone’s public key -- or more precisely an address derived from it. You can know who sent you a transaction too, because the transaction will be signed with the sender’s private key which is mixed together with the hash of the transaction. This means that the recipient does not end up with the sender’s private key undercutting the sender’s privacy because the private key is now combined with a transaction hash that is specific to that particular transaction, and verifiable with the sender’s address/public key.

## 2.6 How do all of these pieces of technology combine to create a peer-to-peer network that solves the double-spend dilemma? 

[<img width="674" alt="screen shot 2018-07-16 at 17 28 35" src="https://user-images.githubusercontent.com/18194034/42785243-c7719e4a-891f-11e8-9dd5-2f19996ea812.png">](https://www.youtube.com/watch?v=yh3tSHLb-2E)
 
### “Digital signatures provide part of the solution, but the main benefits are lost if a trusted third party is still required to prevent double-spending.”
Satoshi Nakamoto | *Excerpt from Bitcoin Whitepaper*

Hashes and asymmetric cryptography provide two crucial elements for building the bitcoin network, but in order to understand how Satoshi Nakamoto solved the challenge of creating a peer-to-peer network where value can be shared we will next turn our attention to **nodes** and the **protocol** [they use](http://lopp.net/pdf/Bitcoin_Developer_Reference.pdf) to secure the bitcoin blockchain.

### 2.6.1 Nodes

In the context of a blockchain, **nodes** are computers running software that maintains the bitcoin network. Anyone can download the software and become a node if they so choose. Basically, instead of having employees looking into the transactions as banks do, the Bitcoin blockchain lets nodes perform those tasks. Nodes are responsible for storing a shared ledger of the network's entire transaction history and maintaining the integrity of the network. A ledger is typically a book or other collection of financial accounts, in this case of bitcoin transactions. The nodes run special algorithms, we’ll call them the “**bookkeeping software**”, that periodically check transaction pools - meaning all of the transactions submitted by network participants within a specific timeframe - to make sure they are congruent with the history of all previous transactions. In this way, these nodes are able to keep the inegrity of the network without relying on trusted third parties.  

If this seems a little incomprehensible an example might clarify it. In a football game each player knows what the score is at any one time because they all have the ability to look up at the scoreboard and see it. No one could change the score without convincing a majority of the players that there was a good reason to, or literally overwhelming them with force -- like tackling the scorekeeper and anyone who tried to stop you -- until you could change it. Applying this example to the bitcoin network, the ledger is the scoreboard, and the nodes are the players. They can observe every play (transaction), or at least their software can, and so no individual player can secretly change the ledger because they are all watching the transactions come in and storing their own record of them.

### 2.6.2 Protocol
The “bookkeeping software” can more accurately be called the **protocol**.The protocol is a set of rules and requirements that standardize the transactions contained in each block in order to maintain the integrity and functionality of the blockchain - it is what actually prevents double spending. It provides the rules for inter-node communication and the validation of new blocks.  There is no need to fully understand the protocol, but just for clarity here is an example of some of the rules of the protocol for validating nodes:
1) Check syntactic correctness of each block
2) Reject if we have duplicate of block in any of the three block categories
3) Transaction list must be non-empty

All the nodes mentioned above are running software that automatically checks if a block of transactions matches these rules. If it does, the nodes accept that block as valid, if it doesn't, then the nodes reject it. 

### 2.6.3 Proof of Work and Miners

[
<img width="674" alt="screen shot 2018-07-16 at 17 29 06" src="https://user-images.githubusercontent.com/18194034/42785658-56d18cb6-8921-11e8-95f3-44851dbace39.png">
](https://www.youtube.com/watch?v=ErxlYOCFCvM)

The network is made up of nodes who are following this protocol, but there are different types of nodes. Partial nodes, which have downloaded a part of the ledger, full nodes, which have downloaded the entire ledger, and full nodes that are also miners, meaning that they are actively submitting blocks of transactions to the ledger for other nodes to examine. Since miners do this extra process of bundling, hashing, and submitting transactions, they need an extra incentive on top of just being able to see first hand a secure ledger of their transactions. They need an incentive for behaving honestly so that they keep the ledger's integrity. This incentive comes through a process known as **Proof of Work**. It provides a reward system which makes any attempts at double-spending economically and computationally costy. 

The protocol is being applied by all nodes, but it is miners who package together transactions and submit them to the network so that other nodes can examine them. By participating in this process miners have a chance of winning bitcoin as a reward. The miners then have another incentive to only submit valid transactions because their bitcoin reward will only be valuable so long as the bitcoin network itself is secure. This creates a financial incentive to maintain the network's integrity, and the process has been working well in this decentralized, uncoordinated manner for the past decade with nodes all over the world working to ensure the integrity of the transactions. All blockchains that use Proof-of-work, which at the moment is all major blockchains, have miners engaged in a process that is the same or very similar to the one we are describing.


### 2.6.4 How does mining work?

About every 10 minutes a new block is composed, with all the network transactions from the previous 10 minutes contained within. The big question here is, of all the miners, who gets to be the one to mathematically compose this new block and link the next block to the chain and earn some Bitcoin? 


In order to decide that, the system creates a challenge for all the miners to solve. Whoever solves it first gets the right to validate if the transactions from the past 10 minutes are in accordance with the protocol and to attach them to the blockchain -- and to earn some Bitcoins in the form of a reward and all of the transaction fees associated with the transactions in that block!

This challenge is based on a hash function. Currently the one that is utilized is called **SHA-256**. “SHA” stands for “Secure Hash Algorithm.” The SHA-256 hash function transforms a piece of input, let's say the message 

###### 'Hello'

and adds numbers to the end of the input, or **base string**, which can be:

###### 'Hello1' or 'Hello2' etc.

...so that when that message is hashed, the resulting hash starts with four 0s. 

Here is an example of a hash created by SHA256:

###### 0000c3af42fc31103f1fdc0151fa747ff87349a4714df7cc52ea464e12dcd4e9

The challenge is to find out what are those numbers that, when added to the end of the base string, will result in the hash *starting with four zeros.* 

When we hear that computers are “mining bitcoin”, what that actually means is that they are essentially solving a big guess and check problem. The software they are running is trying, randomly, by trial and error, to find what numbers were added to the input in order to originate that hash. They keep trying all possibilities until they find the right one and the first to do it gets to validate the next block.

![41691617-558679fa-74b0-11e8-887c-bd4e7d96d17f](https://user-images.githubusercontent.com/18194034/43021088-68d6c770-8c30-11e8-80c2-f32043c5a0e9.gif)

Any computer can compute more than 4,000 trials per second, so as the number of computers competing for the right to validate a block increases, the system adjusts the difficulty of the challenge so that it corresponds to the current computational power available. It does this by simply adding more leading zeros. This ensures that new blocks are always "mined" every ten minutes. This is why the process is called Proof of Work: in order to mine Bitcoin, computational processing work is involved.  Attaching a computational cost makes submitting false transactions uneconomical because then you would have to overpower the network in order to have the right to validate the next block and submit your false transactions in it. 

**Anyone can become a miner,** and this fits in with the democratic nature of bitcoin. All you need is a computer with sufficient processing power and enough energy to run it, but if you had these resources you could start up a node today and begin competing to validate a block and receive the mining and transaction fee rewards. Some people create mining pools, where multiple miners join together. This means they are likely to receive a mining reward more often because of their greater computing power, but this also means the reward will be smaller as it will be split between them.


When PoW is combined with the protocol and digital signature scheme, double spending is effectively eliminated as a potential threat. This This gets us back to the reason we are learning about bitcoin -- because the nodes are located around the world, and no single node or group of nodes is more important than another, the network cannot be easily shut down making it **censorship resistant**. The bitcoin network involves thousands of nodes to verify transactions against the protocol, as well as miners with a strong financial incentive to maintain the integrity of the network so that their block rewards are made up of a valuable token. These components create a secure, distributed, and censorship resistant network that has no need of centralized intermediaries. 

<a name="Global"></a>
# 3.0 Global Decision Making & Universal Basic Income

In the previous unit we learned about blockchain technology. In this unit we will build on that by looking at how blockchains can help us make decisions globally. This section will be less technical as we focus on the state of governance in the world. We will focus on how globalization connects to governance, the concepts of the Land and the Cloud and the control each exerts in our lives, what a jurisdiction means in the age of blockchains, and how Universal Basic Income supports democracy.

## 3.1 The Land: Limitations of nationally-based governance in a globalized world

[<img width="600" alt="screen shot 2018-07-23 at 21 50 03" src="https://user-images.githubusercontent.com/18194034/43112113-6ef2a8c4-8ec2-11e8-9b34-3af24cd22eda.png">](https://www.youtube.com/watch?v=l27t0Yf_Thg)


In our deeply interconnected societies, where our economies and ecology are globalized and trends spread rapidly over the webs of social media, national governments are inherently limited in their abilities to confront many of the issues that affect us, such as climate change, refugee crises and technological disruptions. This incompatibility between a globalized world and national governments often makes our political systems ineffective and increasingly vulnerable to forces outside of their control.   

We are accustomed to thinking about the world in terms of nation-states: land-based governments that organize our life as a society. Another way to gain insight into the nature of our political lives is by focusing on The Cloud, which corresponds to the biggest internet corporations. The amount of power and influence these centralized organizations exert on our society is comparable to that of nation-states. They contain an unprecedented amount of data about individuals, easily co-opted by actors willing to influence the direction of political events, as demonstrated by the Cambridge Analytica revelations.

As citizens of the 21st century, living between the Land and the Cloud, we are discovering that our control over our own lives is limited. Establishing a functional model would require a new kind of governance where citizens of different nations can come together to collaborate on decisions regarding the challenges they collectively face – a concept Historian Yuval Noah Harari makes clear with the following simple story:

*Thousands of years ago, many different tribes lived along the Yellow River in China, relying on it for their survival and suffering from its periodic floods and droughts. Individually, no tribe could do much about it as each only controlled a tiny portion of the river. So they coalesced together to form the Chinese nation, with the ability to build dams and canals, regulating the river and bringing prosperity to the entire region.*

In the 21st century, around 200 different Nation-states are all living along the same challenging river, which today represents a host of issues looming above our heads such as like climate change, mass migration of refugees, transnational terrorist groups, global corporations driving rising inequality, automation eliminating jobs by the millions, and the urgent threat of an Artificial Intelligence-driven arms race.

Today, disenfranchised countries and communities have no way to address the issues that most impact the lives of their citizens. Historically, patriotism has given us the ability to tackle local issues by coordinating cooperation among large groups of people. Now the challenges that impact our lives most directly are no longer local, but take place in a deeply networked and economically globalized system. Like the ancient tribes along the Yellow River, Nation-states are individually inadequate to address those issues and protect their citizens from them: if one country tries to properly regulate any of those areas it will likely undermine its competitive advantage in comparison to the other unregulated countries. For example, if a country tries to implement environmental regulations on a multinational company that company might just move to another country, taking its economic development power with it.

On the other hand, coalition agencies such as the UN are still extremely ineffective in promoting a globalized governance, as member buy-in is ultimately optional. As Peter Schurman from One Global Democracy puts it:

*“Since countries only have to work together as far as they agree to, there’s every opportunity for disagreement and for failure to do what needs to be done.”*

It is also worth noting that the very five countries that hold veto power at the UN — China, France, Russia, United Kingdom, and the United States — also happen to be the ones responsible for the vast majority of all major arms exports in the world. Where that leaves us with the prospect of having the UN as a champion of global peace is unclear.

## 3.1.1 The Cloud

While most of the problems listed above pertain to the land, the Cloud is also a formidible and flawed realm. *The Cloud* controls our data. Major internet corporations have the ability to track and aggregate data regarding most of our digital activities. In a way, they know users better than users know themselves, and over and over have demonstrably predicted and influenced user behaviour. Even though Internet monopolies stand as the gatekeepers of online privacy, it should not be forgotten that, theoretically, Facebook has the power to impersonate any of its 2 Billion registered users should it ever desire to. 

Google and Facebook hold the largest identity databases in the world, surpassing the governments of India and China. With 97% of their reported revenue coming from advertising, their source of income strongly influences the kind of experience that users get with their technology. In other words, users find themselves in bubbles not of their own making, but defined by the invisible hand of the profit-optimizing algorithms of the social media giants. It is in their corporate interest to gather as much information as possible to profile people in order to stay competitive in the attention market, and both companies filter information fed to users with algorithms accountable to no one but their own board. 

Uncensored, free and sovereign debates on the future of humanity are being eaten by attention-farming algorithms and useless likes that help only to perpetuate these corporate entities. Fake news exploits (as were used during the U.S. elections) or critical content spreading like wildfire (as happened during the Arab Spring) demonstrate that any effort to stop international influence on national politics is futile as societies spend most of their time online. Simply put, the Internet is bound to challenge Nation-States, and in a sense, incompatible with their territorial domains.

## 3.2 Towards an Inclusive Global Governance
 
[<img width="582" alt="screen shot 2018-07-23 at 21 59 52" src="https://user-images.githubusercontent.com/18194034/43112363-c345e552-8ec3-11e8-9815-cb8133531cc5.png">](https://www.youtube.com/watch?v=oJ1QCMv8O5M)

The idea of humanity united under the same governance system is anything but new and does not need to come about in an imperial manner. Visions of global governance date back to the ancient Chinese and Indian civilizations. The approaches to this vision are as varied as its defenders whose ranks include Albert Einstein, Immanuel Kant, Mahatma Gandhi, Dante Alighieri, and Martin Luther King Jr, among many others. Now, with blockchain technology, for the first time in history individuals can actually build this kind of global system of cooperation from the bottom up.

For many, global governance can sound like an oppressive and hegemonistic idea, with good reason — the first forms of globalization we witnessed in history were accomplished through bloody conquest by empires. In the modern era, the word globalization brings to mind an explosion of opportunity that has not been equally distributed. Some geographies have enormously benefited because of liberal trade policies, mass migrations, and increased travel. Yet, to large segments of the population, the globalization of our economies did not improve their lives - instead they have borne the costs of it, being exposed to pollution from multinational conglomerates, brain drain, and increased inequality. 

The question now is how we ensure that the benefits of globalization are shared equally and the costs minimized as much as possible. The pains caused by globalization are largely due to the fact that only a small number of countries -- and even a small group of people within those countries -- shaped the policies that guided this process. Lesser developed countries had worse standing in trade negotiations and the forming of regulatory policies. This meant that the globalization of the economy took place without a globalization of the decision making process. Blockchain technology can help to change that, because while it ultimately empowers individuals (and their local communities), it is also inherently transnational, enabling dialogue and collaboration. 

### 3.2.1 Blockchains Create a New Jurisdiction

Blockchain technology creates **a layer in between The Land and The Cloud**. In effect, a sovereign jurisdiction where individuals have control of their identity, their data, and the ways in which they connect with each other.

This changes the dynamics of governance: the economically-driven tension between local and global can be overcome by a global system of governance that is based on blockchain networks. Local and global are woven together because in such a model decision-making is enacted from the bottom-up, from the individual level, by means of a technology  that is inherently transnational, empowering disenfranchised groups and small local communities to have a say on the global agora about the global forces that determine their futures.

As Democracy Earth Foundation sets out to create a blockchain-based governance platform, our goal is to strengthen traditional forms of participation with incorruptible decision-making tools. We understand that in the inter-connected reality that we inhabit, it is necessary to enable one more layer of commitment: in addition to being citizens of a country, we need to be citizens of the world --  and global governance is the next logical step in a world already connected over the Internet.

It is extremely fortuitous that exactly when humanity most needs it most we are seeing the rise of blockchain technology, enabling us to achieve global cooperation that can be built by citizens from the bottom-up and generating transparent and legitimate decision-making. We can have liquid governance establishing the foundations for a democracy of peers, and in that context even permission from established Nation-States is not required: citizens anywhere in the world can embrace this change using blockchain-based networks.

### 3.2.2 Universal Basic Income and Democracy 

The same technology that enables the creation of a global governance system also enables the distribution of a universal basic income.   During Unit 6 of the curriculum we will return to *digital identity systems*, another piece of technology that is necessary for UBI; for now, we have seen that blockchain technology is a powerful tool to securely and widely distribute value with no chance of corruption or mismanagement of the funds.

Universal Basic Income has recently become a hot topic due to its ability to support societies whose populations are rapidly losing jobs due to automation. Despite this recent technology specific interest in UBI, it has a long and well researched symbiotic relationship with democracy. Successful democracies typically only emerge in places that have reached a certain level of economic development and a UBI can help rapidly move countries to this place. According to research presented at Basic Income Earth Network (Munich September 2012), the implementation of basic income can greatly contribute to realizing the principles of democracy because it brings about a base level of economic well-being within society that allows for more full democratic participation.This is not to say that the technology specific argument for UBI is untrue -- UBI both supports democracy and is critical for weathering the effects of automation and job displacement. 

While UBI is typically examined in the context of a single country, to be truly universal it must be distributed internationally because already we see that the use of a new technology in any given industry or country can have effects that reverberate around the world. Blockchains are ideal technology for UBI implementation, as they can enable such an international distribution, for the realization of a truly universal basic income.

# 4.0 Smart Contracts & Liquid Democracy

On the previous section we examined governance on a global scale. On this section we are going to turn our attention to a smaller scale -- the governance structure within any given country. We also introduce a complementary piece of technology to blockchains: smart contracts, which run on top of blockchains. We will develop an introductory knowledge of smart contracts and learn how they enable a voting structure called liquid democracy. 

## 4.1 Smart Contracts

### What is a smart contract?

A smart contract is a computer program that is stored and executed on a blockchain, enabling a new paradigm of "programmable money". A basic analogy can be made with a vending machine: if a person puts in some amount of money, an item will come out. Smart contracts can also employ loops and conditional statements to any desired degree of specificity -- an example would be a contract meant to send a friend (or the holder of any given public key) a pizza, where funds sent to the smart contract can only be spent at one particular pizza store and where the funds are returned (gradually, or all at once) if a pizza is not purchased by the friend in the first 72 hours after being deposited. The pizza order, signed with the private key of the pizza receiving friend and sent to the smart contract as a transaction, would release the funds to the pizza store.

The concept of smart contracts are most often discussed in relation to the Ethereum network, but the term was first coined by Nick Szabo [back in 1996](https://bitcoinmagazine.com/articles/smart-contracts-described-by-nick-szabo-years-ago-now-becoming-reality-1461693751/) and in theory they are not unique to Ethereum. A multi-signature wallet (where multiple parties need to sign for a transaction to go through) for bitcoin, is also a basic example of a smart contract. Smart contracts in Ethereum are programmed in a language called Solidity. The applications are not limited to only basic financial transactions, but could also automate the collection of royalties, the execution of wills, or the transferring of housing ownership. 


### How do smart contracts work?

The beauty of smart contracts is that it allows people to transact with each other without having to necessarily trust that the other party will fulfill their end of the agreement - they can rely on the smart contract to execute according to how it was programmed. Smart contracts get executed when they are interacted with, usually when they receive money, or when some external “oracle” indicates that an event that the smart contract is programmed to watch for has occurred. For example, with the executing of a will, say the smart contract was programmed to begin when an obituary was posted in the newspaper.

Sending a transaction to a smart-contract is like sending a transaction to any other blockchain address, but there is an additional deployment fee for the creator of the smart contract, denominated in the currency of the host blockchain (ETH for ethereum). The more complex a smart contract becomes, the higher the deployment fee becomes -- this is due to the fact that the smart contract will have to be stored and executed on all of the nodes that compose a network, which takes up space. Given the programmable nature of smart contracts, the applications that run on top of smart contracts are known as decentralized apps or **dApps**.

## 4.2 Proof of Stake

Proof of Stake (PoS) is a proposed alternative to Proof of Work (PoW) for preventing sybil attacks and establishing consensus in a decentralized network. Although the details are still being worked out, PoS promises an anti-sybil solution which requires significantly less electricity consumption than PoW. 

A user's chance of winning a block reward in PoS does not rely on the power of their computing device as it does in PoW. Instead, the number of coins a user/staker holds -- or their "stake" in the network -- determines the chance that they will be pseudo-randomly selected to act as the main validator for a certain amount of time. Users who are heavily invested have less incentive to act dishonestly -- if they act dishonestly, their staked coins can be destroyed or "burned".


## 4.3 Issues with Representative Democracy:

Smart contracts are one of the fundamental technological innovations that permit us to envision a token-based liquid democracy. But before we learn about how smart contracts alllow for a new kind of decision making, it is necessary to take a detour to see why national governments need updating at all. 

Most traditional democracies in the world share one basic system: every four years or so, citizens are offered a couple of candidates to choose from. After voting, citizens' power to decide on anything is frozen until the next election cycle and all they can do is watch events unfold from a spectator’s seat. In between voting cycles, citizens are forced to rely on opinion polls to gauge their contentment, positions and desires.

This system is what we call representative democracy. It was designed as an evolution of direct democracy, which has its origins in ancient Greece, where “legitimate” citizens would gather in a public place  —  the agora  —  and vote in favor or against every decision that was made about the city. However, the direct model wasn’t scalable to larger territories. When voting systems had to be built for larger territories, naturally the voting power of the citizen had to be delegated to a representative. This was a rational decision that reflected the information technology of the time, which was the printing press, and its inability to logistically scale the decision-making process at a pace that contemplated the needs of a large country. At the time, it was natural that some people would have to be solely occupied in making decisions for others. And thus, professional politicians were born. 

For awhile, the model of representative democracies worked fairly well. From the 1970s through teh 1990s, dozens of authoritarian regimes became electoral [democracies](https://en.wikipedia.org/wiki/Wave_of_democracy#Third_wave). Things moved forward in a positive, freedom-promoting direction. Unfortunately, it seems that growth has reached its limits. 

Since 2006, we have been in a global democratic recession. Currently only 45% of the global population is living in countries that are qualified as “free” according to the annual report by [Freedom House](https://freedomhouse.org/report/freedom-world/freedom-world-2018). We live in an age of unprecedented technological connectivy but most democratic governments are fairly opaque and many suffer with corruption. The natural dissatisfaction that arises from that is being leveraged by more authoritarian and populist leaders, who are taking control in countries that once seemed like they were on the path to becoming democratic. Facing the faillure of representative democracy in creating effective governments, authoritarianism is on the rise.

Movements like Occupy Wall Street and the Arab Spring show that it is much easier to protest and even to remove leaders than it is to change politics for the better within the confines of a representative democracy. Often, dissident movements, even when successful, only end up creating power vacuums that get filled by new politicians who will eventually repeat the patterns of whatever system they deposed. Escaping that dynamic requires more than citizens having the ability to connect to each other (given by the internet and social media) and point out the flaws of a given system. It requires citizens to actually have a way to propose functioning governance models that can replace the old ones. 

The flaws in **representative democracy** are not necessarily inherent flaws of **democracy**. The alternative that is being taken by many countries over the past few years is to replace it with more authoritarianism - but there are other paths to be explored. 

Technological connectivity breaks the main premise that once justified the creation of representative democracy in the first place — the necessity to scale the decision making process to a large territory. Now we can vote online. There are no technical impediments that could prevent a willing person to participate in a voting procedure. We are connected by a digital commons. The main justification for representatives no longer applies. In the next two sections we will look at a different model, that fully leverages the technology of today to create a stronger, more legitimate democracy, that can rise to the expectations of citizens of the 21st century.


### 4.3.1 Liquid Democracy 

Democracy is about getting the best possible decision, with the greatest amount of legitimacy. In direct democracy, everyone votes — directly. But there is no way that everyone has the time, interest, or expertise to vote on every single issue. On the other hand, in a representative democracy, we elect other people to vote for us. 

There is a system that combines both of these models -- it is called Liquid Democracy. In a liquid democracy individuals can either vote directly on an issue or delegate their vote to an individual they trust to decide for them. They can revoke that vote at any time if they feel their representative voted incorrectly or if they change their mind on the issue. For example, if Laura is a citizen who knows a lot about housing policy she can choose to vote directly on all issues concerning housing policy. If an issue on nuclear power comes up, she might choose to delegate her vote to her favorite physics professor from college with full confidence that she can revoke it from him if she disagrees with his decision. Instead of having representatives based on territory, we utilize a digital, secure, blockchain-based application to start choosing representatives that we know and trust. They represent us for the specific topics that we assign them.

There are some key advantages to this model:

* It enables leadership to emerge **from the bottom up:** if you are trusted by your peers on any given issue, you can have a larger stake on the decisions regarding it. Anyone can potentially be a "politician" or decision-maker.
* It enables **smarter decisions:** given that more knowleadgeable people are likely to have increased stakes on their subjects of expertise, this is a great model to actually leverage all the knowledge that a society posesses on different policies. A liquid democracy quickly evolves to a peer-review system.

### 4.3.2 Token Based Liquid Democracy 

__***Crypto as corruption fighter***__  
Smart contracts are the technological platform that allows for something like liquid democracy to exist. Smart contracts combined with liquid democracy creates what we call a a “token based liquid democracy,” because votes now operate as programmable tokens. Imagine that in the same way that you have a cryptocurrency transaction running on a blockchain, and those cryptocurrencies can be programmed to operate under certain rules with smart contracts, we can now have vote tokens that enable us to have the same control, auditability, and security over how they operate. Let's examine how each of these aspects can help the fight against corruption:

__**Control.**__  
With a VOTE token- what Democracy Earth is currently developing - citizens will have full control over their vote. This means that once a citizen owns their token, they can delegate it to representatives, but if dissatisfied with how that representative is using their vote, they can revoke that delegation at any time. The ability to revoke at any time brings a paradigmatic change to representation, because it incentivizes better behavior on the part of the representatives. 

Think of the all-too-common scenario of a politician quickly who stops delivering on promises right after the election, with power now guaranteed for four long years. In a liquid democracy, citizens could then immediately revoke their delegations, effectively creating a system in which empty promises are actually unsustainable. This framework creates better incentives for leadership, encouraging representatives to be knowledgeable and honest. It also helps prevent a scenario where people buy delegations, because even if a citizen promises away their vote to someone, they can never lose the ability to revoke it. Unless the buyer can control that person 24 hours a day, or have some other means of control (like being able to harm the person in any way) then there is no guarantee that the purchase will be enforced in the long term. 

__**Auditability.**__   
In a referendum that is made with VOTE tokens, anyone is able to personally audit the results of that referendum and be certain of their integrity. This is because the vote tokens are cast on public blockchains, open for all to audit. This does not mean that anonymity is lost for the voter. Decentralized IDs, which is a topic that we will cover extensively in one of the coming units of this course, enable voters to properly own their data and disclose only as much information as is necessary for any specific context. Cryptography ensures the anonymity of the voters, while maintaining the voting records public for all to check. This level of auditability makes it so one can be certain of the integrity of the results of any vote, knowing that it has not been tampered with or manipulated in any way. 

__**Security.**__  
The ability to do referendums where anyone can easily participate from their phones and have the results be reliable might not be so critical in well-functioning and earnest governments, but it is a game-changer when it comes to repressive regimes. All over the world votes and referendums are suppressed with different kinds of violence or corruption. For example, with physical elections voting places can be attacked or ballot boxes burned. Removing the complex logistics of running an election and making voting a safe act that anyone can do from their phones and their homes empowers citizens to clearly express their preferences with no way for powerful actors to suppress the vote. This is one of the most important aspects of how blockchain technology can help otherwise disenfranchised individuals and even entire nations to fully enact their human rights of expressing themselves and their choice of leaders. 

__**The Value of the Vote**__
In addition to these corruption-fighting properties, blockchain-based $VOTE tokens also have a **financial value**, giving rise to several interesting properties.The idea seems strange at first: if $VOTES have a financial value, would that mean that capital  can overtake the decision-making process? 

It's a legitimate concern, addressed by new technologies that can be employed to prevent this from happening in several different ways, such as  **enabling universal access.** On section 3.2.2 we discussed how blockchains enable the distribution of a Universal Basic Income. By granting $VOTE tokens to every person, as a human right, the fact that they have monetary value does not mean that certain people will be unable to afford them -- anyone who verifies their unique identity is eligible to receive tokens. 

We have discussed previously how buying delegations is a difficult act to permanently enforce, given that every $VOTE owner can always revoke their delegations at any time. It is important to note here that despite one being able to buy $VOTE tokens in the market, having more $VOTEs does not necessarily translate to having more power. The Democracy Earth platform brings elasticity in the potential configurations that can serve a democracy, so different kinds of institutions can be modeled. Any organization can set their **Constitutional Smart Contract** (the contract that will regulate how voting is structured within that organization) to permit one vote to be cast by each member; in this case possessing more tokens does not imply possessing more voting power - even if you had a million tokens, you could only validly cast one vote per issue, like every other member. 

A $VOTE token with financial value enables many benefits to citizens and communities. Even though they only possess a small value, **this value helps citizens think more realistically about decisions**. Scarcity (vs the artificial inflation of being able to like everything, forever) enables decision-makers to send very clear signals about what matters most. 

In the same way that institutions have a limited amount of resources to devote to different budgets and projects and must prioritize their energy, attention, and money, so too voters must prioritize with their own resource of votes. Facebook presents a very good example of how expressions of decisions made via “Likes” which have no financial value attached to them, can quickly become empty conversations with little impact. The sense of limitless possibilities that users get with a "like", where they can "like" everything that they want, is not useful when real-world decisions must be made. This has generated what we know as “slacktivism” where users get a sense of satisfaction from talking about issues online but those posts and shares rarely have consequences in the real world. Causes that effectively use facebook activism are the exception and not the rule. One of the reasons that online campaigning often fail to achieve support goals is due to the fact that “likes” lack impact because they’re infinitely inflatable -- you can like as many things as you want, without any cost -- which diminishes their value. With blockchain-based $VOTE tokens, such expressions are deployed rationally by the users because each vote has a value. This more targeted use of votes can make advocacy movements online more meaningful. 

Facing this global recession of democracy and the growing dissatisfaction even in functioning democracies, token based liquid democracy provides an alternative -- it allows citizens to participate exactly as much as they want to and to have more control than ever over the policy that govern their lives. Liquid Democracy holds potential to be the foundation of decision making in virtual communities, as well as local communities and entire governments -- at a global scale. It enables citizens to be more informed and more empowered to engage with their own governance with their opinions being taken into account more often and on a wider range of issues. In liquid democracy, we have the coming together of technologies - smart phones, blockchains and cryptography - that will ensure everyone owns their own voice/VOTE on a system is incorruptible and censorship-resistant.

# References

[1] https://www.theguardian.com/women-in-leadership/2016/feb/23/how-one-womans-app-is-changing-politics-in-the-digital-age

