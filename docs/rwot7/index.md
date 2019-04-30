# Rebooting the Web of Trust VII: Toronto (September 2018)

This repository contains documents related to RWOT7, the seventh Rebooting the Web of Trust design workshop, which ran near Toronto, Canada, on September 26th to 28th, 2018. The goal of the workshop was to generate five technical white papers and/or proposals on topics decided by the group that would have the greatest impact on the future.

_Please see the [Web of Trust Info website](http://www.weboftrust.info/) for more information about our community. Watch for our [next event](https://www.weboftrust.info/next-event-page.html) March 1st-3rd in Barcelona, Spain._

## Final Papers


## [*BTCR v0.1 Decisions*](final-documents/btcr_0_1.pdf) [(Text)](final-documents/btcr_0_1)
#### Kim Hamilton Duffy, Christopher Allen, and Dan Pape

> The Bitcoin Reference (BTCR) DID method supports DIDs using the Bitcoin blockchain. This method has been under development through Rebooting Web of Trust events and hackathons over the past year. The BTCR method's reliance on the Bitcoin blockchain presents both advantages and design challenges. During RWOT7, the authors made a number of design and implementation decisions -- largely scope-cutting in nature -- in order to lock down a Minimum Viable Product (MVP) version, which we'll refer to as v0.1. This paper documents those decisions, which will apply to the upcoming v0.1 BTCR method specification and associated v0.1 BTCR reference implementation.

## [*A DID for Everything*](final-documents/A_DID_for_everything.pdf) [(Text)](final-documents/A_DID_for_everything)
#### Shaun Conway, Andrew Hughes, Moses Ma, Jack Poole, Martin Riedel, Samuel M. Smith Ph.D., and Carsten Stöcker

> The decentralized identifier (DID) is a new and open standard type of globally unique identifier that offers a model for lifetime-scope portable digital identity that does not depend on any centralized authority and that can never be taken away by third-parties. DIDs are supported by the W3C community and the Decentralized Identity Foundation (DIF). They are the "atomic units" of a new layer of decentralized identity infrastructure. However, DIDs can be extended from identifiers for people to any entity, thus identifying everything. We can use DIDs to help us identify and manage objects, machines, or agents through their digital twins; we can expand them to locations, to events, and even to pure data objects, which we refer to as decentralized autonomic data (DAD) items.

> The paper will present novel use-cases for DIDs and DADs and propose a new cryptographic data structure that is a self-contained blockchain of DADs. This enables the verification of the provenance of a given data flow. It builds on a prior paper and an associated reading.

## [*How to Convince Dad\* of the Importance of Self-Sovereign Identity*](final-documents/convincing-dad.pdf) [(Text)](final-documents/convincing-dad)
#### Shannon Appelcline, Kenneth Bok, Lucas Parker, Peter Scott, and Matthew Wong

> One of the major problems with bootstrapping self-sovereign identity is that it requires adoption by a large number of people. Pushing self-sovereign identity from the top-down is most likely to result in a technology that’s not actually used, but instead encouraging the average person to demand self-sovereign identity from the bottom-up will result in the organic development of a vibrant, well-utilized decentralized web-of-trust ecosystem.

> This paper addresses that need by offering arguments to a variety of people who might be reluctant to use self-sovereign identity, uninterested in its possibilities, or oblivious to the dangers of centralization. By focusing on the needs of real people, we hope to also encourage developers, engineers, and software business owners to create the apps that will address their reluctance and fulfill their needs, making self-sovereign identity a reality.

## [*IPLD as a general pattern for DID documents and Verifiable Claims*](final-documents/ipld-did.pdf) [(Text)](final-documents/ipld-did)
#### jonnycrunch, Anthony Ronning, Kim Duffy, Christian Lundkvist

> Since the emergence of the Decentralized Identifier (DID) specification at the Fall 2016 Rebooting the Web of Trust [1], numerous DID method specifications have appeared. Each DID method specification defines how to resolve a cryptographically-tied DID document given a method-specific identifier. In this paper, we describe a way to represent the DID document as a content-addressed Merkle Directed Acyclic Graph (DAG) using Interplanetary Linked Data (IPLD). This technique enables more cost-efficient, scaleable creation of DIDs and can be applied across different DID method specifications.

## [*Peer to Peer Degrees of Trust*](final-documents/peer-to-peer-degrees-of-trust.pdf) [(Text)](final-documents/peer-to-peer-degrees-of-trust)
#### Harrison Stahl, Titus Capilnean, Peter Snyder, and Tyler Yasaka

> Aunthenticity is a challenge for any identity solution. In the physical world, at least in America, it is not difficult to change one's identity. In the digital world, there is the problem of bots. The botnet detection market is expected to be worth over one billion USD by 2023, in a landscape where most digital activity is still heavily centralized. These centralized digital solutions have the advantage of being able to track IP addresses, request phone verification, and present CAPTCHAs to users in order to authenticate them. If this problem is so difficult to solve in the centralized world, how much more challenging will it be in the decentralized world, where none of these techniques are available?

> In this paper, we explore the idea of using a web of trust as a tool to add authenticity to decentralized identifiers (DIDs). We define a framework for deriving relative trust degrees using a given trust metric: a "trustworthiness" score for a given identity from the perspective of another identity. It is our intent that this framework may be used as a starting point for an ongoing exploration of graph-based, decentralized trust. We believe this approach may ultimately be used as a foundation for decentralized reputation.

## [*Resource Integrity Proofs*](final-documents/resource-integrity-proofs.pdf) [(Text)](final-documents/resource-integrity-proofs)
#### Ganesh Annan and Kim Hamilton Duffy

> Currently, the Web provides a simple yet powerful mechanism for the dissemination of information via links. Unfortunately, there is no generalized mechanism that enables verifying that a fetched resource has been delivered without unexpected manipulation. Would it be possible to create an extensible and multipurpose cryptographic link that provides discoverability, integrity, and scheme agility?

> This paper proposes a linking solution that decouples integrity information from link and resource syntaxes, enabling verification of any representation of a resource from any type of link. We call this approach Resource Integrity Proofs (RIPs). RIPs provide a succinct way to link to resources with cryptographically verifiable content integrity. RIPs can be combined with blockchain technology to create discoverable proofs of existence to off-chain resources.

## [*Use Cases and Proposed Solutions for Verifiable Offline Credentials*](final-documents/offline-use-cases.pdf) [(Text)](final-documents/offline-use-cases)
#### Michael Lodder, Samantha Mathews Chase, and Wolf McNally

> In this paper we cover various scenarios where some or all parties have intermittent, unreliable, untrusted, insecure, or no network access, but require cryptographic verification (message protection and/or proofs). Furthermore, communications between the parties may be only via legacy voice channels. Applicable situations include marine, subterranean, remote expeditions, disaster areas, refugee camps, and high-security installations. This paper then recommends solutions for addressing offline deployments.

##  Topics & Advance Readings

In advance of the design workshop, all participants produced a one-or-two page topic paper to be shared with the other attendees on either:

* A specific problem that they wanted to solve with a web-of-trust solution, and why current solutions (PGP or CA-based PKI) can't address the problem?
* A specific solution related to the web-of-trust that you'd like others to use or contribute to?

Here are the advanced readings to date:

* [Addressing Global/Local Barriers to Adoption of Decentralized Identity Systems](topics-and-advance-readings/Adoption) by Eric Brown
* [Agent to Agent Communication Protocol Overview](topics-and-advance-readings/a2a-comm-protocol-overview) by Kyle Den Hartog
* [Blockcerts -- Where we are and what's next](topics-and-advance-readings/blockcerts_roadmap) by Kim Hamilton Duffy, Anthony Ronning, Lucas Parker, and Peter Scott
* [Can Curation Markets Establish a Sustainable Technology Commons](topics-and-advance-readings/CanCurationMarketsEstablishSustainableTechnologyCommons.pdf) by Sam Chase
* [CapAuth](topics-and-advance-readings/capauth) by Manu Sporny, Dave Longley, Chris Webber, and Ganesh Annan
* [A Concept Diagram For RWOT Identity Terms](topics-and-advance-readings/towards-a-terminology-concept-map) by Andrew Hughes
* [Cryptocurrency Wallets as a Form of Functional Identity](topics-and-advance-readings/Cryptocurrency%20wallets%20a%20an%20application%20of%20Functional%20Identity) by Mikerah Quintyne-Collins and Abdulwasay Mehar
* [Decentralized Error Reporting](topics-and-advance-readings/decentralized-error-reporting) by Jack Poole
* [Decentralized Identities and eIDAS](topics-and-advance-readings/leveraging-eidas-for-did) by Oliver Terbu
* [Decentralized Identity: Hub Authentication & Message Encryption](topics-and-advance-readings/did-auth-jwe) by Daniel Buchner
* [DIDDoc Conventions for Interoperability](topics-and-advance-readings/diddoc-conventions-for-interoperability) by Stephen Curran & Olena Mitovska
* [DIDs In DPKI](topics-and-advance-readings/dids-in-dpki) by Greg Slepak
* [DID Resolution Topics](topics-and-advance-readings/did-resolution-topics) by Markus Sabadello
* [Digital Identity for the Homeless](topics-and-advance-readings/Digital-Identity-for-the-Homeless) by Matthew Wong, T. Tian & CG Chen
* [Exploring Browser Web of Trust Use Cases](topics-and-advance-readings/exploring-browser-wot-use) by Peter Snyder and Ben Livshits
* [Five Mental Models of Identity](topics-and-advance-readings/five-mental-models-of-identity) by Joe Andrieu
* [Identity Hub Permissions / Authorization](topics-and-advance-readings/identity-hub-permissions) by Daniel Buchner
* [IPLD as a general pattern for DID Documents](topics-and-advance-readings/ipld_did_documents) by Christian Lundkvist
* [Is a Decentralized Collective Identity Possible?](topics-and-advance-readings/Decentralized-Collective-Identity) by Heather Vescent
* [Magenc Magnet URIs: Secure Object Permanence for the Web](topics-and-advance-readings/magenc) by Christopher Lemmer Webber
* [Measuring Trust](topics-and-advance-readings/measuring-trust) by Tyler Yasaka
* [More Control for Identity Holders](topics-and-advance-readings/more-control-for-identity-holders) by Arturo Manzaneda and Ismenia Galvao
* [Nobody REALLY Trusts the Blockchain](topics-and-advance-readings/Nobody_REALLY_Trusts_the_Blockchain) by Dan Burnett, Shahan Khatchadourian, and Chaals Nevile
* [Not-a-Bot: A Use Case for Decentralized Identity using Proximity Verification to generate a Web of Trust](topics-and-advance-readings/not-a-bot) by Moses Ma & Claire Rumore
* [The Political Economy of Naming](topics-and-advance-readings/political-economy-of-naming) by Kate Sills
* [A Public Web of Trust of Public Identities](topics-and-advance-readings/a-public-web-of-trust-of-public-identities) by Ouri Poupko and Ehud Shapiro
* [Resource Integrity Proofs](topics-and-advance-readings/resource-integrity-proofs) by Ganesh Annan, Manu Sporny, Dave Longley, and David Lehn
* [RWoT Tribal Knowledge: Cryptographic and Data Model Requirements](topics-and-advance-readings/crypto-data-model-requirements) by Manu Sporny, Dave Longley, and Chris Webber
* [The Role of Standards in Accelerating Innovation](topics-and-advance-readings/The_Role_of_Standards_in_Accelerating_Innovation) by Michael B. Jones
* [Scoped Presentation Request on Verifiable Credentials](topics-and-advance-readings/presentation-request/presentation-request) by Martin Riedel
* [Secure Crypto-Wallet Introductions](topics-and-advance-readings/Secure%20Crypto-Wallet%20Introductions) by Wolf McNally, Ryan Grant
* [Standards for Agency and Decentralized Information Governance - Early Experience](topics-and-advance-readings/standards-for-governance) by Adrian Gropper, MD, Michael Chen, MD, and Lydia Fazzio, MD
* [Towards Proof of Person](topics-and-advance-readings/towards-proof-of-person) by Peter Watts
* [A Trustless Web-of-Trust](topics-and-advance-readings/trustless-web-of-trust) by Ouri Poupko
* [The United Humans](topics-and-advance-readings/united-humans) by Bohdan Andriyiv
* [Verifiable Displays](topics-and-advance-readings/verifiable_displays) by Kim Hamilton Duffy, Bohdan Andriyiv, and Lucas Parker
* [Verifiable Offline Credentials](topics-and-advance-readings/verifiable-offline-credentials) by Michael Lodder
* [What (and Who) Is In Your Wallet](topics-and-advance-readings/what-and-who-is-in-your-wallet) by Darrell O'Donnell
* [Digital Identity for the Homeless](topics-and-advance-readings/Digital-Identity-for-the-Homeless) by Matthew Wong, T. Tian & CG Chen
* [Zero Trust Computing with DIDs and DADs](topics-and-advance-readings/ZeroTrustComputingWithDidsAndDads) by Samuel M. Smith

### Primers
These primers overview major topics which are likely to be discussed
at the design workshop. If you read nothing else, read these. (But
really, read as much as you can!)

* [DID Primer](topics-and-advance-readings/did-primer) — Decentralized Identifiers ([extended version](topics-and-advance-readings/did-primer-extended) also available)
* [Functional Identity Primer](topics-and-advance-readings/functional-identity-primer) — A different way to look at identity
* [Verifiable Credentials Primer](topics-and-advance-readings/verifiable-credentials-primer) — the project formerly known as Verifiable Claims
* [DIDs In DPKI](topics-and-advance-readings/dids-in-dpki) - how DIDs fit into Decentralized Public-key Infrastructure

## Complete Rebooting the Web of Trust Listing

A different repository is available for each of the Rebooting the Web of Trust design workshops:

* [Rebooting the Web of Trust I: San Francisco (November 2015)](../rwot1-sf)
* [Rebooting the Web of Trust II: ID2020 (May 2016)](../rwot2-id2020)
* [Rebooting the Web of Trust III: San Francisco (October 2016)](../rwot3-sf)
* [Rebooting the Web of Trust IV: Paris (April 2017)](../rwot4-paris)
* [Rebooting the Web of Trust V: Boston (October 2017)](../rwot5-boston)
* [Rebooting the Web of Trust VI: Santa Barbara (March 2018)](../rwot6)
* [Rebooting the Web of Trust VII: Toronto (September 2018)](../rwot7)
* [Rebooting the Web of Trust VIII: Barcelona](../rwot8)

## License

All of the contents of this directory are licensed [Creative Commons CC-BY](../rwot1-sf/final-documents/LICENSE-CC-BY-4.0) their contributors.
