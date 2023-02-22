
<p align="center">
  <img src="https://user-images.githubusercontent.com/9121234/190864636-b5047a5b-8f44-42ed-a9de-62095bebd2a3.jpg" />
</p>

## Who Are We
[Lavender.Fives Nodes](https://www.lavenderfive.com/) is a company of 3 dedicated to bringing secure infrastructure and pragmatic software solutions to over 30 proof-of-stake blockchains. With 15+ years in software development and system administration experience we guarantee safety for the funds of over **45.000 delegators**. This makes us one of the most trusted Proof of Stake validators, and for good reason!

Our team is able to maintain industry-leading uptime by using dedicated servers around the world, 
multiple 24/7 alerting systems in place, and a remote signing solution with always-ready backups. We are proud to say we serve as validators on more than 30 mainnets processing Millions of transactions every month! 

We differentiate ourselves through our public infrastructure like API nodes and IBC relaying while dedicating ourselves to honest governance and community engagement. We serve the projects we validate by authoring documentation for fellow validators, improving infrastructure security by providing automated setups, developing out new features like hardware wallet support, and helping squash code bugs before they become an issue.

## Our Infrastructure

We take a pragmatic approach to running validators. At the most basic level we utilize bare metal servers with a minimum of 2 full nodes per network. 
Each server is with a different providers, Cherry, Ionos, Leaseweb, DigitalOcean, AWS, Hetzner, OVHCloud, or MEVspace, spread across multiple geographic locations.
In addition, we utilize [Horcrux](https://github.com/strangelove-ventures/horcrux) as our remote signing solution, with 3 signers. What this means in practice is *ALL* nodes have to go down, or 2 signers, before we miss a single block.

In addition to this, we utilize the following as our monitoring solutions:
- [Zabbix](https://www.zabbix.com/)
- [Prometheus](https://prometheus.io/)
- [Tenderduty](https://github.com/blockpane/tenderduty)

## Our Contributions

We also contribute greatly to each ecosystem we're in. 

As a few off the cuff examples:
- We provide **public RPC, API, and gRPC endpoints** for every network we have a presence on serving over 600M queries a month
- We maintain **state sync snapshots** for every network we validate
- We provide a public **seed node** for every network we validate
- **Relaying**: 
  - we are one of the most prolific relayers in the ecosystem, and have helped many relayers get their start (see the docs below)
  - We process over 25.000 IBC transactions a month across 20+ networks and 200+ channels. - [Data](https://relayers.smartstake.io/relayer/F87ADDB700C0CC94)
- **Open source tooling for validators/node runners**:
  - Core maintainer of the [Cosmos Chain Registry](https://github.com/cosmos/chain-registry) 
  - Ansible playbooks for [Horcrux](https://github.com/LavenderFive/horcrux-ansible)
  - Ansible playbooks for [running nodes](https://github.com/LavenderFive/cosmos-validators-ansible)
  - Ansible playbooks for [secure server setup](https://github.com/LavenderFive/secure-server-setup-ansible)
  - [Tendermint slashing refund script](https://github.com/LavenderFive/slash_refunds_tendermint)
- We have addded validator ledger support to the Injective protocol
- We wrote the Gentx documentation for [Kujira](https://github.com/Team-Kujira/networks/pull/5), Defund, Odin, Chihuahua, Dig, and more
- We've either written or edited every document for [Secret Network](https://docs.scrt.network/)
- We write documentation to help other node runners:
  - [Relaying](https://docs.scrt.network/relayers/setting-up-hermes.html)
  - [Setting up TMKMS](https://gist.github.com/dylanschultzie/c7c4eed531df0f004a50c5395e1604b3)
  - [Horcrux](https://gist.github.com/dylanschultzie/0a0b10cf695749f9697197759e7b12ec)
  - [Raising the Security Floor of the Cosmos](https://medium.com/@lavenderfive/raising-the-security-floor-of-the-cosmos-2467f5e71966)
- We commonly create proposals for networks:
  - [Osmosis](https://commonwealth.im/osmosis/proposal/discussion/2487-proposal-discussion-signaling-proposal-for-scrt-incentivized-pools)
  - [Secret](https://secretnodes.com/secret/chains/secret-4/governance/proposals/93)

## A Showing of Networks
A small selection of the networks we support include:
- Aptos
- Near
- Secret Network
- Cosmos Hub 
- Osmosis
- Evmos
- Juno
- Sommelier
- [and many more!](https://www.lavenderfive.com/)
