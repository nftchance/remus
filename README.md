# πΊπΊ Remus 

When Romulus and Remus became adults, they decided to found a city where the wolf had found them. This is my city, a collection of semi-opinionated, lightweight, and build-ready EVM primitives for smart contract development.

```ml
auth
ββ β BadgeAccessControl - "Variant of OpenZeppelin AccessControl using ERC1155 Badges."
ββ β Fingerprint - "Access control powered by fingerprinted ERC721 tokens."
ββ β NBadgeAuth - "On-chain access control powered by complex uses of ERC1155 Badges."
ββ β NBadgeRegistry - "Public shared-access registry powering Badged credentials with simple inheritance."
ββ extensions
|  ββ β NBadgeAuthConsumer- "Localized consumer of a Network Governors NBadge permission constitutions."
ββ modules
|  ββ β NBadgeModule - "Extendable framework for creating a plug-and-play registry access module."
|  ββ β NBadgeIdPacked - "Gating by multiple token ids of a single Badge collection."
|  ββ β NBadgeMultiBalance - "Simple gating by a cumulative balance of Badges held."
|  ββ β NBadgeMultiBalancePoints - "Complex gating by a cumulative point-driven system based on Badges held."
math
ββ β³ MathlessCurves - "Shapeless curves for the EVM using Fourier series."
metatx
ββ β BadgingForwarder - "Forwarder contract that mints a Badge upon transaction execution."
tokens
ββ ERC20
|  ββ β³ ERC20Generational - "Birth and death to emulate culture volatility."
ββ ERC721
|  ββ β³ ERC721Hooked - "Non-fungible token with transfer-hooks enabling external state updates."
|  ββ β³ ERC721Mirror - "Ghost-ownership implementation to efficiently airdrop an entire ERC721 collection."
|  ββ β³ ERC721Receivable - "Mint tokens upon the receipt of ETH, ERC20, ERC721 or ERC1155."
ββ ERC1155
|  ββ β³ ERC1155Throttled - "Implement a throttled-to-cooldown state on token minting when activity exceeds a maximum.
```

## Safety

This is experimental software and is provided on an "as is" and "as available" basis.

We do not give any warranties and will not be liable for any loss incurred through any use of this codebase.