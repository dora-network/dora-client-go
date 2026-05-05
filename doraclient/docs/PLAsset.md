# PLAsset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The ID of the asset | 
**Kind** | [**AssetKind**](AssetKind.md) |  | 
**Symbol** | **string** | The symbol of the asset | 
**Side** | **string** | The side of the position (LONG or SHORT) | 
**AvgEntryPrice** | **string** | The average entry price of the position | 
**MarkPrice** | **string** | The current mark price for the asset to calculate daily PL. This is usually the close price of the previous day | 
**LiquidationPrice** | **string** | The liquidation price of the position | 
**Available** | **string** | The available quantity in units of the asset | 
**Borrowed** | **string** | The borrowed quantity in units of the asset | 
**Margin** | [**Margin**](Margin.md) |  | 
**UnrealizedPl** | **string** | The unrealized profit or loss of the position | 
**LeverageLimit** | **string** | The leverage limit for the position | 
**Tp** | Pointer to **string** | The take profit price set for the position, if any | [optional] 
**Sl** | Pointer to **string** | The stop loss price set for the position, if any | [optional] 
**InitialCapital** | **string** | The initial capital of the position | 
**ImpendingBorrows** | Pointer to **string** | The impending borrows of the position | [optional] 
**Locked** | **string** | The locked amount of the position | 
**UnusedCollateral** | **string** | The unused collateral of the position | 

## Methods

### NewPLAsset

`func NewPLAsset(id string, kind AssetKind, symbol string, side string, avgEntryPrice string, markPrice string, liquidationPrice string, available string, borrowed string, margin Margin, unrealizedPl string, leverageLimit string, initialCapital string, locked string, unusedCollateral string, ) *PLAsset`

NewPLAsset instantiates a new PLAsset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPLAssetWithDefaults

`func NewPLAssetWithDefaults() *PLAsset`

NewPLAssetWithDefaults instantiates a new PLAsset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PLAsset) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PLAsset) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PLAsset) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *PLAsset) GetKind() AssetKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PLAsset) GetKindOk() (*AssetKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PLAsset) SetKind(v AssetKind)`

SetKind sets Kind field to given value.


### GetSymbol

`func (o *PLAsset) GetSymbol() string`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *PLAsset) GetSymbolOk() (*string, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *PLAsset) SetSymbol(v string)`

SetSymbol sets Symbol field to given value.


### GetSide

`func (o *PLAsset) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *PLAsset) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *PLAsset) SetSide(v string)`

SetSide sets Side field to given value.


### GetAvgEntryPrice

`func (o *PLAsset) GetAvgEntryPrice() string`

GetAvgEntryPrice returns the AvgEntryPrice field if non-nil, zero value otherwise.

### GetAvgEntryPriceOk

`func (o *PLAsset) GetAvgEntryPriceOk() (*string, bool)`

GetAvgEntryPriceOk returns a tuple with the AvgEntryPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEntryPrice

`func (o *PLAsset) SetAvgEntryPrice(v string)`

SetAvgEntryPrice sets AvgEntryPrice field to given value.


### GetMarkPrice

`func (o *PLAsset) GetMarkPrice() string`

GetMarkPrice returns the MarkPrice field if non-nil, zero value otherwise.

### GetMarkPriceOk

`func (o *PLAsset) GetMarkPriceOk() (*string, bool)`

GetMarkPriceOk returns a tuple with the MarkPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkPrice

`func (o *PLAsset) SetMarkPrice(v string)`

SetMarkPrice sets MarkPrice field to given value.


### GetLiquidationPrice

`func (o *PLAsset) GetLiquidationPrice() string`

GetLiquidationPrice returns the LiquidationPrice field if non-nil, zero value otherwise.

### GetLiquidationPriceOk

`func (o *PLAsset) GetLiquidationPriceOk() (*string, bool)`

GetLiquidationPriceOk returns a tuple with the LiquidationPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationPrice

`func (o *PLAsset) SetLiquidationPrice(v string)`

SetLiquidationPrice sets LiquidationPrice field to given value.


### GetAvailable

`func (o *PLAsset) GetAvailable() string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *PLAsset) GetAvailableOk() (*string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *PLAsset) SetAvailable(v string)`

SetAvailable sets Available field to given value.


### GetBorrowed

