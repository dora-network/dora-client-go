# ModuleBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**Available** | Pointer to **float64** | The available balance in the module for this asset | [optional] 
**Supplied** | Pointer to **float64** | The total amount supplied to the module for this asset | [optional] 
**SuppliedCollateral** | Pointer to **float64** | The amount supplied as collateral from user balances in the module for this asset | [optional] 
**Virtual** | Pointer to **float64** | Assets minted by virtual-borrowing, but not yet repaid | [optional] 
**Borrowed** | Pointer to **float64** | The total amount borrowed from the supplied but not yet repaid | [optional] 

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

`func (o *ModuleBalance) GetAvailable() float64`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *ModuleBalance) GetAvailableOk() (*float64, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *ModuleBalance) SetAvailable(v float64)`

SetAvailable sets Available field to given value.

### HasAvailable

`func (o *ModuleBalance) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

### GetSupplied

`func (o *ModuleBalance) GetSupplied() float64`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### GetSuppliedOk

`func (o *ModuleBalance) GetSuppliedOk() (*float64, bool)`

GetSuppliedOk returns a tuple with the Supplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplied

`func (o *ModuleBalance) SetSupplied(v float64)`

SetSupplied sets Supplied field to given value.

### HasSupplied

`func (o *ModuleBalance) HasSupplied() bool`

HasSupplied returns a boolean if a field has been set.

### GetSuppliedCollateral

`func (o *ModuleBalance) GetSuppliedCollateral() float64`

GetSuppliedCollateral returns the SuppliedCollateral field if non-nil, zero value otherwise.

### GetSuppliedCollateralOk

`func (o *ModuleBalance) GetSuppliedCollateralOk() (*float64, bool)`

GetSuppliedCollateralOk returns a tuple with the SuppliedCollateral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppliedCollateral

`func (o *ModuleBalance) SetSuppliedCollateral(v float64)`

SetSuppliedCollateral sets SuppliedCollateral field to given value.

### HasSuppliedCollateral

`func (o *ModuleBalance) HasSuppliedCollateral() bool`

HasSuppliedCollateral returns a boolean if a field has been set.

### GetVirtual

`func (o *ModuleBalance) GetVirtual() float64`

GetVirtual returns the Virtual field if non-nil, zero value otherwise.

### GetVirtualOk

`func (o *ModuleBalance) GetVirtualOk() (*float64, bool)`

GetVirtualOk returns a tuple with the Virtual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtual

`func (o *ModuleBalance) SetVirtual(v float64)`

SetVirtual sets Virtual field to given value.

### HasVirtual

`func (o *ModuleBalance) HasVirtual() bool`

HasVirtual returns a boolean if a field has been set.

### GetBorrowed

`func (o *ModuleBalance) GetBorrowed() float64`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *ModuleBalance) GetBorrowedOk() (*float64, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *ModuleBalance) SetBorrowed(v float64)`

SetBorrowed sets Borrowed field to given value.

### HasBorrowed

`func (o *ModuleBalance) HasBorrowed() bool`

HasBorrowed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


