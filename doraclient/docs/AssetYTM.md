# AssetYTM

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**CurrentTime** | **time.Time** |  | 
**CurrentPrice** | **string** |  | 
**YieldToMaturity** | **string** |  | 

## Methods

### NewAssetYTM

`func NewAssetYTM(assetId string, currentTime time.Time, currentPrice string, yieldToMaturity string, ) *AssetYTM`

NewAssetYTM instantiates a new AssetYTM object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetYTMWithDefaults

`func NewAssetYTMWithDefaults() *AssetYTM`

NewAssetYTMWithDefaults instantiates a new AssetYTM object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetYTM) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetYTM) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetYTM) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetCurrentTime

`func (o *AssetYTM) GetCurrentTime() time.Time`

GetCurrentTime returns the CurrentTime field if non-nil, zero value otherwise.

### GetCurrentTimeOk

`func (o *AssetYTM) GetCurrentTimeOk() (*time.Time, bool)`

GetCurrentTimeOk returns a tuple with the CurrentTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentTime

`func (o *AssetYTM) SetCurrentTime(v time.Time)`

SetCurrentTime sets CurrentTime field to given value.


### GetCurrentPrice

`func (o *AssetYTM) GetCurrentPrice() string`

GetCurrentPrice returns the CurrentPrice field if non-nil, zero value otherwise.

### GetCurrentPriceOk

`func (o *AssetYTM) GetCurrentPriceOk() (*string, bool)`

GetCurrentPriceOk returns a tuple with the CurrentPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPrice

`func (o *AssetYTM) SetCurrentPrice(v string)`

SetCurrentPrice sets CurrentPrice field to given value.


### GetYieldToMaturity

`func (o *AssetYTM) GetYieldToMaturity() string`

GetYieldToMaturity returns the YieldToMaturity field if non-nil, zero value otherwise.

### GetYieldToMaturityOk

`func (o *AssetYTM) GetYieldToMaturityOk() (*string, bool)`

GetYieldToMaturityOk returns a tuple with the YieldToMaturity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYieldToMaturity

`func (o *AssetYTM) SetYieldToMaturity(v string)`

SetYieldToMaturity sets YieldToMaturity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


