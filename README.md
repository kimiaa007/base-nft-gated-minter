# base-nft-gated-minter

Gated NFT minter on Base. Only allowed addresses (allowlist / role) can mint.

## Stack
- Solidity (ERC721 + access control)
- Kotlin client
- Base (L2)

## Structure
- `contracts/` — Solidity contracts
- `clients/kotlin/` — Kotlin client

## Notes
- Use OpenZeppelin AccessControl for roles.
- Extend with merkle proof allowlist and metadata.

## License
MIT
