# CreateOrderRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** |  | [optional] [default to null]
**InverseLeverage** | **float64** | Required: Inverse leverage for the order, must be between 0 and 1 (inclusive) | [optional] [default to null]
**Price** | **string** |  | [optional] [default to null]
**Kind** | **string** |  | [optional] [default to null]
**Side** | **string** | Required: Must be either &#x27;BUY&#x27; or &#x27;SELL&#x27; | [optional] [default to null]
**OrderBookId** | **string** | Required: the order book to submit the order to | [optional] [default to null]
**UserText** | **string** | Optional: User-defined text for the order, e.g., &#x27;buying dips&#x27; | [optional] [default to null]
**OrderModifiers** | **[]string** |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

