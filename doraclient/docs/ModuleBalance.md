# ModuleBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Seq** | **int32** |  | 
**Available** | **string** | The available balance in the module for this asset | 
**Supplied** | **string** | The total amount supplied to the module for this asset | 
**Virtual** | **string** | Assets minted by virtual-borrowing, but not yet repaid | 
**Borrowed** | **string** | The total amount borrowed from the supplied but not yet repaid | 

## Methods

### NewModuleBalance

`func NewModuleBalance(assetId string, seq int32, available string, supplied string, virtual string, borrowed string, ) *ModuleBalance`

NewModuleBalance instantiates a new ModuleBalance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModuleBalanceWithDefaults

`func NewModuleBalanceWithDefaults() *ModuleBalance`

NewModuleBalanceWithDefaults instantiates a new ModuleBalance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *ModuleBalance) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *ModuleBalance) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *ModuleBalance) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetSeq

`func (o *ModuleBalance) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ModuleBalance) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ModuleBalance) SetSeq(v int32)`

SetSeq sets Seq field to given value.


### GetAvailable

`func (o *ModuleBalance) GetAvailable() string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *ModuleBalance) GetAvailableOk() (*string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *ModuleBalance) SetAvailable(v string)`

SetAvailable sets Available field to given value.


### GetSupplied

`func (o *ModuleBalance) GetSupplied() string`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### GetSuppliedOk

`func (o *ModuleBalance) GetSuppliedOk() (*string, bool)`

GetSuppliedOk returns a tuple with the Supplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplied

`func (o *ModuleBalance) SetSupplied(v string)`

SetSupplied sets Supplied field to given value.


### GetVirtual

`func (o *ModuleBalance) GetVirtual() string`

GetVirtual returns the Virtual field if non-nil, zero value otherwise.

### GetVirtualOk

`func (o *ModuleBalance) GetVirtualOk() (*string, bool)`

GetVirtualOk returns a tuple with the Virtual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtual

`func (o *ModuleBalance) SetVirtual(v string)`

SetVirtual sets Virtual field to given value.


### GetBorrowed

`func (o *ModuleBalance) GetBorrowed() string`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *ModuleBalance) GetBorrowedOk() (*string, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *ModuleBalance) SetBorrowed(v string)`

SetBorrowed sets Borrowed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


