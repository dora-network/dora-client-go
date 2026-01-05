# ValidateSubmitOrderRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** |  | [default to null]
**Tick** | **string** | Minimum tradable increment for the selected order book | [default to null]
**Kind** | [***OrderKind**](OrderKind.md) |  | [default to null]
**Side** | [***Side**](Side.md) |  | [optional] [default to null]
**Price** | **string** | If kind is LIMIT, must be &gt; 0; if MARKET it must be 0 or omitted | [default to null]
**GoodTillDate** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**InverseLeverage** | **string** |  | [default to null]
**UserBalance** | **string** | User balance used to ensure they can afford the requested quantity | [default to null]
**BaseAssetId** | **string** | base asset of orderbook | [optional] [default to null]
**QuoteAssetId** | **string** | quote asset of orderbook | [optional] [default to null]
**PositionAssets** | [**[]ValidateSubmitOrderRequestPositionAssets**](ValidateSubmitOrderRequest_position_assets.md) | Full list of assets in the position with their price and collateral weight, required when inverse_leverage &lt; 1 for leverage health checks | [optional] [default to null]
**AssetsConfig** | [**[]ValidateSubmitOrderRequestAssetsConfig**](ValidateSubmitOrderRequest_assets_config.md) | Configuration for the assets in the order | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

