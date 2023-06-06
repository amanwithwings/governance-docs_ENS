---
description: A short (1-2 sentence) description of the proposal.
---

# [Executable] Proposal Title

| **Status**            | Pending                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Discussion Thread** | [Discuss](https://discuss.ens.domains/t/extend-ens-dao-to-eip-4824/17249)                                                                                                |
| **Votes**             | Pending                                                                                                                                     |

# Abstract
<!--
  This proposal will extend ENS DAO to EIP-4824 by deploying a new registration contract through a contract interaction with the EIP-4824 factory maintained by DAOstar. The EIP-4824 standard 2 defines common interfaces for DAOs via daoURI, akin to tokenURI for NFTs.
-->

# Rationale
<!--
  Adopting the EIP-4824 standard will enrich the on-chain information availability of ENS governance contracts, making it easier for existing and future DAO tools to seamlessly interact with the contracts. A specific example is enabling members to interact with the ENS governance contracts through different front-end interfaces, potentially across multiple chains. Some of the tools that are digesting or committed to digesting this enriched information include Snapshot, Tally, DAOhaus, Etherscan, DeepDAO, and other members of DAOstar One 3.

Note that adopting the standard does not require any parameter changes to ENS’s existing DAO contracts, nor is there any cost besides gas to call the factory contract. The proposal does not in any way change the way that ENS’s governance works.
-->

# Specification
<!-- 
  By voting yes, the ENS DAO will (1) upgrade to EIP-4824 by calling the EIP-4824 registration contract located at 0x37df3fc47c1c3a2acafd2dad9c1c00090a8655bc, setting the _[ENS Timelock]_(https://etherscan.io/address/0xFe89cc7aBB2C4183683ab71653C4cdc9B02D44b7) and the _[MetaGovernance WG multisig] _(https://etherscan.io/address/0x91c32893216de3ea0a55abb9851f581d4503d39b) as its admin and Joshua Tan (thelastjosh.eth) of DAOstar as its manager.
 -->

# Transactions
<!-- The transactions section describes all the calls that should be encoded in the onchain version of this proposal. Use the table below as a starting point. -->
<table>
    <tr>
        <th>Address</th>
        <th>Value</th>
        <th>Function</th>
        <th>Argument</th>
        <th>Value</th>
    </tr>
    <tr>
        <td rowspan=2>Address or ENS name of target</td>
        <td rowspan=2>Value to send (ETH)</td>
        <td rowspan=2>Function identifier</td>
        <td>First arg</td>
        <td>First value</td>
    </tr>
    <tr>
        <td>Second arg</td>
        <td>Second value</td>
    </tr>
</table>
