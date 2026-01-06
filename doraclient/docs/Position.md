# Position

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique identifier for the position. Used, for example, when creating an order from a position, or deciding collateral should be transferred from position A to position B. | [optional] 
**AssetId** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**IsGlobal** | Pointer to **bool** |  | [optional] 
**Available** | Pointer to **float64** | The available balance in the position for this asset that are not locked, supplied, or used as collateral | [optional] 
**Locked** | Pointer to **float64** | The balance that has been reserved for a current order. If spent by the order, they are removed. If the order is cancelled, they are returned to the position&#39;s available balance. | [optional] 
**Supplied** | Pointer to **float64** | The balance that user has supplied to the leverage module. The user remains entitled to these assets and can withdraw them into their available balance. | [optional] 
**Collateral** | Pointer to **float64** | The balance that has been locked or supplied, but are marked as collateral to support borrow limits and can be consumed in case of liquidation. When unmarked as collateral, the balance returns to the available balance. | [optional] 
**SuppliedCollateral** | Pointer to **float64** | The balance that have been supplied to the leverage module and marked as collateral. The user remains entitled to this balance and can withdraw it into the collateral balance, or unmark them as collateral and move them to the supplied balance. | [optional] 
**Borrowed** | Pointer to **float64** | The total amount of debt outstanding for this position. The position&#39;s collateral + supplied_collateral must support a borrow limit sufficient to cover all borrowed assets. This position cannot be closed until all debt is fully repaid, i.e. borrowed &#x3D; 0. | [optional] 
**ImpendingBorrows** | Pointer to **float64** | The equivalent of locked balances, but for leveraged orders. If a user has an active order that would borrow assets as part of its input, then their borrow limit must be reduced until the order is executed or cancelled. | [optional] 
**AvgEntryPrice** | Pointer to **float64** | average cost per unit quantity that was paid (long positions) or received (short positions) for this asset. | [optional] 
**BorrowLimit** | Pointer to **float64** | The borrow limit | [optional] 
**LiquidationThreshold** | Pointer to **float64** | The borrow limit | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**PositionName** | Pointer to **string** |  | [optional] 

## Methods

### NewPosition

`func NewPosition() *Position`

NewPosition instantiates a new Position object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPositionWithDefaults

`func NewPositionWithDefaults() *Position`

NewPositionWithDefaults instantiates a new Position object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Position) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Position) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Position) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Position) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAssetId

`func (o *Position) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *Position) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *Position) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.

### HasAssetId

`func (o *Position) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

### GetSeq

`func (o *Position) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *Position) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *Position) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *Position) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

### GetIsGlobal

`func (o *Position) GetIsGlobal() bool`

GetIsGlobal returns the IsGlobal field if non-nil, zero value otherwise.

### GetIsGlobalOk

`func (o *Position) GetIsGlobalOk() (*bool, bool)`

GetIsGlobalOk returns a tuple with the IsGlobal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobal

`func (o *Position) SetIsGlobal(v bool)`

SetIsGlobal sets IsGlobal field to given value.

### HasIsGlobal

`func (o *Position) HasIsGlobal() bool`

HasIsGlobal returns a boolean if a field has been set.

### GetAvailable

`func (o *Position) GetAvailable() float64`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *Position) GetAvailableOk() (*float64, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *Position) SetAvailable(v float64)`

SetAvailable sets Available field to given value.

### HasAvailable

