# CouponPayment

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [optional] [default to null]
**AssetId** | **string** |  | [optional] [default to null]
**Yield** | **float64** |  | [optional] [default to null]
**StartAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**EndAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**PayAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**AvailableToPay** | **string** |  | [optional] [default to null]
**CompletedAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**CreatedAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**ProcessEvery** | **int32** | Number of nanoseconds to wait between coupon payment processing, must be at least 1000 (1 microsecond) | [optional] [default to null]
**LastProcessedAt** | [**time.Time**](time.Time.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

