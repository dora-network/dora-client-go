# NewIsolatedPositionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GlobalPositionId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **float64** |  | 
**PositionName** | Pointer to **string** |  | [optional] 

## Methods

### NewNewIsolatedPositionRequest

`func NewNewIsolatedPositionRequest(globalPositionId string, assetId string, quantity float64, ) *NewIsolatedPositionRequest`

NewNewIsolatedPositionRequest instantiates a new NewIsolatedPositionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNewIsolatedPositionRequestWithDefaults

`func NewNewIsolatedPositionRequestWithDefaults() *NewIsolatedPositionRequest`

NewNewIsolatedPositionRequestWithDefaults instantiates a new NewIsolatedPositionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGlobalPositionId

`func (o *NewIsolatedPositionRequest) GetGlobalPositionId() string`

GetGlobalPositionId returns the GlobalPositionId field if non-nil, zero value otherwise.

### GetGlobalPositionIdOk

`func (o *NewIsolatedPositionRequest) GetGlobalPositionIdOk() (*string, bool)`

GetGlobalPositionIdOk returns a tuple with the GlobalPositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalPositionId

`func (o *NewIsolatedPositionRequest) SetGlobalPositionId(v string)`

SetGlobalPositionId sets GlobalPositionId field to given value.


### GetAssetId

`func (o *NewIsolatedPositionRequest) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *NewIsolatedPositionRequest) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *NewIsolatedPositionRequest) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *NewIsolatedPositionRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *NewIsolatedPositionRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *NewIsolatedPositionRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.


### GetPositionName

`func (o *NewIsolatedPositionRequest) GetPositionName() string`

GetPositionName returns the PositionName field if non-nil, zero value otherwise.

### GetPositionNameOk

`func (o *NewIsolatedPositionRequest) GetPositionNameOk() (*string, bool)`

GetPositionNameOk returns a tuple with the PositionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionName

`func (o *NewIsolatedPositionRequest) SetPositionName(v string)`

SetPositionName sets PositionName field to given value.

### HasPositionName

`func (o *NewIsolatedPositionRequest) HasPositionName() bool`

HasPositionName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


