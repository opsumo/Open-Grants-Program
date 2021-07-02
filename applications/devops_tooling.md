# W3F Open Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Open Grants Program Process](https://github.com/w3f/Open-Grants-Program/#pencil-process) on how to submit a proposal.

* **Project Name:** DevOps Tooling for Polkadot and Substrate Networks
* **Team Name:** Jackson Peak LLC aka OPSUMO.co
* **Payment Address:** BTC or Ethereum (USDT/DAI) payment address. We don't accept payments for the program in other currencies at this stage. If this is an Ethereum address, please specify USDT or DAI. (e.g. 0x8920... (DAI))


> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

Having been recognized as a runner-up in the India Buildathon 2021, our [project](https://github.com/opsumo/polkadot-cn-devops-priv) has proven that it could be useful Polkadot and Substrate projects and that, it has more room for further innovations.

We intend to continue innovating it.

### Overview

Please provide the following:

* Provision and Deploy a Polkadot/Substrate Network or Component(s) or Custom Blockchain Project in a Cloud-Native Testnet.
* We recognize that for a would be layer-1 or 2 app development like Parachains, Parathread, Bridge, Validator, Collator, Smart Contracts, NFT, DeFi, etc starting from scratch is hard. So what if, there exist pre-baked set of initial Infra as Code provisioner, Cluster, Network and Security setup that a would-be team could leverage and use to scaffold their own use-cases as a foundational building block? Imagine the win-win benefit it could give for the Polkadot Network community. Speed of development could ascertain greater velocities, and with it, a more lively and active community. For the project teams planning on using it, again, the value is speed to market. 
* We will setup project teams that focuses on the streams such [P1](https://github.com/opsumo/polkadot-cn-devops-priv/blob/main/deploy-chain-1/README.md), [P2](https://github.com/opsumo/polkadot-cn-devops-priv/blob/main/deploy-chain-2/README.md), [P3](https://github.com/opsumo/polkadot-cn-devops-priv/blob/main/deploy-chain-3/README.md), etc. We will provide pathways to use our tools specific to Polkadot Blockchain Network, and custom Substrate Blockchain.
* One of our main business focus is IoT in the field of RFID and Bluetooth (Low Energy). A key intent in doing this endeavour is to correlate this project as a probable platform for future IoT projects.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

* Mockups/designs of any UI components
* Data models / API specifications of the core functionality
* Architecture: CNCF certified components, platforms, tools and cloud infrastructure.
* Documentation of core components, protocols, architecture, etc. to be deployed
* PoC/MVP or other relevant prior work or research on the topic - [Our entry to the buildathn India 2021 is our PoC](https://github.com/opsumo/polkadot-cn-devops-priv)
* What your project is _not_ or will _not_ provide or implement
  * This is a place for you to manage expectations and to clarify any limitations that might not be obvious
    - 

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

* Where and how does your project fit into the ecosystem? 
  + We will provide a service to host initial skeletal workspace with ready CICD automation further host DEV, TEST networks for Polkadot network, its components such as parachains, validators, collators and various customization streams for Substrate Blockchain designed for dApps, deFi, Smart Contracts, etc
* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
  + Our consumers will be potentially Paritech, developers, designers, other dapps developer houses and even us ourselves.
* What need(s) does your project meet?
  + The need for speed to market and standardization of deployment flows. 
  + Cost savings from a pay as you go service for hosting, managed-service, or consultancy
* Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  * We believe that there exist nothing like us in the current ecosystem.
  * The likelihood of similar work from other ecosystems is zero to maybe very low probability.

## Team :busts_in_silhouette:

### Team members

* Name of team leader: Mike Stankavich
* Names of team members : 
  1. Bobby Corpus 
  2. Edison Macabebe

### Contact

* **Contact Name:** Mike Stankavich
* **Contact Email:** mike@kwyk.net
* **Website:** [www.opsumo.co](https://www.opsumo.co)

### Legal Structure

* **Registered Address:** 2001 MIMOSA DR, Austin, Texas, United States
* **Registered Legal Entity:** JacksonPeak LLC

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

### Team Code Repos

* https://github.com/opsumo
* https://github.com/opsumo/keypr
* https://github.com/opsumo/polkadot-cn-devops-priv

GitHub accounts of all team members. 

* https://github.com/mikestankavich
* https://github.com/edmacabebe
* https://github.com/corpbob

### Team LinkedIn Profiles (if available)

* https://www.linkedin.com/in/mikestankavich/
* https://www.linkedin.com/in/edison-macabebe-31709b35/
* https://www.linkedin.com/in/bobbycorpus/

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

* links to improvement proposals or [RFPs](https://github.com/w3f/General-Grants-Program/tree/master/rfp-proposal) (requests for proposal),
* academic publications relevant to the problem,
* links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
* references to conversations you might have had related to this project with anyone from the Web3 Foundation,
* previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that the scope of the work can fit within a three-month period and that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

* make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we have created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* include the amount of funding requested _per milestone_.
* include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
* provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
* commit to providing Dockerfiles for the delivery of your project.
* indicate milestone duration as well as number of full-time employees working on each milestone.
* **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
* **Total Costs:** Amount of payment in USD for the whole project. The total amount of funding _needs to be below $30k for initial grants_ and $100k for follow-up grants. (e.g. 12,000 USD). This and the costs for each milestone need to be in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Implement Substrate Modules

* **Estimated duration:** 1 month
* **FTE:**  2
* **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  


### Milestone 2 Example — Additional features

* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 4,000 USD

...


## Future Plans

Please include here

* how you intend to use, enhance, promote and support your project in the short term, and
* the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

* Work you have already done.
* Wheter there are any other teams who have already contributed (financially) to the project.
* Previous grants you may have applied for.
