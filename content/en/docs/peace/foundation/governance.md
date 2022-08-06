---
title: Governance
weight: 15
lead: "Peace DAO's purpose is to fund life-saving assistance and support for refugees of war and internally displaced people. The following is an initial framework for the governance of Peace DAO, the execution of funding initiatives, and the management of Peace DAO’s treasury."
---

## I. The Peace DAO Council 

The Peace DAO ("DAO") Council ("Council") exists to curate Peace DAO governance proposals ("Proposals"). Council members ("Stewards") hold credentials over DAO tooling, including the Endowment Treasury[^1], the Operational Treasury[^2], the [Juicebox](https://juicebox.money/p/peace), the [Snapshot Space](https://snapshot.org/#/peace.movedao.eth), the [website](https://peace.move.xyz), social media accounts, and the [Discord server](https://discord.gg/movexyz). Stewards must publish a quarterly outline of all expenditures from the Operational Treasury and transactions from the Endowment Treasury.

Stewards may be appointed or removed by Proposals. Stewards may also be appointed by unanimous public consent of the Council. The initial Stewards are:

|Discord|Ethereum Address|ENS|
|-|-|-|
|@Fuego#4208|0x06bc1be1b5dd4d287a3be9b72dbe8eda8297c465|fuegomoves.eth|
|@tankbottoms(🎽,🍑)#2749|0x5d95baEBB8412AD827287240A5c281E3bB30d27E|tankbottoms.eth|
|@theryanking#1111|0x8C00f41676Ce4670ae9FcBBF297a24736dc23cc3|ryan-breslow.eth|
|@\_anna#5501|Unavailable|N/A|

Stewards must agree to act in accordance with the will of PeaceDAO, as expressed through PeaceDAO's Governance Framework.

## II. Proposal Process
> Before implementation, signatures and transactions from `peace.movedao.eth` and updates to DAO documents or processes must be submitted as Proposals and ratified by this process.

{{< alert icon="⚠️" context="info" text="Throughout the Proposal Process, the term \"name\" refers to an individual's Ethereum address, Ethereum Name Service name (\"ENS\"), Discord handle, Twitter handle, or another form of identification sufficient to identify that individual." />}}

### 1) Submission

Anyone holding a Peace DAO Movement token[^3] may submit a Proposal to the `#✍│proposals` channel in the [DAO's Discord](https://discord.gg/movexyz). All submissions must be discussed and workshopped by the DAO community in public Peace Ops meetings.

**Peace Funding Initiatives** ("PFI"s) are proposals to fund relief efforts. All other Proposals are **Peace DAO Proposals** ("PDP"s).

Proposals must include:
- The name of the author(s).
- A Peace DAO Proposal (PDP-#) or Peace Funding Initiative (PFI-#) number.
- A specification containing the transaction(s) to execute, including specific quantities of assets to be transferred and the recipient’s Ethereum address(es) if applicable.

### 2) Snapshot Voting

Steward(s) may endorse a Proposal by publicly stating their support and publishing the proposal to the [DAO's Snapshot Space](https://snapshot.org/#/peace.movedao.eth) for Basic voting with a 5 day Voting period. Proposals must be announced in the DAO's Discord at least 24 hours before voting opens. Donors can elect to be emailed with voting and delegation instructions.

When publishing Proposals, Stewards must include:
- The name(s) of the Steward(s) endorsing it.
- A link documenting public Steward endorsement.
- The full proposal text, or a link to an immutable copy of the full proposal text.

The [DAO's Snapshot Space](https://snapshot.org/#/peace.movedao.eth) ought to grant one vote per PEACE Token[^4] and use a Delegation strategy.[^5]

Proposals which receive affirmative votes amounting to at least 60% of total votes are queued for execution by the Council. "Abstain" votes are not included in this calculation.

### 3) Emergency Funding Initiatives

In an emergency scenario, the Council can utilize Operational Treasury[^2] funds with explicit public approval from all Stewards. Any such intiative must be announced immediately, along with any relevant transactions. A PFI can be created to retroactively refund the Operational Treasury.

## III. Peace DAO Treasury

### 1) Endowment Treasury

The Endowment Treasury[^1] is a Gnosis Safe which receives funds from the DAO's [Juicebox Project](https://juicebox.money/p/peace). The current signers are `dao-lawfirm.eth`, `tankbottoms.eth`, `natasha-pankina.eth`, `ryan-breslow.eth`, and `jimmyethworld.eth`, and the current threshold is 3 signers. The Endowment Treasury's configuration, threshold, and signer membership can be updated by Proposals.

### 2) Operational Treasury

The Operational Treasury[^2] shall receive 5% percent of all assets, or the equivalent value in ETH or DAI, contributed to the Endowment Treasury, and may receive additional funds because of a Proposal. The Operational Treasury shall receive 10% of reserved tokens the Endowment Treasury receives from the DAO's Juicebox Project. The Council may utilize the Operational Treasury at their discretion, but must abide by ratified Proposals.

[^1]: The Endowment Treasury Gnosis Multi-Signature Safe can be found on the Ethereum mainnet at `0xD2427c0e44D28Ea74c0504E072c6073d135569B2`.
[^2]: The Operation Treasury Gnosis Multi-Signature Safe can be found on the Ethereum mainnet at `0xD2427c0e44D28Ea74c0504E072c6073d135569B2`
[^3]: Peace Movement DAO's Mainnet Ethereum NFT: `0x1c43E7Fb2885d9FF4403521eAE41d7943F7f51Ee` [*OpenSea*](https://opensea.io/collection/peace-dao-distortion-v2).
[^4]: Peace Movement DAO's Mainnet Ethereum Token: `0xdE43304bD02E5517a1B646179eb9612b5d58E6A1`
[^5]: See the [Snapshot Docs](https://docs.snapshot.org/guides/delegation). Deployed on the Ethereum mainnet at [`0x469788fE6E9E9681C6ebF3bF78e7Fd26Fc015446`](https://etherscan.io/address/0x469788fE6E9E9681C6ebF3bF78e7Fd26Fc015446).