`func (o *PLAsset) GetBorrowed() string`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *PLAsset) GetBorrowedOk() (*string, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *PLAsset) SetBorrowed(v string)`

SetBorrowed sets Borrowed field to given value.


### GetMargin

`func (o *PLAsset) GetMargin() Margin`

GetMargin returns the Margin field if non-nil, zero value otherwise.

### GetMarginOk

`func (o *PLAsset) GetMarginOk() (*Margin, bool)`

GetMarginOk returns a tuple with the Margin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin

`func (o *PLAsset) SetMargin(v Margin)`

SetMargin sets Margin field to given value.


### GetUnrealizedPl

`func (o *PLAsset) GetUnrealizedPl() string`

GetUnrealizedPl returns the UnrealizedPl field if non-nil, zero value otherwise.

### GetUnrealizedPlOk

`func (o *PLAsset) GetUnrealizedPlOk() (*string, bool)`

GetUnrealizedPlOk returns a tuple with the UnrealizedPl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrealizedPl

`func (o *PLAsset) SetUnrealizedPl(v string)`

SetUnrealizedPl sets UnrealizedPl field to given value.


### GetLeverageLimit

`func (o *PLAsset) GetLeverageLimit() string`

GetLeverageLimit returns the LeverageLimit field if non-nil, zero value otherwise.

### GetLeverageLimitOk

`func (o *PLAsset) GetLeverageLimitOk() (*string, bool)`

GetLeverageLimitOk returns a tuple with the LeverageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeverageLimit

`func (o *PLAsset) SetLeverageLimit(v string)`

SetLeverageLimit sets LeverageLimit field to given value.


### GetTp

`func (o *PLAsset) GetTp() string`

GetTp returns the Tp field if non-nil, zero value otherwise.

### GetTpOk

`func (o *PLAsset) GetTpOk() (*string, bool)`

GetTpOk returns a tuple with the Tp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTp

`func (o *PLAsset) SetTp(v string)`

SetTp sets Tp field to given value.

### HasTp

`func (o *PLAsset) HasTp() bool`

HasTp returns a boolean if a field has been set.

### GetSl

`func (o *PLAsset) GetSl() string`

GetSl returns the Sl field if non-nil, zero value otherwise.

### GetSlOk

`func (o *PLAsset) GetSlOk() (*string, bool)`

GetSlOk returns a tuple with the Sl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSl

`func (o *PLAsset) SetSl(v string)`

SetSl sets Sl field to given value.

### HasSl

`func (o *PLAsset) HasSl() bool`

HasSl returns a boolean if a field has been set.

### GetInitialCapital

`func (o *PLAsset) GetInitialCapital() string`

GetInitialCapital returns the InitialCapital field if non-nil, zero value otherwise.

### GetInitialCapitalOk

`func (o *PLAsset) GetInitialCapitalOk() (*string, bool)`

GetInitialCapitalOk returns a tuple with the InitialCapital field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialCapital

`func (o *PLAsset) SetInitialCapital(v string)`

SetInitialCapital sets InitialCapital field to given value.


### GetImpendingBorrows

`func (o *PLAsset) GetImpendingBorrows() string`

GetImpendingBorrows returns the ImpendingBorrows field if non-nil, zero value otherwise.

### GetImpendingBorrowsOk

`func (o *PLAsset) GetImpendingBorrowsOk() (*string, bool)`

GetImpendingBorrowsOk returns a tuple with the ImpendingBorrows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpendingBorrows

`func (o *PLAsset) SetImpendingBorrows(v string)`

SetImpendingBorrows sets ImpendingBorrows field to given value.

### HasImpendingBorrows

`func (o *PLAsset) HasImpendingBorrows() bool`

HasImpendingBorrows returns a boolean if a field has been set.

### GetLocked

`func (o *PLAsset) GetLocked() string`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *PLAsset) GetLockedOk() (*string, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *PLAsset) SetLocked(v string)`

SetLocked sets Locked field to given value.


### GetUnusedCollateral

`func (o *PLAsset) GetUnusedCollateral() string`

GetUnusedCollateral returns the UnusedCollateral field if non-nil, zero value otherwise.

### GetUnusedCollateralOk

`func (o *PLAsset) GetUnusedCollateralOk() (*string, bool)`

GetUnusedCollateralOk returns a tuple with the UnusedCollateral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnusedCollateral

`func (o *PLAsset) SetUnusedCollateral(v string)`

SetUnusedCollateral sets UnusedCollateral field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


