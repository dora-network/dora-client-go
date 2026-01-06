# AssetPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | Pointer to **string** |  | [optional] 
**Price** | Pointer to **float64** |  | [optional] 
**Time** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewAssetPrice

`func NewAssetPrice() *AssetPrice`

NewAssetPrice instantiates a new AssetPrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetPriceWithDefaults

`func NewAssetPriceWithDefaults() *AssetPrice`

NewAssetPriceWithDefaults instantiates a new AssetPrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetPrice) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetPrice) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetPrice) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.

### HasAssetId

`func (o *AssetPrice) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

### GetPrice

`func (o *AssetPrice) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *AssetPrice) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *AssetPrice) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *AssetPrice) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetTime

`func (o *AssetPrice) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *AssetPrice) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *AssetPrice) SetTime(v time.Time)`

SetTime sets Time field to given value.

### HasTime

`func (o *AssetPrice) HasTime() bool`

HasTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


