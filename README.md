# Nouns 95 Subgraphs

A collection of subgraphs indexing Nouns DAO smart contracts, developed by Macrohard. These subgraphs provide comprehensive event tracking and data aggregation for the Nouns DAO ecosystem.

## Governance Subgraph

The governance subgraph indexes events and metrics from the following contracts:

### DAO Logic
- NounsDAOLogicV1 (`0xa43aFE317985726E4e194eb061Af77fbCb43F944`)
- NounsDAOLogicV2 (`0xCaCF365eDA93F07741a80D4F39a773BAaBb3a873`)
- NounsDAOLogicV2.1 (`0x51C7D7C47E440d937208bD987140D6db6B1E4051`)
- NounsDAOLogicV3 (`0xe3caa436461DBa00CFBE1749148C9fa7FA1F5344`)
- NounsDAOLogicV4 (`0xA23e8A919D29d74Ee24d909D80f4bC8778d656d1`)

### Candidates & DUNA Admin System
- CandidatesAdminV1 (`0x624eFabA6E7df177AD8cA5BeE3bD62f78B304B6e`)
- CandidatesAdminV2 (`0x513e9277192767eb4dc044A08da8228862828150`)

### Token
- NounsToken (`0x9C8fF314C9Bc7F6e59A9d9225Fb22946427eDC03`)

## Financials Subgraph

The financials subgraph indexes events and metrics from the following contracts:

### Treasury Management
- TreasuryV1 (`0x0BC3807Ec262cB779b38D65b38158acC3bfedE10`)
- TreasuryV2 (`0x0FB7CF84F171154cBC3F553aA9Df9b0e9076649D`)
- TokenBuyer (`0x4f2acdc74f6941390d9b1804fabc3e780388cfe5`)
- USDCPayer (`0xd97Bcd9f47cEe35c0a9ec1dc40C1269afc9E8E1D`)
- StreamFactory (`0x0fd206FC7A7dBcD5661157eDCb1FFDD0D02A61ff`)

### Auction System
- AuctionHouseV1 (`0xF15a943787014461d94da08aD4040f79Cd7c124e`)
- AuctionHouseV2 (`0x9E9E1b545Bf48F4C81A13589cf5c9A3E9E4D5c77`)
- AuctionHouseV3 (`0x1D835808ddCa38fbE14e560D8e25b3D256810aF0`)
- ClientRewards (`0xaaF173E6b65aa4473C830EDB402D26B7A33c5E94`)

## Features

### Governance
- Complete proposal lifecycle tracking
- Vote tracking with support levels and vote weights
- Candidate system monitoring
- Token holder activity tracking

### Financials
- Comprehensive event tracking for all DAO financial operations
- Daily metrics aggregation for treasury, auctions, and client activities
- Client rewards and participation tracking
- Token streaming and debt management monitoring
- Historical data for all contract interactions

## Deployment

The subgraphs are deployed on Goldsky and can be accessed at:

### Governance Subgraph
- Dashboard: https://api.goldsky.com/api/public/project_cm7pqlylm0sy201xib6m37zoe/subgraphs/nouns95-financials-mainnet/1.0.0/
- GraphQL API: https://api.goldsky.com/api/public/project_cm7pqlylm0sy201xib6m37zoe/subgraphs/nouns95-financials-mainnet/1.0.0/gn

### Financials Subgraph
- Dashboard: https://app.goldsky.com/project_cm7pqlylm0sy201xib6m37zoe/dashboard/subgraphs/nouns95-financials-mainnet/1.0.0
- GraphQL API: https://api.goldsky.com/api/public/project_cm7pqlylm0sy201xib6m37zoe/subgraphs/nouns95-financials-mainnet/1.0.0/gn

## Development

The subgraphs are configured using Goldsky's no-code configuration system. Key files:

### Governance
- `governance/nouns95-governance/1.0.0/nouns95-governance-config.json`: Main configuration file
- `governance/schema.graphql`: GraphQL schema defining all entities and relationships
- `governance/nouns95-governance/1.0.0/abis/`: Contract ABIs

### Financials
- `financials/nouns95-financials/1.0.0/nouns95-financials-config.json`: Main configuration file
- `financials/schema.graphql`: GraphQL schema defining all entities and relationships
- `financials/nouns95-financials/1.0.0/abis/`: Contract ABIs

## License

MIT 