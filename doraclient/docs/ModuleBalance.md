# ModuleBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**Available** | Pointer to **string** | The available balance in the module for this asset | [optional] 
**Supplied** | Pointer to **string** | The total amount supplied to the module for this asset | [optional] 
**Virtual** | Pointer to **string** | Assets minted by virtual-borrowing, but not yet repaid | [optional] 
**Borrowed** | Pointer to **string** | The total amount borrowed from the supplied but not yet repaid | [optional] 

## Methods

### NewModuleBalance

`func NewModuleBalance() *ModuleBalance`

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

### HasAssetId

`func (o *ModuleBalance) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

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

### HasSeq

`func (o *ModuleBalance) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

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

### HasAvailable

`func (o *ModuleBalance) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

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

### HasSupplied

`func (o *ModuleBalance) HasSupplied() bool`

HasSupplied returns a boolean if a field has been set.

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

### HasVirtual

`func (o *ModuleBalance) HasVirtual() bool`

HasVirtual returns a boolean if a field has been set.

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

### HasBorrowed

`func (o *ModuleBalance) HasBorrowed() bool`

HasBorrowed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


