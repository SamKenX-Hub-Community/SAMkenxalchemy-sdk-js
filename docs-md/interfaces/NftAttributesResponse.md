[alchemy-sdk](../README.md) / [Exports](../modules.md) / NftAttributesResponse

# Interface: NftAttributesResponse

Summary of the attribute prevalence for the specified NFT contract.

## Table of contents

### Properties

- [contractAddress](NftAttributesResponse.md#contractaddress)
- [summary](NftAttributesResponse.md#summary)
- [totalSupply](NftAttributesResponse.md#totalsupply)

## Properties

### contractAddress

• **contractAddress**: `string`

The specified NFT contract's address.

#### Defined in

[src/types/types.ts:1371](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1371)

___

### summary

• **summary**: `Record`<`string`, `Record`<`string`, `number`\>\>

The attribute prevalence of each trait grouped by the trait type for the
provided NFT.

#### Defined in

[src/types/types.ts:1380](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1380)

___

### totalSupply

• **totalSupply**: `number`

The specified NFT contract's total supply.

#### Defined in

[src/types/types.ts:1374](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1374)
