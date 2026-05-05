# AccountV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique identifier for the account. Used, for example, when creating an order from an account, or deciding collateral should be transferred from account A to account B. | 
**AssetId** | **string** |  | 
**Seq** | **int32** |  | 
**IsGlobal** | Pointer to **bool** |  | [optional] 
**Available** | **string** | The available balance in the account for this asset that are not locked, supplied, or used as collateral | 
**Locked** | **string** | The balance that has been reserved for a current order. If spent by the order, they are removed. If the order is cancelled, they are returned to the account&#39;s available balance. | 
**Supplied** | **string** | The balance that user has supplied to the leverage module. The user remains entitled to these assets and can withdraw them into their available balance. | 
**Borrowed** | **string** | The total amount of debt outstanding for this account. This account cannot be closed until all debt is fully repaid, i.e. borrowed &#x3D; 0. | 
**ImpendingBorrows** | **string** | The equivalent of locked balances, but for leveraged orders. If a user has an active order that would borrow assets as part of its input, then their borrow limit must be reduced until the order is executed or cancelled. | 
**AvgEntryPrice** | **string** | average cost per unit quantity that was paid (long accounts) or received (short accounts) for this asset. | 
**BorrowLimit** | **string** | The borrow limit | 
**LiquidationThreshold** | **string** | The borrow limit | 
**CreatedAt** | **time.Time** |  | 
**PendingWithdrawal** | **string** | The amount of asset that is pending withdrawal from the account. | 
**AccountName** | **string** |  | 

## Methods

### NewAccountV2

`func NewAccountV2(id string, assetId string, seq int32, available string, locked string, supplied string, borrowed string, impendingBorrows string, avgEntryPrice string, borrowLimit string, liquidationThreshold string, createdAt time.Time, pendingWithdrawal string, accountName string, ) *AccountV2`

NewAccountV2 instantiates a new AccountV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountV2WithDefaults

`func NewAccountV2WithDefaults() *AccountV2`

NewAccountV2WithDefaults instantiates a new AccountV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountV2) SetId(v string)`

SetId sets Id field to given value.


### GetAssetId

`func (o *AccountV2) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AccountV2) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AccountV2) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetSeq

`func (o *AccountV2) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *AccountV2) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *AccountV2) SetSeq(v int32)`

SetSeq sets Seq field to given value.


### GetIsGlobal

`func (o *AccountV2) GetIsGlobal() bool`

GetIsGlobal returns the IsGlobal field if non-nil, zero value otherwise.

### GetIsGlobalOk

`func (o *AccountV2) GetIsGlobalOk() (*bool, bool)`

GetIsGlobalOk returns a tuple with the IsGlobal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobal

`func (o *AccountV2) SetIsGlobal(v bool)`

SetIsGlobal sets IsGlobal field to given value.

### HasIsGlobal

`func (o *AccountV2) HasIsGlobal() bool`

HasIsGlobal returns a boolean if a field has been set.

### GetAvailable

`func (o *AccountV2) GetAvailable() string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *AccountV2) GetAvailableOk() (*string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *AccountV2) SetAvailable(v string)`

SetAvailable sets Available field to given value.


### GetLocked

`func (o *AccountV2) GetLocked() string`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *AccountV2) GetLockedOk() (*string, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *AccountV2) SetLocked(v string)`

SetLocked sets Locked field to given value.


### GetSupplied

`func (o *AccountV2) GetSupplied() string`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### GetSuppliedOk

`func (o *AccountV2) GetSuppliedOk() (*string, bool)`

GetSuppliedOk returns a tuple with the Supplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplied

`func (o *AccountV2) SetSupplied(v string)`

SetSupplied sets Supplied field to given value.


### GetBorrowed

`func (o *AccountV2) GetBorrowed() string`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *AccountV2) GetBorrowedOk() (*string, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *AccountV2) SetBorrowed(v string)`

SetBorrowed sets Borrowed field to given value.


### GetImpendingBorrows

`func (o *AccountV2) GetImpendingBorrows() string`

GetImpendingBorrows returns the ImpendingBorrows field if non-nil, zero value otherwise.

### GetImpendingBorrowsOk

`func (o *AccountV2) GetImpendingBorrowsOk() (*string, bool)`

GetImpendingBorrowsOk returns a tuple with the ImpendingBorrows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpendingBorrows

`func (o *AccountV2) SetImpendingBorrows(v string)`

SetImpendingBorrows sets ImpendingBorrows field to given value.


### GetAvgEntryPrice

`func (o *AccountV2) GetAvgEntryPrice() string`

GetAvgEntryPrice returns the AvgEntryPrice field if non-nil, zero value otherwise.

### GetAvgEntryPriceOk

`func (o *AccountV2) GetAvgEntryPriceOk() (*string, bool)`

GetAvgEntryPriceOk returns a tuple with the AvgEntryPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEntryPrice

`func (o *AccountV2) SetAvgEntryPrice(v string)`

SetAvgEntryPrice sets AvgEntryPrice field to given value.


### GetBorrowLimit

`func (o *AccountV2) GetBorrowLimit() string`

GetBorrowLimit returns the BorrowLimit field if non-nil, zero value otherwise.

### GetBorrowLimitOk

`func (o *AccountV2) GetBorrowLimitOk() (*string, bool)`

GetBorrowLimitOk returns a tuple with the BorrowLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowLimit

`func (o *AccountV2) SetBorrowLimit(v string)`

SetBorrowLimit sets BorrowLimit field to given value.


### GetLiquidationThreshold

`func (o *AccountV2) GetLiquidationThreshold() string`

GetLiquidationThreshold returns the LiquidationThreshold field if non-nil, zero value otherwise.

### GetLiquidationThresholdOk

`func (o *AccountV2) GetLiquidationThresholdOk() (*string, bool)`

GetLiquidationThresholdOk returns a tuple with the LiquidationThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationThreshold

`func (o *AccountV2) SetLiquidationThreshold(v string)`

SetLiquidationThreshold sets LiquidationThreshold field to given value.


### GetCreatedAt

`func (o *AccountV2) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AccountV2) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AccountV2) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetPendingWithdrawal

`func (o *AccountV2) GetPendingWithdrawal() string`

GetPendingWithdrawal returns the PendingWithdrawal field if non-nil, zero value otherwise.

### GetPendingWithdrawalOk

`func (o *AccountV2) GetPendingWithdrawalOk() (*string, bool)`

GetPendingWithdrawalOk returns a tuple with the PendingWithdrawal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingWithdrawal

`func (o *AccountV2) SetPendingWithdrawal(v string)`

SetPendingWithdrawal sets PendingWithdrawal field to given value.


### GetAccountName

`func (o *AccountV2) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *AccountV2) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *AccountV2) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


