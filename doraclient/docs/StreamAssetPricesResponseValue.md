# StreamAssetPricesResponseValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Price** | **float64** |  | 
**Time** | **time.Time** |  | 

## Methods

### NewStreamAssetPricesResponseValue

`func NewStreamAssetPricesResponseValue(assetId string, price float64, time time.Time, ) *StreamAssetPricesResponseValue`

NewStreamAssetPricesResponseValue instantiates a new StreamAssetPricesResponseValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamAssetPricesResponseValueWithDefaults

`func NewStreamAssetPricesResponseValueWithDefaults() *StreamAssetPricesResponseValue`

NewStreamAssetPricesResponseValueWithDefaults instantiates a new StreamAssetPricesResponseValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *StreamAssetPricesResponseValue) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *StreamAssetPricesResponseValue) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *StreamAssetPricesResponseValue) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetPrice

`func (o *StreamAssetPricesResponseValue) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *StreamAssetPricesResponseValue) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *StreamAssetPricesResponseValue) SetPrice(v float64)`

SetPrice sets Price field to given value.


### GetTime

`func (o *StreamAssetPricesResponseValue) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *StreamAssetPricesResponseValue) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *StreamAssetPricesResponseValue) SetTime(v time.Time)`

SetTime sets Time field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


