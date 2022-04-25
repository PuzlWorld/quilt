# Quilt

This repository contains the core smart contracts for the Quilt V1 Protocol.


Quilt is a protocol aimed at migrating abandoned tokens (namely NFT) into wrapped deflationary instances. A Patchwork systems for rugs if you will.

#### Core Implementations:

* Initialize a Quilt instance
* Register 'rug' collection IDs on instance (initial support ERC-721)
* Use interface in target workflow (mint, claim, allow, etc...) 
* (optional) explore BONDfire
* (optional) explore auto burn

#### Core Use Cases:

* Allow list - Fundementally 'paying' with registered collection
* Mint Coupon - A discount mechanism reducing payable requirement in a "mint"
* Migration - While not target, can be used for a token migration
* Rebalancing - Abtract case: effectively creating new market dynamics in an existing collection by reducing supply
* ReMint - An experimental concept of re minting an active part of an existing collection (think git branch). Optional, one could pair with a dutch auction to create new equilibrium across a lively sub group.

### Core smart contracts of Quilt v1


### Using solidity interfaces
The Quilt v1 interfaces are available for import into solidity smart contracts via the npm artifact @puzlworld/v1-quilt, e.g.:
```
import '@puzlworld/v3-quilt/contracts/interfaces/IQuiltAccept.sol';

contract MyContract {
  IQuiltAccept patch;

  function doSomethingWithPath() {
    // path.register(...);
  }
}
```


Licensing
The primary license for Quilt V1 is MIT, see LICENSE.
