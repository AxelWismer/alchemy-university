# Alchemy University Ethereum Developer Bootcamp projects

## [ECDSA Node](https://github.com/AxelWismer/ecdsa-node)

https://user-images.githubusercontent.com/49920097/206914537-8491be30-90f3-4940-bc67-e5427cbdaadf.mp4

This project is an example of using a client and server to facilitate transfers between different addresses. It incorporates public key cryptography using Elliptic Curve Digital Signatures, so the server only allows transfers that have been signed by the person who owns the associated address.

## [Gift List](https://github.com/AxelWismer/GiftList)

This exercise demonstrates how you can use the Merkle tree to check if a data item is in a set without having to store the set.

In order to do this, the root of the Merkle tree is calculated and stored on the server. The client generates a proof that an element is in the set and sends it along with the element to be verified. The server calculates the root using the given proof and checks if it's equal to the stored root.

## [Block Explorer](https://github.com/AxelWismer/blockexplorer)
Ethereum block explorer app that uses the Alchemy SDK to perform complex blockchain queries.