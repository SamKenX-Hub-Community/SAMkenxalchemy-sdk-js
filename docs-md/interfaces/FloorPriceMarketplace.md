[alchemy-sdk](../README.md) / [Exports](../modules.md) / FloorPriceMarketplace

# Interface: FloorPriceMarketplace

The successful object returned by the [getFloorPrice](../classes/NftNamespace.md#getfloorprice) call for each
marketplace (e.g. looksRare).

## Table of contents

### Properties

- [collectionUrl](FloorPriceMarketplace.md#collectionurl)
- [floorPrice](FloorPriceMarketplace.md#floorprice)
- [priceCurrency](FloorPriceMarketplace.md#pricecurrency)
- [retrievedAt](FloorPriceMarketplace.md#retrievedat)

## Properties

### collectionUrl

• `Readonly` **collectionUrl**: `string`

The link to the collection on the given marketplace

#### Defined in

[src/types/types.ts:947](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L947)

___

### floorPrice

• `Readonly` **floorPrice**: `number`

The floor price of the collection on the given marketplace

#### Defined in

[src/types/types.ts:943](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L943)

___

### priceCurrency

• `Readonly` **priceCurrency**: `string`

The currency in which the floor price is denominated

#### Defined in

[src/types/types.ts:945](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L945)

___

### retrievedAt

• `Readonly` **retrievedAt**: `string`

UTC timestamp of when the floor price was retrieved from the marketplace

#### Defined in

[src/types/types.ts:949](https://github.com/alchemyplatform/alchemy-sdk-js/blob/e62e5c7/src/types/types.ts#L949)
