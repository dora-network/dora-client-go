# CreateOrderRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** |  | [default to null]
**InverseLeverage** | **string** |  | [default to null]
**Price** | **string** |  | [optional] [default to null]
**Kind** | [***OrderKind**](OrderKind.md) |  | [default to null]
**Side** | [***Side**](Side.md) |  | [default to null]
**PositionId** | **string** | position ID to use for the order. required. | [default to null]
**OrderBookId** | **string** | Required: the order book to submit the order to | [default to null]
**OrderModifiers** | [**[]OrderModifierKind**](OrderModifierKind.md) |  | [optional] [default to null]
**GoodTillDate** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**TriggerPrice** | **string** |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

