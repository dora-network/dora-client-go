# StreamedAssetPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Price** | **string** |  | 
**Time** | **time.Time** |  | 

## Methods

### NewStreamedAssetPrice

`func NewStreamedAssetPrice(assetId string, price string, time time.Time, ) *StreamedAssetPrice`

NewStreamedAssetPrice instantiates a new StreamedAssetPrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamedAssetPriceWithDefaults

`func NewStreamedAssetPriceWithDefaults() *StreamedAssetPrice`

NewStreamedAssetPriceWithDefaults instantiates a new StreamedAssetPrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *StreamedAssetPrice) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *StreamedAssetPrice) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *StreamedAssetPrice) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetPrice

`func (o *StreamedAssetPrice) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *StreamedAssetPrice) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *StreamedAssetPrice) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetTime

`func (o *StreamedAssetPrice) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *StreamedAssetPrice) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *StreamedAssetPrice) SetTime(v time.Time)`

SetTime sets Time field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


