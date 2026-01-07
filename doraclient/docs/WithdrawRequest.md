# WithdrawRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PositionId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **string** |  | 

## Methods

### NewWithdrawRequest

`func NewWithdrawRequest(positionId string, assetId string, quantity string, ) *WithdrawRequest`

NewWithdrawRequest instantiates a new WithdrawRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawRequestWithDefaults

`func NewWithdrawRequestWithDefaults() *WithdrawRequest`

NewWithdrawRequestWithDefaults instantiates a new WithdrawRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPositionId

`func (o *WithdrawRequest) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *WithdrawRequest) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *WithdrawRequest) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetAssetId

`func (o *WithdrawRequest) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *WithdrawRequest) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *WithdrawRequest) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *WithdrawRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *WithdrawRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *WithdrawRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


