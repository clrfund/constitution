# CLR.FUND CONSTITUTION

## I. Introduction
Clr.fund is a protocol for efficiently allocating funds to public goods that benefit the Ethereum Network according to the preferences of the Ethereum Community. Clr.fund strives for credible neutrality, decentralization, permissionlessness, trustlessness, and pseudonymity.

This document outlines clr.fund’s purpose, the properties it must have in order to fully achieve that purpose, and the principles guiding its development.

*Note: clr.fund is open-source software and may be forked by any community looking to allocate funds to public goods. This document pertains to the instance of clr.fund dedicated to public goods benefiting the Ethereum Ecosystem. Other instances may have different objectives or values, and this document does not represent them.*

## II. Key Definitions
### A. Public Goods <a name="public-goods"> </a>
Public goods are commodities or services that are neither [excludable](#Excludable) nor [subtractable](#Rival-/-Subtractable).

Fully non-excludable and non-subtractable goods are public goods. Additionally, because a good can be partially excludable or partially subtractable, goods that are relatively low on the excludability continuum and the subtractability continuum are also public goods.

### B. Ethereum Protocol <a name="ethereum-protocol"> </a>
The mainnet, canonical Ethereum software protocol that stores, executes changes in, and facilitates consensus on balances of Ether and information (“state”) within Ethereum smart contracts. It is the protocol on which this instance of clr.fund is deployed.

### C. Ethereum Ecosystem <a name="ethereum-ecosystem"> </a>
The individual people, organizations, software, and standards that create, operate, maintain, use, analyze, or convene around the Ethereum Protocol or anything built with the Ethereum Protocol. It is a strict superset of the Ethereum Protocol.

## III. Purpose and Scope
Clr.fund aims to be a primary protocol by which the [Ethereum Protocol](#ethereum-protocol) and [Ecosystem](#ethereum-ecosystem) allocate funds towards the development of [public goods](#public-goods) that benefit the Ethereum Ecosystem.
#### “Allocates funds”
Clr.fund is concerned with how existing funds are allocated towards public goods that benefit the Ethereum Ecosystem; it is agnostic to how those funds are raised in the first place. Those decisions are left to the Ethereum Ecosystem to determine.

To maximize the number of funding sources that can viably use clr.fund as their allocation protocol, clr.fund must have a particular set of [core properties](#core-properties).

#### “Development of public goods”
Clr.fund allocates funds solely towards the creation, improvement, and maintenance of public goods (as defined in Section II(A)), and excludes other types of goods that can be sold to generate revenue—such as [private](#Private-good) or [club goods](#Club-good).

#### “Benefit the Ethereum Ecosystem”
Only public goods that benefit the Ethereum Ecosystem qualify to receive funding via clr.fund. Public goods that do not benefit the Ethereum Ecosystem, even if they are built on or with the Ethereum Protocol, do not qualify.

## IV. Core Properties <a name="core-properties"> </a>
To become a primary fund allocation protocol for the Ethereum network, clr.fund must develop the following properties:

### A. Credibly neutral
In carrying out its purpose, the protocol must not discriminate for or against any specific people, and this property must be both reliable and reasonably demonstrable to both participants and external observers.

#### 1. Permissionless
Every member of the Ethereum Ecosystem who desires to participate in deciding where funds should be allocated should be able to do so.

#### 2. Trustless
The protocol should place as little trust in operators or other individuals as possible. The less the protocol relies on such actors, the more credible its neutrality will be.

#### 3. Decentralized
No central party or parties should have control over funds or be responsible for the allocation of funds. Power and control should be as widely distributed as possible so that the Ethereum Network cannot be captured or corrupted.

Fund allocation responsibility and decision-making should be as widely distributed as possible to capture as much information about the needs of the Ethereum network as possible.

### B. Attack-resistant
To remain credibly neutral within an open and adversarial environment, the clr.fund must be robust to multiple types of attacks and manipulation, including [collusion](#Collusion), [bribery](#Bribery), [blackmail](#Blackmail), [griefing](#Griefing), and [sybil attacks](#Sybil-attack).

#### 1. Collusion
Individual parties must not be able to coordinate such that they or their interests each receive more funding than they would receive if all parties were to act of their own accord.

#### 2. Bribery and blackmail
Individual parties must not be able to profitably pay off or otherwise induce other parties to take actions that increase the funding received by the inducing party over and above what the inducing party would receive if the induced party were to act of their own accord.

#### 3. Griefing
Individual parties must not be able to prevent other parties from taking actions within the clr.fund protocol or from such actions having their intended effect.

#### 4. Sybil-resistant
The protocol must be able to attribute all of the actions taken by a given individual to said individual.

## V. Glossary
##### Excludable
A good is considered excludable if it is possible to prevent non-paying people from using it, and non-excludable if it is not possible to do so. Goods exist on a continuum from fully excludable to fully non-excludable.

##### Rival / Subtractable
A good is considered rival (or subtractable) if its consumption or use by one party reduces (subtracts from) the ability of another party to do so, and non-rival (non-subtractable) if it can be provided to an additional party without cost. Goods exist on a continuum from fully rival to fully non-rival.

##### Private good
A good that is both excludable and rival.

##### Club good
A good that is excludable but non-rival.

##### Bribery
The offering, giving, receiving, or soliciting of any item of value to influence the actions of a participant in a system.

##### Blackmail
The demand of specific action by a participant in a system in return for not revealing compromising or damaging information about that participant or its interests.

##### Collusion
Cooperation, coordination, or agreement between two or more participants that subverts the intended behavior of a system to gain a disproportionately large influence for or payout to the cooperating participants.

##### Griefing
Imposing a cost on a single participant in a system, a group of participants, or on the system as a whole, even if doing so is unprofitable within the context of the system. Such behavior may be conducted for mere schadenfreude or in order to accrue rewards outside of the system.

##### Sybil attack
When a participant subverts the reputation system of a network by creating additional pseudonymous identities and uses them to gain a disproportionately large influence or payout.
