# SKALE Hackathon Onboarding

## Table of Contents
* [Resources](#Resources)
* [Bounties](#Bounties-for-EthDenver)
    * [Overview](#Bounty-Overview-Rockies-SKALER)
    * [Judging Criteria](#Judging-Criteria)
* [Hackathon Idea Categories](#Hackathon-Idea-Categories)
    * [Microtransactions](#Microtransactions)
    * [Computation](#Computation)

## Resources
* [SKALE Labs Website](https://www.skalelabs.com/)
* [SKALE Blog](https://medium.com/skale)
* [SKALE Development channel on Discord](https://discord.gg/vvUtWJB) (👈Come here to get your SKALE chain)
* [SKALE Developer documentation](https://developers.skalelabs.com)

## Bounties (for EthDenver)

### Bounty Overview: Rockies SKALER
Description: The most impressive scaling submission based on judgment criteria detailed below.

* **1st Place Prize Amount: $2,000** 🏆
* **Honorable Mention: $1,000 each to up to three teams**

#### Requirements
* [Join our Discord channel](https://discord.gg/vvUtWJB)
* Brief 3-5 minute presentation describing the scaling issue and how SKALE was used to solve the issue.
* Use of a SKALE chain in solution.
* Link to open source code.

### Judging Criteria
Show the world what is possible when we aren’t encumbered with scaling issues. Run smart contracts and transactions at high speeds. Prizes will be awarded to teams based on the following criteria:

**Powerful scaling use cases**: Show off the power of SKALE and show how decentralized smart contract execution in Layer 2 can make an impact on the world.

**Creativity**: This is a new domain. We appreciate creativity and innovative thinking. Now that the constraints are off, show the world what Ethereum can do!

**Effort over perfection**: We love hustle. We love effort. We are prioritizing effort over perfection for the ETHDenver hackathon. We would rather see something hacked together that could be fixed up later rather than something limited by perfection. When we hear your pitch, please tell us about your effort. We’ll also look directly at your code to see the fruits of your labor.

Advancements in both smart contract complexity and computation power vastly increase the types of dApps that are feasible with solidity. While we aren’t expecting someone to be running ADMM Optimization over the weekend, we do hope that people no longer have a fear of running out of gas or using loops in their code.


## Hackathon Idea Categories

### Microtransactions
Presently, the blocktimes on Ethereum make it impossible to create high-throughput dApps. And even if Ethereum had faster blocktimes, the ability to perform microtransactions would likely be prohibitively expensive (with gas costs often outweighing the actual value of the transaction). 

SKALE’s faster blocktimes and decreased costs allow for teams to integrate microtransactions into existing dApps as well as create services to be consumed by other dApps. Here are a few examples of dApps you could build that showcase microtransactions with SKALE:

##### The Jamie Dimon Alarm Clock
Do you find yourself constantly pressing the snooze button on your alarm clock? Well, with The Jamie Dimon Alarm Clock, every snooze is your money in his pocket. 

Users set up their alarm by escrowing money on Ethereum and configuring their timezone, how many days they want the alarm to continue before withdrawing their money, the time of the alarm, and the amount they lose for every minute they snooze the alarm. In this case, SKALE is used to facilitate microtransactions between your deposit and Jamie Dimon’s wallet!

##### PPM (Pay-Per-Minute) Movies
Have you ever decided partway through a movie that it just wasn’t for you? So, you stop watching it, even though you paid for the entire movie.

With PPM Movies, users only pay for what they watch and are charged for each minute of content provided to them. The content is served via some decentralized datastore (we like IPFS) and users are charged each minute that they have data streaming to their devices.

##### ETH Cam
As we become more connected with smart devices, our privacy is constantly being undermined and compromised. Just the other week, it was made known that Amazon’s Ring “provided its Ukraine-based research and development team virtually unfettered access to a folder on Amazon’s S3 cloud storage service that contained every video created by every Ring camera around the world”. 

Between the disregard for user privacy as well as the high fees charged for access to those videos (for users), we know that we can offer something better. We envision a service that encrypts all data on-device and charges users for what they decrypt and view (similar to PPM Movies). Less rent paid to a middle-man and greater privacy. 

### Computation
Smart contracts on Ethereum are succinct and cost prohibitive out of necessity. With SKALE’s increased larger blocks and high gasLimit, we are able to support much more complex smart contracts and computationally-intensive operations. Here are a few examples of dApps you could build that showcase computation with SKALE:

##### Decentralized Kaggle Competitions
For those not familiar with Kaggle competitions, these are competitions in which the host provides a dataset as well as a problem to go along with said dataset. At the end of the competition, the participant with the best solution (as decided in an automated process by the Kaggle Kernels) is awarded a prize by the host in exchange for the right to use the algorithm. 

##### Sorting Microservice
While most engineers regard sorting as a given, blockchain developers have often had to work around this. Have you ever tried to sort an array on Ethereum? It’s more likely that you’ve used a queue or just worked with unordered data - referencing everything by an address as a means of saving gas.

Providing a decentralized service on SKALE that dApps can call to sort their data would be a huge benefit to the community and help to curb some of the compromises being made in smart contracts to fit the gas usage of each block. 