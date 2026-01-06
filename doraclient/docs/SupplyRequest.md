# SupplyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PositionId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **float64** |  | 

## Methods

### NewSupplyRequest

`func NewSupplyRequest(positionId string, assetId string, quantity float64, ) *SupplyRequest`

NewSupplyRequest instantiates a new SupplyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplyRequestWithDefaults

`func NewSupplyRequestWithDefaults() *SupplyRequest`

NewSupplyRequestWithDefaults instantiates a new SupplyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPositionId

`func (o *SupplyRequest) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *SupplyRequest) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *SupplyRequest) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetAssetId

`func (o *SupplyRequest) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *SupplyRequest) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *SupplyRequest) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *SupplyRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SupplyRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SupplyRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


