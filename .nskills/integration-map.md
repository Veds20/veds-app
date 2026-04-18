# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`506dc698`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`b218870e`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`b218870e`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`9b156934`)
  
