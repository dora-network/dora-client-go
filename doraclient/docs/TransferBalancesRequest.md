# TransferBalancesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromPositionId** | **string** |  | 
**ToPositionId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **string** |  | 

## Methods

### NewTransferBalancesRequest

`func NewTransferBalancesRequest(fromPositionId string, toPositionId string, assetId string, quantity string, ) *TransferBalancesRequest`

NewTransferBalancesRequest instantiates a new TransferBalancesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransferBalancesRequestWithDefaults

`func NewTransferBalancesRequestWithDefaults() *TransferBalancesRequest`

NewTransferBalancesRequestWithDefaults instantiates a new TransferBalancesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromPositionId

`func (o *TransferBalancesRequest) GetFromPositionId() string`

GetFromPositionId returns the FromPositionId field if non-nil, zero value otherwise.

### GetFromPositionIdOk

`func (o *TransferBalancesRequest) GetFromPositionIdOk() (*string, bool)`

GetFromPositionIdOk returns a tuple with the FromPositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromPositionId

`func (o *TransferBalancesRequest) SetFromPositionId(v string)`

SetFromPositionId sets FromPositionId field to given value.


### GetToPositionId

`func (o *TransferBalancesRequest) GetToPositionId() string`

GetToPositionId returns the ToPositionId field if non-nil, zero value otherwise.

### GetToPositionIdOk

`func (o *TransferBalancesRequest) GetToPositionIdOk() (*string, bool)`

GetToPositionIdOk returns a tuple with the ToPositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToPositionId

`func (o *TransferBalancesRequest) SetToPositionId(v string)`

SetToPositionId sets ToPositionId field to given value.


### GetAssetId

`func (o *TransferBalancesRequest) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *TransferBalancesRequest) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *TransferBalancesRequest) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *TransferBalancesRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *TransferBalancesRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *TransferBalancesRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


