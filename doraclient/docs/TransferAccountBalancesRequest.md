# TransferAccountBalancesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromAccountId** | **string** |  | 
**ToAccountId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **string** |  | 

## Methods

### NewTransferAccountBalancesRequest

`func NewTransferAccountBalancesRequest(fromAccountId string, toAccountId string, assetId string, quantity string, ) *TransferAccountBalancesRequest`

NewTransferAccountBalancesRequest instantiates a new TransferAccountBalancesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransferAccountBalancesRequestWithDefaults

`func NewTransferAccountBalancesRequestWithDefaults() *TransferAccountBalancesRequest`

NewTransferAccountBalancesRequestWithDefaults instantiates a new TransferAccountBalancesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromAccountId

`func (o *TransferAccountBalancesRequest) GetFromAccountId() string`

GetFromAccountId returns the FromAccountId field if non-nil, zero value otherwise.

### GetFromAccountIdOk

`func (o *TransferAccountBalancesRequest) GetFromAccountIdOk() (*string, bool)`

GetFromAccountIdOk returns a tuple with the FromAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromAccountId

`func (o *TransferAccountBalancesRequest) SetFromAccountId(v string)`

SetFromAccountId sets FromAccountId field to given value.


### GetToAccountId

`func (o *TransferAccountBalancesRequest) GetToAccountId() string`

GetToAccountId returns the ToAccountId field if non-nil, zero value otherwise.

### GetToAccountIdOk

`func (o *TransferAccountBalancesRequest) GetToAccountIdOk() (*string, bool)`

GetToAccountIdOk returns a tuple with the ToAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToAccountId

`func (o *TransferAccountBalancesRequest) SetToAccountId(v string)`

SetToAccountId sets ToAccountId field to given value.


### GetAssetId

`func (o *TransferAccountBalancesRequest) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *TransferAccountBalancesRequest) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *TransferAccountBalancesRequest) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *TransferAccountBalancesRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *TransferAccountBalancesRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *TransferAccountBalancesRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


