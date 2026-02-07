# UserValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **map[string]string** |  | 
**Locked** | **map[string]string** |  | 
**Borrowed** | **map[string]string** |  | 
**Supplied** | **map[string]string** |  | 
**ImpendingBorrows** | **map[string]string** |  | 
**BorrowLimit** | **map[string]string** |  | 
**LiquidationThreshold** | **map[string]string** |  | 

## Methods

### NewUserValue

`func NewUserValue(available map[string]string, locked map[string]string, borrowed map[string]string, supplied map[string]string, impendingBorrows map[string]string, borrowLimit map[string]string, liquidationThreshold map[string]string, ) *UserValue`

NewUserValue instantiates a new UserValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserValueWithDefaults

`func NewUserValueWithDefaults() *UserValue`

NewUserValueWithDefaults instantiates a new UserValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *UserValue) GetAvailable() map[string]string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *UserValue) GetAvailableOk() (*map[string]string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *UserValue) SetAvailable(v map[string]string)`

SetAvailable sets Available field to given value.


### GetLocked

`func (o *UserValue) GetLocked() map[string]string`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *UserValue) GetLockedOk() (*map[string]string, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *UserValue) SetLocked(v map[string]string)`

SetLocked sets Locked field to given value.


### GetBorrowed

`func (o *UserValue) GetBorrowed() map[string]string`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *UserValue) GetBorrowedOk() (*map[string]string, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *UserValue) SetBorrowed(v map[string]string)`

SetBorrowed sets Borrowed field to given value.


### GetSupplied

`func (o *UserValue) GetSupplied() map[string]string`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### GetSuppliedOk

`func (o *UserValue) GetSuppliedOk() (*map[string]string, bool)`

GetSuppliedOk returns a tuple with the Supplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplied

`func (o *UserValue) SetSupplied(v map[string]string)`

SetSupplied sets Supplied field to given value.


### GetImpendingBorrows

`func (o *UserValue) GetImpendingBorrows() map[string]string`

GetImpendingBorrows returns the ImpendingBorrows field if non-nil, zero value otherwise.

### GetImpendingBorrowsOk

`func (o *UserValue) GetImpendingBorrowsOk() (*map[string]string, bool)`

GetImpendingBorrowsOk returns a tuple with the ImpendingBorrows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpendingBorrows

`func (o *UserValue) SetImpendingBorrows(v map[string]string)`

SetImpendingBorrows sets ImpendingBorrows field to given value.


### GetBorrowLimit

`func (o *UserValue) GetBorrowLimit() map[string]string`

GetBorrowLimit returns the BorrowLimit field if non-nil, zero value otherwise.

### GetBorrowLimitOk

`func (o *UserValue) GetBorrowLimitOk() (*map[string]string, bool)`

GetBorrowLimitOk returns a tuple with the BorrowLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowLimit

`func (o *UserValue) SetBorrowLimit(v map[string]string)`

SetBorrowLimit sets BorrowLimit field to given value.


### GetLiquidationThreshold

`func (o *UserValue) GetLiquidationThreshold() map[string]string`

GetLiquidationThreshold returns the LiquidationThreshold field if non-nil, zero value otherwise.

### GetLiquidationThresholdOk

`func (o *UserValue) GetLiquidationThresholdOk() (*map[string]string, bool)`

GetLiquidationThresholdOk returns a tuple with the LiquidationThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationThreshold

`func (o *UserValue) SetLiquidationThreshold(v map[string]string)`

SetLiquidationThreshold sets LiquidationThreshold field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


