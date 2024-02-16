# Paseo Github organization
Welcome to the Paseo testnet!
Paseo is the newest testnet on Polkadot, replacing Rococo as a decentralised, community run, stable testnet for Parachain teams and dapp developers to build on. The below guide will show you how to interact with the testnet as a developer, infrastructure provider and as an end user. 

## Basic info
The network has been (pending a successful treasury proposal) funded by the Polkadot Treasury for operation and maintance during 2024.
The 2024 proposal link is here: https://polkadot.polkassembly.io/referenda/464#e5af1f3c-8e7d-4f1f-b6a0-d1dab9f05c23
Paseo is for Parachains and dapp builders to build and test their applications ontop of a stable testnet.
The other testnet we have is Westend, which is for Parachains to perform protocol testing. Westend will be the environment to test new changes to the Polkadot relaychain and system chains, e.g. Coretime, Beefy, and Asycbacking.

## Ongoing work to the network
There is always ongoing work being made to the testnet - we have made this transparent and public to the community by logging all work as a github issue. The workboard can be found here
https://github.com/orgs/paseo-network/projects/1/views/3

## Large changes to the network
Changes to the network are covered by raising a PAS (Paseo Action Submission). Similar to EIPs these are to document changes to how the network will progress.
Anyone is able to raise a PAS for review by the maintainers of the network. 
The raised PASs can be found at https://github.com/paseo-network/paseo-action-submission

## $PAS the testnet token
All actions made on the relay chain, will need to be made in $PAS 

## Getting the testnet token ($PAS)
1. Faucet -> https://paritytech.github.io/polkadot-testnet-faucet/
2. Guide on how to interact with the faucet -> https://medium.com/p/8c2fbe45b603

## Adding your tokens to the faucet
Are you a team deploying on Paseo that wants to make their tokens availabe on the fuacet for builders? (TODO)

## Want to become a validator on Paseo?
Please read -> https://github.com/paseo-network/paseo-action-submission/blob/main/pas/onboard_infrastructure_providers.md

Q. Why can’t we just keep maintaining Rococo with decentralised funding?
A. There are several reasons why we believe Rococo is no longer fit for purpose for the best experience of a testnet. 
Rococo being a POA chain, is built differently from Polkadot (nPOS) meaning there are differences in how the chain is structured. 
As Rococo is several years old, the time it takes a developer to sync the chain to start building is over 24h, for a developer they want to get started asap, and having a fast syncing chain is incredibly important. This is one of the reasons why ETH testnets are cycled through every 2-3 years. 
Building on Rococo is currently permissioned and handled by Parity with strict limitations, also, the team that are managing this are leaving Parity to start their own company, this service will no longer be managed.
Rococo receives updates prior to Kusama, meaning we don’t currently have an environment which is close to production for teams to build and test on.
We believe this opportunity has given us time to take stock of our testnet offering and make a change for the better for 2024.



## Q&A about the network:
Q. Do I need an existing parachain on Rococo, Kusama or Polkadot to receive a slot on Paseo?
No, access to a slot on Paseo will be permissionless with the launch of Coretime and until then, any team is able to leverage the development environment to start tinkering and coding their project. 

Q. Will all existing parachains and projects running on Rococo need to migrate to Paseo?
A. Yes, Rococo will be decommissioned early 2024 (more details to follow), teams will need to launch on Paseo with no chain state (preferred) or, migrate their Rococo chainstate to Paseo to continue operation of their testnet environment.

Q. What is the migration path from Rococo to Paseo?
A. A full migration path guide will be published in the future.

Q. When will coretime launch on Paseo? 
A. Coretime on Paseo will launch just before Polkadot. If you are wanting to test or build applications for Coretime before it ships on Polkadot, we suggest testing this on Westend.

Q. I want to test new Polkadot features that aren’t yet on Polkadot, can I do this on Paseo?
A. No, you should test new bleeding edge features on Westend.

Q. Who is managing Paseo and what experience do they have running a testnet?
Two core contributors to the Paseo testnet, the teams Portico and ROGUE are ex-Parity with two years of experience running Rococo, so they are very experienced. They are also joined by Zondax who have substantial web3 experience and are building on their substrate expertise and will be assisting in managing Paseo. 

Q. Are there any SLAs for incident management?
Yes, this is something we are currently working out and we will propose it as an RFC in the Paseo github.

Q. Will it be possible to access the logs from the Relay and System chains?
Yes, all logging will be made publicly available to help with development and troubleshooting efforts.
