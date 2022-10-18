# celestia-bundlr

## Notes

* Intuition is that CIDs can be processed on Celestia (where exactly, is the question--gossipsub(?)), which route to bundlr, or equivalent service.
* I beleive the entire lesson data fields (whether that be a smart contract like it is now, or a struct) should be included in the block type somewhere in this file...within the header struct perhaps? https://github.com/celestiaorg/rollmint/blob/main/types/block.go
* 

### Resources

* https://docs.bundlr.network/docs/client/examples/full-example
* Possibly can add the lesson metadata fields (see here: https://github.com/DED-EDU/DED/blob/main/src/DEDListing.sol) to the Client struct here: https://github.com/DED-EDU/rollmint/blob/main/p2p/client.go (?)
* https://github.com/The-Arbiter/Hash-Storage-Example/blob/main/src/HashStore.sol
* https://docs.ipfs.tech/concepts/content-addressing/#what-is-a-cid
