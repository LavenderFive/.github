
<p align="center">
  <img src="https://user-images.githubusercontent.com/9121234/189499808-fa2b744f-fa1f-459a-8866-0625c619e1e0.png" />
</p>


## Who Are We
[Lavender.Fives Nodes](https://www.lavenderfive.com/) is one of the most trusted Proof of Stake validators. 
Our team is able to maintain near-100% uptime through a variety of resources including dedicated servers around the world, 
multiple 24/7 alerting systems in place, and always-ready backup servers. We are proud to say we serve as validators on more than 30 mainnets, and are trusted by over **20000** delegators. 

We differentiate ourselves through our community engagement and contributions to the projects we serve. 
This is achieved by authoring documentation for fellow validators, writing and promoting new governance proposals, 
and helping squash code bugs before they become an issue.

## A Showing of Networks
A small selection of the networks we support include:
- Secret Network
- Cosmos Hub 
- Osmosis
- Evmos
- Juno
- NEAR
- [and many more!](https://www.lavenderfive.com/)

## Our Infrastructure

We take a pragmatic approach to running validators. At the most basic level we utilize bare metal servers
with a minimum of 2 full nodes per network. Each server is with a different providers, across Hetzner, OVHCloud, or MEVSpace.
In addition, we utilize [Horcrux](https://github.com/strangelove-ventures/horcrux) as our remote signing solution, with 3 signers. 
What this means in practice is *ALL* nodes have to go down, or 2 signers, before we begin to miss blocks.

In addition to this, we utilize the following as our monitoring solutions:
- [Zabbix](https://www.zabbix.com/)
- [Prometheus](https://prometheus.io/)
- [Tenderduty](https://github.com/blockpane/tenderduty)

## Our Contributions

We also contribute greatly to each ecosystem we're in. As a few off the cuff examples:
- Open source tooling for validators/node runners:
  - Ansible playbooks for Horcrux: https://github.com/LavenderFive/horcrux-ansible
  - Ansible playbooks for running nodes: https://github.com/LavenderFive/cosmos-validators-ansible
  - Ansible playbooks for secure server setup: https://github.com/LavenderFive/secure-server-setup-ansible
  - Slashing refund: https://github.com/LavenderFive/slash_refunds_tendermint
- **Relaying**: we are one of the most prolific relayers in the ecosystem, and have helped many relayers get their start (see the docs below).
- We wrote the Gentx documentation for [Kujira](https://github.com/Team-Kujira/networks/pull/5)
- We've either written or edited every document for [Secret Network](https://docs.scrt.network/)
- We write documentation to help other node runners:
  - [Relaying](https://docs.scrt.network/relayers/setting-up-hermes.html)
  - [Setting up TMKMS](https://gist.github.com/dylanschultzie/c7c4eed531df0f004a50c5395e1604b3)
  - [Horcrux](https://gist.github.com/dylanschultzie/0a0b10cf695749f9697197759e7b12ec)
  - [Raising the Security Floor of the Cosmos/](https://medium.com/@lavenderfive/raising-the-security-floor-of-the-cosmos-2467f5e71966)
- We commonly create proposals for networks:
  - [Osmosis](https://commonwealth.im/osmosis/proposal/discussion/2487-proposal-discussion-signaling-proposal-for-scrt-incentivized-pools)
  - [Secret](https://secretnodes.com/secret/chains/secret-4/governance/proposals/93)
