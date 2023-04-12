[alchemy-sdk](../README.md) / [Exports](../modules.md) / GetContractsForOwnerResponse

# Interface: GetContractsForOwnerResponse

The response for the [NftNamespace.getContractsForOwner](../classes/NftNamespace.md#getcontractsforowner) method.

## Table of contents

### Properties

- [contracts](GetContractsForOwnerResponse.md#contracts)
- [pageKey](GetContractsForOwnerResponse.md#pagekey)
- [totalCount](GetContractsForOwnerResponse.md#totalcount)

## Properties

### contracts

• **contracts**: [`ContractForOwner`](ContractForOwner.md)[]

The list of contracts, that match the query, held by the given address.

#### Defined in

[src/types/types.ts:1020](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1020)

___

### pageKey

• `Optional` **pageKey**: `string`

Key for pagination to use to fetch results from the next page if available.

#### Defined in

[src/types/types.ts:1023](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1023)

___

### totalCount

• **totalCount**: `number`

Total number of NFT contracts held by the given address.

#### Defined in

[src/types/types.ts:1026](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1026)
