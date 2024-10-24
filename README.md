<p align="center">
  <img src="../resources/logo_header.svg" />
</p>


## Welcome to the Paseo testnet!
Paseo is the newest testnet on Polkadot, replacing Rococo as a decentralised, community run, stable testnet for Parachain teams and dapp developers to build on. The below guide will show you how to interact with the testnet as a developer, infrastructure provider and as an end user.

### Basic info
The network supported by the Polkadot DAO:
The 2024 proposal link is here:
- https://polkadot.polkassembly.io/referenda/464#e5af1f3c-8e7d-4f1f-b6a0-d1dab9f05c23

Paseo is for Parachains and dapp builders to build and test their applications ontop of a stable testnet.
The other testnet we have is Westend, which is for Parachains to perform protocol testing. Westend will be the environment to test new changes to the Polkadot relaychain and system chains, e.g. Coretime, Beefy, and Asycbacking.

## Ongoing work to the network
There is always ongoing work being made to the testnet - we have made this transparent and public to the community by logging all work as a github issue. The workboard can be found here:

- https://github.com/orgs/paseo-network/projects/1/views/3

## Impactful changes to the network and its operation
Changes to the network are covered by raising a PAS (Paseo Action Submission). Similar to EIPs these are to document changes to how the network will progress.
Anyone is able to raise a PAS for review by the maintainers of the network.
The raised PASs can be found at:

- https://github.com/paseo-network/paseo-action-submission

## $PAS the testnet token
All actions made on the relay chain, will need to be made in $PAS

## Getting the testnet token ($PAS)
1. Faucet -> https://faucet.polkadot.io/
2. Guide on how to interact with the faucet -> https://medium.com/p/8c2fbe45b603

## Adding your tokens to the faucet
Are you a team deploying on Paseo that wants to make their tokens availabe on the fuacet for builders? (TODO)

## Want to connect a chain to Paseo?
Please read -> [PAS-10: Onboard chains via coretime](https://github.com/paseo-network/paseo-action-submission/blob/main/pas/PAS-10-Onboard-paras-coretime.md).
Or open an issue at: https://github.com/paseo-network/support

## Want to become a validator on Paseo?
Provider onboardings are frozen at the moment.

Please read -> [PAS-1: Onboard infrastructure providers](https://github.com/paseo-network/paseo-action-submission/blob/main/pas/PAS_ID1_onboard_infrastructure_providers.md).

## Q&A about the network:

**Q**. Why can’t we just keep maintaining Rococo with decentralised funding?

Rococo was shut down the 14th of October of 2024. Being the last block of the network [#12625076](https://gist.github.com/KarimJedda/697b22713a2fb72b748fa0daa67deaa8), which hides a secret. Farewell, Dear Rococo.

~~There are several reasons why we believe Rococo is no longer fit for purpose for the best experience of a testnet.
Rococo being a POA chain, is built differently from Polkadot (nPOS) meaning there are differences in how the chain is structured.
As Rococo is several years old, the time it takes a developer to sync the chain to start building is over 24h, for a developer they want to get started asap, and having a fast syncing chain is incredibly important. This is one of the reasons why ETH testnets are cycled through every 2-3 years.
Building on Rococo is currently permissioned and handled by Parity with strict limitations, also, the team that are managing this are leaving Parity to start their own company, this service will no longer be managed.
Rococo receives updates prior to Kusama, meaning we don’t currently have an environment which is close to production for teams to build and test on.
We believe this opportunity has given us time to take stock of our testnet offering and make a change for the better for 2024.~~

**Q**. Do I need an existing parachain Kusama or Polkadot to receive a slot on Paseo?

> No, access to a slot on Paseo will be as permissionless as possible thanks to [Agile Coretime](https://wiki.polkadot.network/docs/learn-guides-coretime-parachains).

**Q**. Will all existing parachains and projects running on Rococo need to migrate to Paseo?
> Yes, Rococo will be decommissioned early 2024 (more details to follow), teams will need to launch on Paseo with no chain state (preferred) or, migrate their Rococo chainstate to Paseo to continue operation of their testnet environment.

**Q**. What is the migration path from another relay to Paseo?
> Please read: https://github.com/paseo-network/support/blob/main/docs/rococo_migration.md

**Q**. When will coretime launch on Paseo?
> Coretime on Paseo was launched with runtime upgrade [v1.3.1](https://github.com/paseo-network/runtimes/releases/tag/v1.3.1)

**Q**. I want to test new Polkadot features that aren’t yet on Polkadot, can I do this on Paseo?
> No, you should test new bleeding edge features on Westend.

**Q**. Who is managing Paseo?
> Paseo is a joint effort between Portico, R0GUE, Zondax and number of infrastructure providers from Polkadot ecosystem.

**Q**. Are there any SLAs for incident management?
> Yes, this is something we are currently working out and we will propose it as an RFC in the Paseo github.

**Q**. Will it be possible to access the logs from the Relay and System chains?
> Yes, all logging will be made publicly available to help with development and troubleshooting efforts. (TODO)

## Paseo Announcements

Please join this public Matrix channel in order to get the latest updates about Paseo network:

https://matrix.to/#/#paseo-announcements:matrix.org

## Paseo Support

Please join this public Matrix channel in order to reach out to the team and other involved players of the Paseo network:

https://matrix.to/#/#paseo-testnet-support:parity.io

## Paseo chain specs

The chain-specs for the Paseo Relay and its system chains can be found in the following repository:

https://github.com/paseo-network/paseo-chain-specs
