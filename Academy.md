# Introduction

The Democracy Earth Foundation is working to update government for the 21st century by building a blockchain-based liquid-democracy platform. In that pursuit, the foundation has spent the past 6 years researching, experimenting, learning and building at the intersection of technology and politics. In our white paper, [The Social Smart Contract](https://github.com/DemocracyEarth/paper/blob/master/README.mediawiki), we explore in detail how a blockchain-based liquid democracy can help the world solve some of the most pressing challenges facing democracy, such as rising authoritarianism and a lack of voter participation.

While Democracy Earth is focused on building civic tech designed to be easy to use on an everyday basis, we also view it as important to provide education regarding the ideas and technology that have made this possible. Due to the fact that The Social Smart Contract contains some technical vocabulary and information that require background expertise not possessed by the typical reader, we are launching this companion curriculum, the Democracy Academy. Our goal is to give readers the foundational knowledge needed to understand the content of The Social Smart Contract, provide a sound understanding of blockchains, liquid democracy and other technical information it contains, and with it help foster a global movement that enables everyone to claim civic participation as their right.


The content of Democracy Academy was developed collaboratively by students for students, but will be helpful to anyone curious about these topics. Our goal is for everyone following this curriculum to emerge with a strong grasp of essential blockchain technology concepts, as well as the history and context around the founding and development of the Democracy Earth governance platform. It is our hope that in doing so we can help a new generation of leaders effectively learn as much as possible about the intersection of technology and politics - and Democracy Earth’s crowd-sourced proposal - so they are fully equipped to advocate for it, contribute to it, and promote it around the world.

Neither the white paper nor the Democracy Academy curriculum are intended to remain static and we welcome contributions from readers to continue improving them. Like Democracy itself, Democracy Academy must always be a work in progress. 



<a name="Background"></a>
# 1.0 Background

In Week One, we discuss the emergence of civic tech/democracy tech and the history of the Democracy Earth Foundation. We will provide an overview of the vision and journey of Democracy Earth founders, and how their experiences and lessons shape our software development and movement.

##  1.1 A group of hacktivists tried to improve their country

Before co-founders Pia Mancini and Santiago Siri launched Democracy Earth and the Sovereign platform, they created a software called Democracy OS, one of the earliest civic tech projects of its kind. As Pia stated in a 2016 interview with The Guardian [1], Democracy OS could not have emerged in a stable country like the US or UK, but only in a country where politics were bad enough that people were willing to take risks. In many ways, their native Argentina - with some of the highest internet access in Latin America, yet some of the most corrupt and unresponsive politics - offered the perfect birthplace for this historic civic tech. 

Pia's political education included years spent developing training programs to teach democratic values, preparing civil leaders for public office - efforts that were succcessful in getting candidates elected as mayors and governonrs. Yet systemic corruption made it clear that working in traditional politics would not be effective in fixing pervasive social issues. Eventually Pia and Santi concluded that it was not enough to try to place better people in the same system, but that the very system itself was an issue. It distanced the voters from decision-making, creating a breakdown in communication between political leaders and ordinary citizens. That inspired them to create Democracy OS, where citizens could learn about current congressional policy proposals, as well as make their own proposals, debate and vote on them. The software translated all proposals into plain language, and was accessible to anyone with a smartphone. Though Pia, Santi and their collaborators offered the Democracy OS platform to political parties, they had no takers; instead, they were "sent away like little kids", as she noted in her [2014 TED Talk](https://www.ted.com/talks/pia_mancini_how_to_upgrade_democracy_for_the_internet_era). 

They were not the first civic technologists to learn the lesson that software alone could not solve the deep divide between politicians and citizens – although better technology was needed, the main barrier was still a cultural one. Undaunted by this rejection, Pia and Santi decided to take a different path, and form their own political party called  “Partido de la Red,” or the “Net Party” in English. The party promised to vote in line with how citizens voted on the DemocracyOS application. In 2013, they campaigned with a large Trojan Horse made of wood, driving it around the neighbourhoods of Buenos Aires. The Trojan Horse signified that while the Net Party was participating in the familiar process of campaigning like a typical political party, it was only a front - they had no intention to behave like one. Unlike the other parties, they intended to actually let citizens guide their decisions directly through their app. While Partido de la Red candidates did not win an elected seat in the parliament, they received 22,000 votes. It was enough for the Congress to take notice and to launch an instance of DemocracyOS to discuss three issues, two on public transport and one on the use of public space.

Partido de la Red and DemocracyOS taught Pia and Santi three important lessons that still ring true today:

1. Civic tech has the potential to revolutionize government. Though it failed to gain a Parliamentary seat, Partido de la Red forced the government to take notice of, and even use, Democracy OS civic tech. Clearly, the idea of online participation had power - it resonated with people. But even with this success, the government did not promise to vote in alignment with the decisions made by citizens on the Democracy OS platform, which led to the second lesson:

2.  While civic tech has a true potential to change government, this change is far from inevitable -  and a simple app that serves as an interface with Congress is not enough in and of itself to make change happen.

3. The third and most painful lesson was about corruption. [Spies infiltrated party meetings](https://medium.com/@santisiri/baptism-of-fire-100392b05726) to generate confusion; they were attacked online, and were even asked to bribe a judge in order to be able to run for the 2015 elections. This first-hand contact with corruption taught them how difficult it is to change the system from within. As Santi has remarked, “it is much more likely that the system will change you first.”
 
🎥[Watch here Pia Mancini's TED talk about DemocracyOS and how to upgrade democracy for the internet era](https://www.ted.com/talks/pia_mancini_how_to_upgrade_democracy_for_the_internet_era)  

## 1.2 Silicon Valley

In 2015 the Silicon Valley accelerator YCombinator - backer of Reddit and AirBnb, among others - invited Pia and Santi to join the Y15 class of nonprofit startups, selected for their potential for global impact. It was here they met Herb Stephens, a former GE auditor and serial software entrepreneur with a 25-year history of building disintermediating systems that shifted power to the user through technology. Since learning of blockchain technology in 2012 and considering it “the best invention since the Internet itself”, Herb dedicated the rest of his career to social entrepreneurism, readily joining the foundation in the role of president and treasurer.

Together Herb, Santi, Pia and Virgile Devile - the Paris-based co-founder of Open Source Politics and one-time team lead for Democracy OS Europe- formed the Democracy Earth Foundation, a U.S. (CA) 501©(3) non-profit.

With these early civic tech experiences, the team was prepared to go well beyond the constraints of the political status quo. They adopted a theory of change best summarized by architect Buckminster Fullers’ famous quote: **“You don’t change the existing reality by fighting against it. To change something, build a new model that makes the existing model obsolete.”** In other words, building an app to interface with existing political systems won’t create change; what is needed is a tool that brings about such an obvious and enormous improvement to governance it renders the current system outdated.

Their new approach was to use blockchains - the same technology underlying Bitcoin - to create a censorship resistant peer-to-peer democracy (terms that will be explained in greater detail later in the curriculum). This new focus would bring massive improvements to three fundamental pillars of governance: 

**Voting**: The current system for voting is both insecure and difficult to audit because it is highly centralized. It can be hacked and manipulated in many ways, and the only people able to verify voting rolls are a very small group of election officials. With a blockchain-based system, manipulating results is functionally impossible as all votes are recorded in an immutable public ledger that anyone can audit.

**Identity**: Today we receive identity from centralized authorities such as governments providing passports and ID cards, and from websites providing passwords, logins and profiles. The Democracy Earth platform will employ a decentralized ID system, allowing citizens to have a secure form of identification beyond the influence of any third party. Democracy Earth will help citizens own their data and identity through the use of new cryptographic technologies, which will be explained in-depth later in the curriculum.

**Representation**: Our system does not provide the right incentives for our representatives to represent us very well. If we disagree with how they voted, we have to wait until the next election cycle to try to remove them which could be many years. We are forced to choose a single representative to represent us on all issues, rather than be able to choose multiple experts from different fields to represent us on different issues. This is why Democracy Earth is building a liquid democracy platform that allows for users to propose, debate, and vote directly on issues, or to *delegate* their vote to someone they trust to vote for them. Representation will be more responsive when you can delegate your vote to anyone and immediately revoke it if they vote incorrectly or behave unethically.


🎥[Meet Democracy Earth's co-founder, Herb Stephens, and his perspective on Liquid Democracy.](https://youtu.be/gWdhc-jxs_s) 

## 1.3 Sovereign

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

🎥[Watch Santi Siri talk about the key aspects of the Democracy Earth platform.](https://youtu.be/FwGF9g3t3Vw) 

# References

[1] https://www.theguardian.com/women-in-leadership/2016/feb/23/how-one-womans-app-is-changing-politics-in-the-digital-age

