# BOSIPs Introduction

BOS Improvement Proposals (BOSIPs) describ procedures and standards for BOS, including BOS core protocol specifications, networking protocols, client API/RPC, and contract standards.

How to contribute？Here is a [template BOSIP here](https://github.com/boscore/BOSIPs/blob/master/BOSIPS/bosip-xxxxxxxx.md).

# BOSIP Status Terms

- **Draft** - one BOSIP which is undergoing rapid iteration and changes, forming into something specific and concret.
- **Last Call** - BOSIPs that are done with initial iterations and will be reviewed by the more in time.
- **Accepted (Core)** - a core BOSIP that has been in **Last Call** for 2 weeks or more and any technical changes that were requested have been addressed by the author.
- **Final (Core)** - a BOSIP which the Core-Developing-Groups have decided to implement and release in a future hard fork, or has already released in a hard fork.
- **Final (non-Core)** - BOSIPs that have been in **Last Call** for 2 weeks or more and any technical changes that were requested have been addressed by the author.
- **Deferred** - BOSIPs that are not being considered for immediate adoption. May be considered in the future.

![](https://github.com/boscore/BOSIPs/blob/master/assets/class.png)

# BOSIP Types

BOSIPs are now separated into several different types as described below. For now, all of the BOSIPs types belong to `Standard Tracking`, which describes changes that affect most or all BOS implementations, such as a change to the BOS IBC Priciples, a change to BOS networking protocols, a change to BOS Batch-PBFT Solutions, or a change to BOS  API/RPC specifications, or anything not mentioned but will affect the interoperability of applications that are using BOS. In details, Standard Tracking BOSIPs can be broken down into the following categories

## Core

Improvements on BOS and need a consensus fork, as well as changes that are not necessarily consensus critical but may be relevant to core-developing-group discussions. This part could include core-changes on IBC or Batch-PBFT.

## Networking

Improvements on BOS p2p networking protocols and so on.

## Interface

Includes improvements around client API/RPC specifications and standards, and also certain language-level standards like method names, parameters and so on.

## BRC

Improvements on Application-level standards and conventions, such as changes on eosio.token contract.

# Examples

Coming soon.

