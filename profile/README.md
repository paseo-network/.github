<p align="center">
  <img src="../resources/logo_header.svg" />
</p>


## Welcome to the Paseo testnet!
Paseo is Polkadot's testnet.
It is decentralized, community run and stable! Paseo is for Parachain teams and dapp developers to build on. The below guide will show you how to interact with the testnet as a developer, infrastructure provider and as an end user.

### Basic info
The network is funded by the Polkadot Treasury for operation and maintance since 2024.
These are the treasury proposals that have helped maintain Paseo running:
- https://polkadot.polkassembly.io/referenda/464#e5af1f3c-8e7d-4f1f-b6a0-d1dab9f05c23
- https://polkadot.subsquare.io/referenda/1487

Paseo is for Parachains and dapp builders to build and test their applications ontop of a stable testnet.
Another testnet exists: Westend. Which hosts all protocol testing. While Westend can be less stable it is the environment to test new protocol changes while they are being prepared for quality control and later release.

## Block explorers:
- https://paseo.subscan.io/
- https://paseo.statescan.io/
- EVM contracts: https://blockscout-passet-hub.parity-testnet.parity.io/

## Governance:
Users are welcome to test governance related features. However, most priviledged operations are executed via a priviledged key controlled by the maintainers of the testnet.

- https://paseo.subsquare.io/
- https://paseo.polkassembly.io/

## Ongoing work to the network
There is always ongoing work being made to the testnet. The work is kept in public repositories, namely:

- https://github.com/paseo-network/paseo-active-submissions
- https://github.com/paseo-network/paseo-chain-specs
- https://github.com/paseo-network/passet-hub
- https://github.com/paseo-network/runtimes
- https://github.com/paseo-network/support

## Large changes to the network
Changes to the network are covered by raising a PAS (Paseo Action Submission). Similar to EIPs these are to document changes to how the network will progress.
Anyone is able to raise a PAS for review by the maintainers of the network.
The raised PASs can be found at:

- https://github.com/paseo-network/paseo-action-submission

## $PAS the testnet token
All actions made on the relay chain, will need to be made in $PAS

## Getting the testnet token ($PAS)
1. Faucet -> https://paritytech.github.io/polkadot-testnet-faucet/
2. Guide on how to interact with the faucet -> https://medium.com/p/8c2fbe45b603

## Adding your tokens to the faucet
Are you a team deploying on Paseo that wants to make their tokens availabe on the fuacet for builders? Please reach out by opening a support issue at:

- https://github.com/paseo-network/support

## Want to become a validator on Paseo?
Please read -> https://github.com/paseo-network/paseo-action-submission/blob/main/pas/PAS-1-onboard_infrastructure_providers.md


## Q&A about the network:

**Q**. How do I obtain coretime in Paseo ?
> One can obtain coretime in Paseo by participating on coretime sales, just like in production. After getting some tokens from the faucet one can easily participate in sales via: https://app.regionx.tech/?network=paseo

**Q**. I want to test new Polkadot features that aren’t yet on Polkadot, can I do this on Paseo?
> Only after they have been included in a runtime release by the polkadot fellowship. One of they key ways to keep Paseo stable is by only deploying code that has been deemed of certian quality by the Polkadot fellows.

**Q**. Who is managing Paseo ?
> The maintainers of the testnet is a distributed group of contributors taking care of the testnet runtimes and its infrastructure.
> The exact list can be seen at: https://github.com/paseo-network/paseo-action-submission/

**Q**. Are there any SLAs for incident management?
> Yes, find them at: https://github.com/paseo-network/paseo-action-submission/blob/main/pas/PAS-2-core-support-model.md

**Q**. Will it be possible to access the logs from the Relay and System chains?
> Yes, most infrastructure providers send logs to a centralized logging service that can be accessed at: https://grafana.paseo.site/

**Q**. I am a bit lost or I need further support, what do I do?
> The best way of contacting the involved contributors are:
> - Open an issue at: https://github.com/paseo-network/support
> - Join the public paseo matrix room: https://matrix.to/#/#paseo-testnet-support:parity.io
