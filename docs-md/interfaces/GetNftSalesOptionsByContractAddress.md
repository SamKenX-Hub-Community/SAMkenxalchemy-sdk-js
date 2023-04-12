[alchemy-sdk](../README.md) / [Exports](../modules.md) / GetNftSalesOptionsByContractAddress

# Interface: GetNftSalesOptionsByContractAddress

Alternative optional parameters object for the [NftNamespace.getNftSales](../classes/NftNamespace.md#getnftsales)
method that allows filtering results by contractAddress.

This interface is used to filter the NFT sales data.

## Hierarchy

- [`GetNftSalesOptions`](GetNftSalesOptions.md)

  ↳ **`GetNftSalesOptionsByContractAddress`**

## Table of contents

### Properties

- [buyerAddress](GetNftSalesOptionsByContractAddress.md#buyeraddress)
- [contractAddress](GetNftSalesOptionsByContractAddress.md#contractaddress)
- [fromBlock](GetNftSalesOptionsByContractAddress.md#fromblock)
- [limit](GetNftSalesOptionsByContractAddress.md#limit)
- [marketplace](GetNftSalesOptionsByContractAddress.md#marketplace)
- [order](GetNftSalesOptionsByContractAddress.md#order)
- [pageKey](GetNftSalesOptionsByContractAddress.md#pagekey)
- [sellerAddress](GetNftSalesOptionsByContractAddress.md#selleraddress)
- [taker](GetNftSalesOptionsByContractAddress.md#taker)
- [toBlock](GetNftSalesOptionsByContractAddress.md#toblock)
- [tokenId](GetNftSalesOptionsByContractAddress.md#tokenid)

## Properties

### buyerAddress

• `Optional` **buyerAddress**: `string`

The address of the NFT buyer to filter sales by.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[buyerAddress](GetNftSalesOptions.md#buyeraddress)

#### Defined in

[src/types/types.ts:1194](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1194)

___

### contractAddress

• **contractAddress**: `string`

The contract address of a NFT collection to filter sales by.

#### Defined in

[src/types/types.ts:1223](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1223)

___

### fromBlock

• `Optional` **fromBlock**: `number` \| ``"latest"``

The block number to start fetching NFT sales data from.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[fromBlock](GetNftSalesOptions.md#fromblock)

#### Defined in

[src/types/types.ts:1182](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1182)

___

### limit

• `Optional` **limit**: `number`

The maximum number of NFT sales to return.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[limit](GetNftSalesOptions.md#limit)

#### Defined in

[src/types/types.ts:1206](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1206)

___

### marketplace

• `Optional` **marketplace**: [`NftSaleMarketplace`](../enums/NftSaleMarketplace.md)

The NFT marketplace to filter sales by.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[marketplace](GetNftSalesOptions.md#marketplace)

#### Defined in

[src/types/types.ts:1191](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1191)

___

### order

• `Optional` **order**: [`SortingOrder`](../enums/SortingOrder.md)

Whether to return the results in ascending or descending order by block number.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[order](GetNftSalesOptions.md#order)

#### Defined in

[src/types/types.ts:1188](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1188)

___

### pageKey

• `Optional` **pageKey**: `string`

Key for pagination to use to fetch results from the next page if available.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[pageKey](GetNftSalesOptions.md#pagekey)

#### Defined in

[src/types/types.ts:1209](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1209)

___

### sellerAddress

• `Optional` **sellerAddress**: `string`

The address of the NFT seller to filter sales by.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[sellerAddress](GetNftSalesOptions.md#selleraddress)

#### Defined in

[src/types/types.ts:1197](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1197)

___

### taker

• `Optional` **taker**: [`NftSaleTakerType`](../enums/NftSaleTakerType.md)

Filter by whether the buyer or seller was the taker in the NFT trade.
Defaults to returning both buyer and seller taker trades.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[taker](GetNftSalesOptions.md#taker)

#### Defined in

[src/types/types.ts:1203](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1203)

___

### toBlock

• `Optional` **toBlock**: `number` \| ``"latest"``

The block number limit to fetch NFT sales data from.

#### Inherited from

[GetNftSalesOptions](GetNftSalesOptions.md).[toBlock](GetNftSalesOptions.md#toblock)

#### Defined in

[src/types/types.ts:1185](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1185)

___

### tokenId

• `Optional` **tokenId**: [`BigNumberish`](../modules.md#bignumberish)

The token ID of an NFT within the specified contractAddress to filter sales by.

#### Defined in

[src/types/types.ts:1226](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L1226)
