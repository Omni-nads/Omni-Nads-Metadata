# Omni Nads NFT Collection Metadata Structure

This document outlines the metadata structure used for the Omni Nads NFT collection. Below is the hierarchical organization of the metadata:

## Metadata Structure
```
- images/
    - [chain]/
        - [tokenState]/
            - image
- metadata/
    - [chain]/
        - [tokenState]/
            - json
```
### Explanation
- **images/**: Stores the image assets associated with each NFT.
  - **[chain]**: Represents the blockchain the NFT is deployed on.
  - **[tokenState]**: Indicates the current state of the token (e.g., minted, burned, staked, etc.).
  - **image**: The actual image file corresponding to the NFT.

- **metadata/**: Contains the metadata files for each NFT.
  - **[chain]**: Represents the blockchain the NFT is deployed on.
  - **[tokenState]**: Indicates the current state of the token.
  - **json**: The metadata JSON file that includes attributes, properties, and other necessary details.