# CreateOrderRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** |  | [default to null]
**InverseLeverage** | **float64** | Required: Inverse leverage for the order, must be between 0 and 1 (inclusive) | [default to null]
**Price** | **string** |  | [default to null]
**Kind** | [***OrderKind**](OrderKind.md) |  | [default to null]
**Side** | [***Side**](Side.md) |  | [default to null]
**OrderBookId** | **string** | Required: the order book to submit the order to | [default to null]
**UserText** | **string** | Optional: User-defined text for the order, e.g., &#x27;buying dips&#x27; | [optional] [default to null]
**OrderModifiers** | [**[]OrderModifierKind**](OrderModifierKind.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

