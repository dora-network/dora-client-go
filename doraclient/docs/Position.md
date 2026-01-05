# Position

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique identifier for the position. Used, for example, when creating an order from a position, or deciding collateral should be transferred from position A to position B. | [optional] [default to null]
**AssetId** | **string** |  | [optional] [default to null]
**Seq** | **int32** |  | [optional] [default to null]
**IsGlobal** | **bool** |  | [optional] [default to null]
**Available** | **string** | The available balance in the position for this asset that are not locked, supplied, or used as collateral | [optional] [default to null]
**Locked** | **string** | The balance that has been reserved for a current order. If spent by the order, they are removed. If the order is cancelled, they are returned to the position&#x27;s available balance. | [optional] [default to null]
**Supplied** | **string** | The balance that user has supplied to the leverage module. The user remains entitled to these assets and can withdraw them into their available balance. | [optional] [default to null]
**Borrowed** | **string** | The total amount of debt outstanding for this position. This position cannot be closed until all debt is fully repaid, i.e. borrowed &#x3D; 0. | [optional] [default to null]
**ImpendingBorrows** | **string** | The equivalent of locked balances, but for leveraged orders. If a user has an active order that would borrow assets as part of its input, then their borrow limit must be reduced until the order is executed or cancelled. | [optional] [default to null]
**AvgEntryPrice** | **string** | average cost per unit quantity that was paid (long positions) or received (short positions) for this asset. | [optional] [default to null]
**BorrowLimit** | **string** | The borrow limit | [optional] [default to null]
**LiquidationThreshold** | **string** | The borrow limit | [optional] [default to null]
**CreatedAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**PositionName** | **string** |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

