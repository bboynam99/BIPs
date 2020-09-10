<!--
BIP: 1
title: BIP Purpose and Guidelines
status: Active
type: Meta
author: Bee2 core developers <shellzxc@gmail.com> 
created: 2020-09-09
updated: 2020-09-09
-->

# BIP-1

## What is an BIP?

BIP stands for Bee2 Improvement Proposal. A BIP is a design document providing information to the Bee2 community, or describing a new feature for Bee2 or its processes or environment. The BIP should provide a concise technical specification of the feature and a rationale for the feature. The BIP author is responsible for building consensus within the community and documenting dissenting opinions.

## BIP Rationale

We intend BIPs to be the primary mechanisms for proposing new features, for collecting community technical input on an issue. Because the BIPs are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.

BIPs are a convenient way to track the progress of their implementation. Ideally each implementation maintainer would list the BIPs that they have implemented. This will give end users a convenient way to know the current status of a given implementation or library.

### BIP Process 

```
[ WIP ] -> [ DRAFT ] -> [ LAST CALL ] -> [ FINAL ]
```

Following is the process that a BIP will move along:

```
[ IDEA ] -> [ DRAFT ] -> [ LAST CALL ] -> [ ACCEPTED ] -> [ FINAL ]
```

Each status change is requested by the BIP author and reviewed by the BIP editors. Use a pull request to update the status. Please include a link to where people should continue discussing your BIP. The BIP editors will process these requests as per the conditions below.

## BIP Formats and Templates

BIPs should be written in [markdown] format.
Image files should be included in a subdirectory of the `assets` folder for that BIP as follows: `assets/BIP-N` (where **N** is to be replaced with the BIP number). When linking to an image in the BIP, use relative links such as `../assets/BIP-1/image.png`.


## History

This document was derived heavily from [Ethereum's EIP-0001] written by Martin Becze, Hudson Jameson, and others which in turn was derived from [Python's PEP-0001]. In many places text was simply copied and modified.

### Bibliography


[API/RPC]: https://documenter.getpostman.com/view/1112175/SzS5u6bE?version=latest
[interfaces repo]: https://github.com/okex/okchain-interfaces
[markdown]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[Ethereum's EIP-0001]: https://eips.ethereum.org/EIPS/eip-1
[Python's PEP-0001]: https://www.python.org/dev/peps/
[AllCoreDevs agenda GitHub Issue]: https://github.com/okex/okchain-pm/issues