# PLAsset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Symbol** | Pointer to **string** | The symbol of the asset | [optional] 
**Side** | Pointer to **string** | The side of the position (LONG or SHORT) | [optional] 
**AvgEntryPrice** | Pointer to **float64** | The average entry price of the position | [optional] 
**MarkPrice** | Pointer to **float64** | The current mark price for the asset to calculate daily PL. This is usually the close price of the previous day | [optional] 
**LiquidationPrice** | Pointer to **float64** | The liquidation price of the position | [optional] 
**Available** | Pointer to **float64** | The available quantity in units of the asset | [optional] 
**Borrowed** | Pointer to **float64** | The borrowed quantity in units of the asset | [optional] 
**Margin** | Pointer to [**Margin**](Margin.md) |  | [optional] 
**UnrealizedPl** | Pointer to **float64** | The unrealized profit or loss of the position | [optional] 
**LeverageLimit** | Pointer to **float64** | The leverage limit for the position | [optional] 
**Tp** | Pointer to **float64** | The take profit price set for the position, if any | [optional] 
**Sl** | Pointer to **float64** | The stop loss price set for the position, if any | [optional] 

## Methods

### NewPLAsset

`func NewPLAsset() *PLAsset`

NewPLAsset instantiates a new PLAsset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPLAssetWithDefaults

`func NewPLAssetWithDefaults() *PLAsset`

NewPLAssetWithDefaults instantiates a new PLAsset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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

### HasSymbol

`func (o *PLAsset) HasSymbol() bool`

HasSymbol returns a boolean if a field has been set.

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

### HasSide

`func (o *PLAsset) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetAvgEntryPrice

`func (o *PLAsset) GetAvgEntryPrice() float64`

GetAvgEntryPrice returns the AvgEntryPrice field if non-nil, zero value otherwise.

### GetAvgEntryPriceOk

`func (o *PLAsset) GetAvgEntryPriceOk() (*float64, bool)`

GetAvgEntryPriceOk returns a tuple with the AvgEntryPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEntryPrice

`func (o *PLAsset) SetAvgEntryPrice(v float64)`

SetAvgEntryPrice sets AvgEntryPrice field to given value.

### HasAvgEntryPrice

`func (o *PLAsset) HasAvgEntryPrice() bool`

HasAvgEntryPrice returns a boolean if a field has been set.

### GetMarkPrice

`func (o *PLAsset) GetMarkPrice() float64`

GetMarkPrice returns the MarkPrice field if non-nil, zero value otherwise.

### GetMarkPriceOk

`func (o *PLAsset) GetMarkPriceOk() (*float64, bool)`

GetMarkPriceOk returns a tuple with the MarkPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkPrice

`func (o *PLAsset) SetMarkPrice(v float64)`

SetMarkPrice sets MarkPrice field to given value.

### HasMarkPrice

`func (o *PLAsset) HasMarkPrice() bool`

HasMarkPrice returns a boolean if a field has been set.

### GetLiquidationPrice

`func (o *PLAsset) GetLiquidationPrice() float64`

GetLiquidationPrice returns the LiquidationPrice field if non-nil, zero value otherwise.

### GetLiquidationPriceOk

`func (o *PLAsset) GetLiquidationPriceOk() (*float64, bool)`

GetLiquidationPriceOk returns a tuple with the LiquidationPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationPrice

`func (o *PLAsset) SetLiquidationPrice(v float64)`

SetLiquidationPrice sets LiquidationPrice field to given value.

### HasLiquidationPrice

`func (o *PLAsset) HasLiquidationPrice() bool`

HasLiquidationPrice returns a boolean if a field has been set.

### GetAvailable

`func (o *PLAsset) GetAvailable() float64`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *PLAsset) GetAvailableOk() (*float64, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *PLAsset) SetAvailable(v float64)`

SetAvailable sets Available field to given value.

### HasAvailable

`func (o *PLAsset) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

### GetBorrowed

`func (o *PLAsset) GetBorrowed() float64`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *PLAsset) GetBorrowedOk() (*float64, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *PLAsset) SetBorrowed(v float64)`

SetBorrowed sets Borrowed field to given value.

### HasBorrowed

`func (o *PLAsset) HasBorrowed() bool`

HasBorrowed returns a boolean if a field has been set.

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

### HasMargin

`func (o *PLAsset) HasMargin() bool`

HasMargin returns a boolean if a field has been set.

### GetUnrealizedPl

`func (o *PLAsset) GetUnrealizedPl() float64`

GetUnrealizedPl returns the UnrealizedPl field if non-nil, zero value otherwise.

### GetUnrealizedPlOk

`func (o *PLAsset) GetUnrealizedPlOk() (*float64, bool)`

GetUnrealizedPlOk returns a tuple with the UnrealizedPl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrealizedPl

`func (o *PLAsset) SetUnrealizedPl(v float64)`

SetUnrealizedPl sets UnrealizedPl field to given value.

### HasUnrealizedPl

`func (o *PLAsset) HasUnrealizedPl() bool`

HasUnrealizedPl returns a boolean if a field has been set.

### GetLeverageLimit

`func (o *PLAsset) GetLeverageLimit() float64`

GetLeverageLimit returns the LeverageLimit field if non-nil, zero value otherwise.

### GetLeverageLimitOk

`func (o *PLAsset) GetLeverageLimitOk() (*float64, bool)`

GetLeverageLimitOk returns a tuple with the LeverageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeverageLimit

`func (o *PLAsset) SetLeverageLimit(v float64)`

SetLeverageLimit sets LeverageLimit field to given value.

### HasLeverageLimit

`func (o *PLAsset) HasLeverageLimit() bool`

HasLeverageLimit returns a boolean if a field has been set.

### GetTp

`func (o *PLAsset) GetTp() float64`

GetTp returns the Tp field if non-nil, zero value otherwise.

### GetTpOk

`func (o *PLAsset) GetTpOk() (*float64, bool)`

GetTpOk returns a tuple with the Tp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTp

`func (o *PLAsset) SetTp(v float64)`

SetTp sets Tp field to given value.

### HasTp

`func (o *PLAsset) HasTp() bool`

HasTp returns a boolean if a field has been set.

### GetSl

`func (o *PLAsset) GetSl() float64`

GetSl returns the Sl field if non-nil, zero value otherwise.

### GetSlOk

`func (o *PLAsset) GetSlOk() (*float64, bool)`

GetSlOk returns a tuple with the Sl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSl

`func (o *PLAsset) SetSl(v float64)`

SetSl sets Sl field to given value.

### HasSl

`func (o *PLAsset) HasSl() bool`

HasSl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