`func (o *Position) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

### GetLocked

`func (o *Position) GetLocked() float64`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *Position) GetLockedOk() (*float64, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *Position) SetLocked(v float64)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *Position) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetSupplied

`func (o *Position) GetSupplied() float64`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### GetSuppliedOk

`func (o *Position) GetSuppliedOk() (*float64, bool)`

GetSuppliedOk returns a tuple with the Supplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplied

`func (o *Position) SetSupplied(v float64)`

SetSupplied sets Supplied field to given value.

### HasSupplied

`func (o *Position) HasSupplied() bool`

HasSupplied returns a boolean if a field has been set.

### GetCollateral

`func (o *Position) GetCollateral() float64`

GetCollateral returns the Collateral field if non-nil, zero value otherwise.

### GetCollateralOk

`func (o *Position) GetCollateralOk() (*float64, bool)`

GetCollateralOk returns a tuple with the Collateral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollateral

`func (o *Position) SetCollateral(v float64)`

SetCollateral sets Collateral field to given value.

### HasCollateral

`func (o *Position) HasCollateral() bool`

HasCollateral returns a boolean if a field has been set.

### GetSuppliedCollateral

`func (o *Position) GetSuppliedCollateral() float64`

GetSuppliedCollateral returns the SuppliedCollateral field if non-nil, zero value otherwise.

### GetSuppliedCollateralOk

`func (o *Position) GetSuppliedCollateralOk() (*float64, bool)`

GetSuppliedCollateralOk returns a tuple with the SuppliedCollateral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppliedCollateral

`func (o *Position) SetSuppliedCollateral(v float64)`

SetSuppliedCollateral sets SuppliedCollateral field to given value.

### HasSuppliedCollateral

`func (o *Position) HasSuppliedCollateral() bool`

HasSuppliedCollateral returns a boolean if a field has been set.

### GetBorrowed

`func (o *Position) GetBorrowed() float64`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *Position) GetBorrowedOk() (*float64, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *Position) SetBorrowed(v float64)`

SetBorrowed sets Borrowed field to given value.

### HasBorrowed

`func (o *Position) HasBorrowed() bool`

HasBorrowed returns a boolean if a field has been set.

### GetImpendingBorrows

`func (o *Position) GetImpendingBorrows() float64`

GetImpendingBorrows returns the ImpendingBorrows field if non-nil, zero value otherwise.

### GetImpendingBorrowsOk

`func (o *Position) GetImpendingBorrowsOk() (*float64, bool)`

GetImpendingBorrowsOk returns a tuple with the ImpendingBorrows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpendingBorrows

`func (o *Position) SetImpendingBorrows(v float64)`

SetImpendingBorrows sets ImpendingBorrows field to given value.

### HasImpendingBorrows

`func (o *Position) HasImpendingBorrows() bool`

HasImpendingBorrows returns a boolean if a field has been set.

### GetAvgEntryPrice

`func (o *Position) GetAvgEntryPrice() float64`

GetAvgEntryPrice returns the AvgEntryPrice field if non-nil, zero value otherwise.

### GetAvgEntryPriceOk

`func (o *Position) GetAvgEntryPriceOk() (*float64, bool)`

GetAvgEntryPriceOk returns a tuple with the AvgEntryPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEntryPrice

`func (o *Position) SetAvgEntryPrice(v float64)`

SetAvgEntryPrice sets AvgEntryPrice field to given value.

### HasAvgEntryPrice

`func (o *Position) HasAvgEntryPrice() bool`

HasAvgEntryPrice returns a boolean if a field has been set.

### GetBorrowLimit

`func (o *Position) GetBorrowLimit() float64`

GetBorrowLimit returns the BorrowLimit field if non-nil, zero value otherwise.

### GetBorrowLimitOk

`func (o *Position) GetBorrowLimitOk() (*float64, bool)`

GetBorrowLimitOk returns a tuple with the BorrowLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowLimit

`func (o *Position) SetBorrowLimit(v float64)`

SetBorrowLimit sets BorrowLimit field to given value.

### HasBorrowLimit

`func (o *Position) HasBorrowLimit() bool`

HasBorrowLimit returns a boolean if a field has been set.

### GetLiquidationThreshold

`func (o *Position) GetLiquidationThreshold() float64`

GetLiquidationThreshold returns the LiquidationThreshold field if non-nil, zero value otherwise.

### GetLiquidationThresholdOk

`func (o *Position) GetLiquidationThresholdOk() (*float64, bool)`

GetLiquidationThresholdOk returns a tuple with the LiquidationThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationThreshold

`func (o *Position) SetLiquidationThreshold(v float64)`

SetLiquidationThreshold sets LiquidationThreshold field to given value.

### HasLiquidationThreshold

`func (o *Position) HasLiquidationThreshold() bool`

HasLiquidationThreshold returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Position) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Position) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Position) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Position) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetPositionName

`func (o *Position) GetPositionName() string`

GetPositionName returns the PositionName field if non-nil, zero value otherwise.

### GetPositionNameOk

`func (o *Position) GetPositionNameOk() (*string, bool)`

GetPositionNameOk returns a tuple with the PositionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionName

`func (o *Position) SetPositionName(v string)`

SetPositionName sets PositionName field to given value.

### HasPositionName

`func (o *Position) HasPositionName() bool`

HasPositionName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


