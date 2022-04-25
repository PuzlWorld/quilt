# Quilt

This repository contains the core smart contracts for the Quilt V1 Protocol.


Quilt is a protocol aimed at migrating abandoned tokens (namely NFT) into wrapped instances to be utilized in alternative ways. A Patchwork systems for rugs if you will.


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
