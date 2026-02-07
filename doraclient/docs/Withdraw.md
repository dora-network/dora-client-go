# Withdraw

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PositionId** | **string** |  | 
**TransactionId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **string** |  | 

## Methods

### NewWithdraw

`func NewWithdraw(positionId string, transactionId string, assetId string, quantity string, ) *Withdraw`

NewWithdraw instantiates a new Withdraw object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawWithDefaults

`func NewWithdrawWithDefaults() *Withdraw`

NewWithdrawWithDefaults instantiates a new Withdraw object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPositionId

`func (o *Withdraw) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *Withdraw) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *Withdraw) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetTransactionId

`func (o *Withdraw) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *Withdraw) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *Withdraw) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetAssetId

`func (o *Withdraw) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *Withdraw) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *Withdraw) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *Withdraw) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *Withdraw) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *Withdraw) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


