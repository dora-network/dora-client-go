# Order

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | **string** |  | [optional] [default to null]
**OrderBookId** | **string** |  | [optional] [default to null]
**Kind** | [***OrderKind**](OrderKind.md) |  | [optional] [default to null]
**OriginalPrice** | **string** | If Kind is LIMIT, this is the original limit price. If Kind is MARKET, this may be 0 or omitted. | [optional] [default to null]
**AvgFillPrice** | **string** |  | [optional] [default to null]
**CancelledQuantity** | **string** | Quantity that was cancelled, if any. | [optional] [default to null]
**OpenQuantity** | **string** | Quantity that is still open, i.e., not filled or cancelled. | [optional] [default to null]
**OriginalQuantity** | **string** | The original quantity of the order when it was created. | [optional] [default to null]
**FilledQuantity** | **string** | Quantity that has been filled so far. | [optional] [default to null]
**FilledNotional** | **string** | Quote quantity that has been filled so far. | [optional] [default to null]
**LastUpdateAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**OpenedAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**InverseLeverage** | **string** |  | [optional] [default to null]
**Side** | [***Side**](Side.md) |  | [optional] [default to null]
**Status** | [***OrderStatus**](OrderStatus.md) |  | [optional] [default to null]
**UserId** | **string** |  | [optional] [default to null]
**OrderModifiers** | [**[]OrderModifierKind**](OrderModifierKind.md) |  | [optional] [default to null]
**PositionId** | **string** |  | [optional] [default to null]
**OrderInfo** | **string** |  | [optional] [default to null]
**GoodTillDate** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**TriggerPrice** | **string** |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

