# Position

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique identifier for the position. Used, for example, when creating an order from a position, or deciding collateral should be transferred from position A to position B. | 
**AssetId** | **string** |  | 
**Seq** | **int32** |  | 
**IsGlobal** | Pointer to **bool** |  | [optional] 
**Available** | **string** | The available balance in the position for this asset that are not locked, supplied, or used as collateral | 
**Locked** | **string** | The balance that has been reserved for a current order. If spent by the order, they are removed. If the order is cancelled, they are returned to the position&#39;s available balance. | 
**Supplied** | **string** | The balance that user has supplied to the leverage module. The user remains entitled to these assets and can withdraw them into their available balance. | 
**Borrowed** | **string** | The total amount of debt outstanding for this position. This position cannot be closed until all debt is fully repaid, i.e. borrowed &#x3D; 0. | 
**ImpendingBorrows** | **string** | The equivalent of locked balances, but for leveraged orders. If a user has an active order that would borrow assets as part of its input, then their borrow limit must be reduced until the order is executed or cancelled. | 
**AvgEntryPrice** | **string** | average cost per unit quantity that was paid (long positions) or received (short positions) for this asset. | 
**BorrowLimit** | **string** | The borrow limit | 
**LiquidationThreshold** | **string** | The borrow limit | 
**CreatedAt** | **time.Time** |  | 
**PositionName** | **string** |  | 
**PendingWithdrawal** | **string** | The amount of asset that is pending withdrawal from the position. | 

## Methods

### NewPosition

`func NewPosition(id string, assetId string, seq int32, available string, locked string, supplied string, borrowed string, impendingBorrows string, avgEntryPrice string, borrowLimit string, liquidationThreshold string, createdAt time.Time, positionName string, pendingWithdrawal string, ) *Position`

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

`func (o *Position) GetAvailable() string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *Position) GetAvailableOk() (*string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *Position) SetAvailable(v string)`

SetAvailable sets Available field to given value.


### GetLocked

`func (o *Position) GetLocked() string`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *Position) GetLockedOk() (*string, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *Position) SetLocked(v string)`

SetLocked sets Locked field to given value.


### GetSupplied

`func (o *Position) GetSupplied() string`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### GetSuppliedOk

`func (o *Position) GetSuppliedOk() (*string, bool)`

GetSuppliedOk returns a tuple with the Supplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplied

`func (o *Position) SetSupplied(v string)`

SetSupplied sets Supplied field to given value.


### GetBorrowed

`func (o *Position) GetBorrowed() string`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *Position) GetBorrowedOk() (*string, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *Position) SetBorrowed(v string)`

SetBorrowed sets Borrowed field to given value.


### GetImpendingBorrows

`func (o *Position) GetImpendingBorrows() string`

GetImpendingBorrows returns the ImpendingBorrows field if non-nil, zero value otherwise.

### GetImpendingBorrowsOk

`func (o *Position) GetImpendingBorrowsOk() (*string, bool)`

GetImpendingBorrowsOk returns a tuple with the ImpendingBorrows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpendingBorrows

`func (o *Position) SetImpendingBorrows(v string)`

SetImpendingBorrows sets ImpendingBorrows field to given value.


### GetAvgEntryPrice

`func (o *Position) GetAvgEntryPrice() string`

GetAvgEntryPrice returns the AvgEntryPrice field if non-nil, zero value otherwise.

### GetAvgEntryPriceOk

`func (o *Position) GetAvgEntryPriceOk() (*string, bool)`

GetAvgEntryPriceOk returns a tuple with the AvgEntryPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEntryPrice

`func (o *Position) SetAvgEntryPrice(v string)`

SetAvgEntryPrice sets AvgEntryPrice field to given value.


### GetBorrowLimit

`func (o *Position) GetBorrowLimit() string`

GetBorrowLimit returns the BorrowLimit field if non-nil, zero value otherwise.

### GetBorrowLimitOk

`func (o *Position) GetBorrowLimitOk() (*string, bool)`

GetBorrowLimitOk returns a tuple with the BorrowLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowLimit

`func (o *Position) SetBorrowLimit(v string)`

SetBorrowLimit sets BorrowLimit field to given value.


### GetLiquidationThreshold

`func (o *Position) GetLiquidationThreshold() string`

GetLiquidationThreshold returns the LiquidationThreshold field if non-nil, zero value otherwise.

### GetLiquidationThresholdOk

`func (o *Position) GetLiquidationThresholdOk() (*string, bool)`

GetLiquidationThresholdOk returns a tuple with the LiquidationThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationThreshold

`func (o *Position) SetLiquidationThreshold(v string)`

SetLiquidationThreshold sets LiquidationThreshold field to given value.


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


### GetPendingWithdrawal

`func (o *Position) GetPendingWithdrawal() string`

GetPendingWithdrawal returns the PendingWithdrawal field if non-nil, zero value otherwise.

### GetPendingWithdrawalOk

`func (o *Position) GetPendingWithdrawalOk() (*string, bool)`

GetPendingWithdrawalOk returns a tuple with the PendingWithdrawal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingWithdrawal

`func (o *Position) SetPendingWithdrawal(v string)`

SetPendingWithdrawal sets PendingWithdrawal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


