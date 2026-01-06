# UserValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | Pointer to **map[string]string** |  | [optional] 
**Locked** | Pointer to **map[string]string** |  | [optional] 
**Borrowed** | Pointer to **map[string]string** |  | [optional] 
**Supplied** | Pointer to **map[string]string** |  | [optional] 
**Collateral** | Pointer to **map[string]string** |  | [optional] 
**SuppliedCollateral** | Pointer to **map[string]string** |  | [optional] 
**ImpendingBorrows** | Pointer to **map[string]string** |  | [optional] 
**BorrowLimit** | Pointer to **map[string]string** |  | [optional] 
**LiquidationThreshold** | Pointer to **map[string]string** |  | [optional] 
**NotionalLong** | Pointer to **map[string]string** |  | [optional] 
**NotionalShort** | Pointer to **map[string]string** |  | [optional] 
**PortfolioValue** | Pointer to **map[string]string** |  | [optional] 
**NetLiquidationValue** | Pointer to **map[string]string** |  | [optional] 
**UnrealizedPnl** | Pointer to **map[string]string** |  | [optional] 
**RealizedPnl** | Pointer to **map[string]string** |  | [optional] 

## Methods

### NewUserValue

`func NewUserValue() *UserValue`

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

### HasAvailable

`func (o *UserValue) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

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

### HasLocked

`func (o *UserValue) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

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

### HasBorrowed

`func (o *UserValue) HasBorrowed() bool`

HasBorrowed returns a boolean if a field has been set.

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

### HasSupplied

`func (o *UserValue) HasSupplied() bool`

HasSupplied returns a boolean if a field has been set.

### GetCollateral

`func (o *UserValue) GetCollateral() map[string]string`

GetCollateral returns the Collateral field if non-nil, zero value otherwise.

### GetCollateralOk

`func (o *UserValue) GetCollateralOk() (*map[string]string, bool)`

GetCollateralOk returns a tuple with the Collateral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollateral

`func (o *UserValue) SetCollateral(v map[string]string)`

SetCollateral sets Collateral field to given value.

### HasCollateral

`func (o *UserValue) HasCollateral() bool`

HasCollateral returns a boolean if a field has been set.

### GetSuppliedCollateral

`func (o *UserValue) GetSuppliedCollateral() map[string]string`

GetSuppliedCollateral returns the SuppliedCollateral field if non-nil, zero value otherwise.

### GetSuppliedCollateralOk

`func (o *UserValue) GetSuppliedCollateralOk() (*map[string]string, bool)`

GetSuppliedCollateralOk returns a tuple with the SuppliedCollateral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppliedCollateral

`func (o *UserValue) SetSuppliedCollateral(v map[string]string)`

SetSuppliedCollateral sets SuppliedCollateral field to given value.

### HasSuppliedCollateral

`func (o *UserValue) HasSuppliedCollateral() bool`

HasSuppliedCollateral returns a boolean if a field has been set.

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

### HasImpendingBorrows

`func (o *UserValue) HasImpendingBorrows() bool`

HasImpendingBorrows returns a boolean if a field has been set.

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

### HasBorrowLimit

`func (o *UserValue) HasBorrowLimit() bool`

HasBorrowLimit returns a boolean if a field has been set.

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

### HasLiquidationThreshold

`func (o *UserValue) HasLiquidationThreshold() bool`

HasLiquidationThreshold returns a boolean if a field has been set.

### GetNotionalLong

`func (o *UserValue) GetNotionalLong() map[string]string`

GetNotionalLong returns the NotionalLong field if non-nil, zero value otherwise.

### GetNotionalLongOk

`func (o *UserValue) GetNotionalLongOk() (*map[string]string, bool)`

GetNotionalLongOk returns a tuple with the NotionalLong field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotionalLong

`func (o *UserValue) SetNotionalLong(v map[string]string)`

SetNotionalLong sets NotionalLong field to given value.

### HasNotionalLong

`func (o *UserValue) HasNotionalLong() bool`

HasNotionalLong returns a boolean if a field has been set.

### GetNotionalShort

`func (o *UserValue) GetNotionalShort() map[string]string`

GetNotionalShort returns the NotionalShort field if non-nil, zero value otherwise.

### GetNotionalShortOk

`func (o *UserValue) GetNotionalShortOk() (*map[string]string, bool)`

GetNotionalShortOk returns a tuple with the NotionalShort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotionalShort

`func (o *UserValue) SetNotionalShort(v map[string]string)`

SetNotionalShort sets NotionalShort field to given value.

### HasNotionalShort

`func (o *UserValue) HasNotionalShort() bool`

HasNotionalShort returns a boolean if a field has been set.

### GetPortfolioValue

`func (o *UserValue) GetPortfolioValue() map[string]string`

GetPortfolioValue returns the PortfolioValue field if non-nil, zero value otherwise.

### GetPortfolioValueOk

`func (o *UserValue) GetPortfolioValueOk() (*map[string]string, bool)`

GetPortfolioValueOk returns a tuple with the PortfolioValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortfolioValue

`func (o *UserValue) SetPortfolioValue(v map[string]string)`

SetPortfolioValue sets PortfolioValue field to given value.

### HasPortfolioValue

`func (o *UserValue) HasPortfolioValue() bool`

HasPortfolioValue returns a boolean if a field has been set.

### GetNetLiquidationValue

`func (o *UserValue) GetNetLiquidationValue() map[string]string`

GetNetLiquidationValue returns the NetLiquidationValue field if non-nil, zero value otherwise.

### GetNetLiquidationValueOk

`func (o *UserValue) GetNetLiquidationValueOk() (*map[string]string, bool)`

GetNetLiquidationValueOk returns a tuple with the NetLiquidationValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetLiquidationValue

`func (o *UserValue) SetNetLiquidationValue(v map[string]string)`

SetNetLiquidationValue sets NetLiquidationValue field to given value.

### HasNetLiquidationValue

`func (o *UserValue) HasNetLiquidationValue() bool`

HasNetLiquidationValue returns a boolean if a field has been set.

### GetUnrealizedPnl

`func (o *UserValue) GetUnrealizedPnl() map[string]string`

GetUnrealizedPnl returns the UnrealizedPnl field if non-nil, zero value otherwise.

### GetUnrealizedPnlOk

`func (o *UserValue) GetUnrealizedPnlOk() (*map[string]string, bool)`

GetUnrealizedPnlOk returns a tuple with the UnrealizedPnl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrealizedPnl

`func (o *UserValue) SetUnrealizedPnl(v map[string]string)`

SetUnrealizedPnl sets UnrealizedPnl field to given value.

### HasUnrealizedPnl

`func (o *UserValue) HasUnrealizedPnl() bool`

HasUnrealizedPnl returns a boolean if a field has been set.

### GetRealizedPnl

`func (o *UserValue) GetRealizedPnl() map[string]string`

GetRealizedPnl returns the RealizedPnl field if non-nil, zero value otherwise.

### GetRealizedPnlOk

`func (o *UserValue) GetRealizedPnlOk() (*map[string]string, bool)`

GetRealizedPnlOk returns a tuple with the RealizedPnl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealizedPnl

`func (o *UserValue) SetRealizedPnl(v map[string]string)`

SetRealizedPnl sets RealizedPnl field to given value.

### HasRealizedPnl

`func (o *UserValue) HasRealizedPnl() bool`

HasRealizedPnl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


