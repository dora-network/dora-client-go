# Asset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**CollateralWeight** | Pointer to **float32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**Decimals** | Pointer to **int32** |  | [optional] 
**FractionalizedUnits** | Pointer to **int32** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**LiquidationThreshold** | Pointer to **float32** |  | [optional] 
**MaturityId** | Pointer to **string** |  | [optional] 
**MaxSupply** | Pointer to **int32** |  | [optional] 
**MaxUtilization** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Symbol** | Pointer to **string** |  | [optional] 
**Kind** | Pointer to [**AssetKind**](AssetKind.md) |  | [optional] 
**Yield** | Pointer to **float32** |  | [optional] 
**CanAddLiquidity** | Pointer to **bool** |  | [optional] 
**CanDirectBorrow** | Pointer to **bool** |  | [optional] 
**CanOnboard** | Pointer to **bool** |  | [optional] 
**CanTrade** | Pointer to **bool** |  | [optional] 
**CanVirtualBorrow** | Pointer to **bool** |  | [optional] 
**MaxLeverage** | Pointer to **float32** |  | [optional] 
**Bond** | Pointer to [**Bond**](Bond.md) |  | [optional] 

## Methods

### NewAsset

`func NewAsset() *Asset`

NewAsset instantiates a new Asset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetWithDefaults

`func NewAssetWithDefaults() *Asset`

NewAssetWithDefaults instantiates a new Asset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Asset) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Asset) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Asset) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Asset) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCollateralWeight

`func (o *Asset) GetCollateralWeight() float32`

GetCollateralWeight returns the CollateralWeight field if non-nil, zero value otherwise.

### GetCollateralWeightOk

`func (o *Asset) GetCollateralWeightOk() (*float32, bool)`

GetCollateralWeightOk returns a tuple with the CollateralWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollateralWeight

`func (o *Asset) SetCollateralWeight(v float32)`

SetCollateralWeight sets CollateralWeight field to given value.

### HasCollateralWeight

`func (o *Asset) HasCollateralWeight() bool`

HasCollateralWeight returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Asset) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Asset) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Asset) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Asset) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDecimals

`func (o *Asset) GetDecimals() int32`

GetDecimals returns the Decimals field if non-nil, zero value otherwise.

### GetDecimalsOk

`func (o *Asset) GetDecimalsOk() (*int32, bool)`

GetDecimalsOk returns a tuple with the Decimals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecimals

`func (o *Asset) SetDecimals(v int32)`

SetDecimals sets Decimals field to given value.

### HasDecimals

`func (o *Asset) HasDecimals() bool`

HasDecimals returns a boolean if a field has been set.

### GetFractionalizedUnits

`func (o *Asset) GetFractionalizedUnits() int32`

GetFractionalizedUnits returns the FractionalizedUnits field if non-nil, zero value otherwise.

### GetFractionalizedUnitsOk

`func (o *Asset) GetFractionalizedUnitsOk() (*int32, bool)`

GetFractionalizedUnitsOk returns a tuple with the FractionalizedUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFractionalizedUnits

`func (o *Asset) SetFractionalizedUnits(v int32)`

SetFractionalizedUnits sets FractionalizedUnits field to given value.

### HasFractionalizedUnits

`func (o *Asset) HasFractionalizedUnits() bool`

HasFractionalizedUnits returns a boolean if a field has been set.

### GetDescription

`func (o *Asset) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Asset) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Asset) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Asset) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLiquidationThreshold

`func (o *Asset) GetLiquidationThreshold() float32`

GetLiquidationThreshold returns the LiquidationThreshold field if non-nil, zero value otherwise.

### GetLiquidationThresholdOk

`func (o *Asset) GetLiquidationThresholdOk() (*float32, bool)`

GetLiquidationThresholdOk returns a tuple with the LiquidationThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationThreshold

`func (o *Asset) SetLiquidationThreshold(v float32)`

SetLiquidationThreshold sets LiquidationThreshold field to given value.

### HasLiquidationThreshold

`func (o *Asset) HasLiquidationThreshold() bool`

HasLiquidationThreshold returns a boolean if a field has been set.

### GetMaturityId

`func (o *Asset) GetMaturityId() string`

GetMaturityId returns the MaturityId field if non-nil, zero value otherwise.

### GetMaturityIdOk

`func (o *Asset) GetMaturityIdOk() (*string, bool)`

GetMaturityIdOk returns a tuple with the MaturityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaturityId

`func (o *Asset) SetMaturityId(v string)`

SetMaturityId sets MaturityId field to given value.

### HasMaturityId

`func (o *Asset) HasMaturityId() bool`

HasMaturityId returns a boolean if a field has been set.

### GetMaxSupply

`func (o *Asset) GetMaxSupply() int32`

GetMaxSupply returns the MaxSupply field if non-nil, zero value otherwise.

### GetMaxSupplyOk

`func (o *Asset) GetMaxSupplyOk() (*int32, bool)`

GetMaxSupplyOk returns a tuple with the MaxSupply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSupply

`func (o *Asset) SetMaxSupply(v int32)`

SetMaxSupply sets MaxSupply field to given value.

### HasMaxSupply

`func (o *Asset) HasMaxSupply() bool`

HasMaxSupply returns a boolean if a field has been set.

### GetMaxUtilization

`func (o *Asset) GetMaxUtilization() int32`

GetMaxUtilization returns the MaxUtilization field if non-nil, zero value otherwise.

### GetMaxUtilizationOk

`func (o *Asset) GetMaxUtilizationOk() (*int32, bool)`

GetMaxUtilizationOk returns a tuple with the MaxUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUtilization

`func (o *Asset) SetMaxUtilization(v int32)`

SetMaxUtilization sets MaxUtilization field to given value.

### HasMaxUtilization

`func (o *Asset) HasMaxUtilization() bool`

HasMaxUtilization returns a boolean if a field has been set.

### GetName

`func (o *Asset) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Asset) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Asset) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Asset) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSymbol

`func (o *Asset) GetSymbol() string`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *Asset) GetSymbolOk() (*string, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *Asset) SetSymbol(v string)`

SetSymbol sets Symbol field to given value.

### HasSymbol

`func (o *Asset) HasSymbol() bool`

HasSymbol returns a boolean if a field has been set.

### GetKind

`func (o *Asset) GetKind() AssetKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Asset) GetKindOk() (*AssetKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Asset) SetKind(v AssetKind)`

SetKind sets Kind field to given value.

### HasKind

`func (o *Asset) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetYield

`func (o *Asset) GetYield() float32`

GetYield returns the Yield field if non-nil, zero value otherwise.

### GetYieldOk

`func (o *Asset) GetYieldOk() (*float32, bool)`

GetYieldOk returns a tuple with the Yield field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYield

`func (o *Asset) SetYield(v float32)`

SetYield sets Yield field to given value.

### HasYield

`func (o *Asset) HasYield() bool`

HasYield returns a boolean if a field has been set.

### GetCanAddLiquidity

`func (o *Asset) GetCanAddLiquidity() bool`

GetCanAddLiquidity returns the CanAddLiquidity field if non-nil, zero value otherwise.

### GetCanAddLiquidityOk

`func (o *Asset) GetCanAddLiquidityOk() (*bool, bool)`

GetCanAddLiquidityOk returns a tuple with the CanAddLiquidity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanAddLiquidity

`func (o *Asset) SetCanAddLiquidity(v bool)`

SetCanAddLiquidity sets CanAddLiquidity field to given value.

### HasCanAddLiquidity

`func (o *Asset) HasCanAddLiquidity() bool`

HasCanAddLiquidity returns a boolean if a field has been set.

### GetCanDirectBorrow

`func (o *Asset) GetCanDirectBorrow() bool`

GetCanDirectBorrow returns the CanDirectBorrow field if non-nil, zero value otherwise.

### GetCanDirectBorrowOk

`func (o *Asset) GetCanDirectBorrowOk() (*bool, bool)`

GetCanDirectBorrowOk returns a tuple with the CanDirectBorrow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanDirectBorrow

`func (o *Asset) SetCanDirectBorrow(v bool)`

SetCanDirectBorrow sets CanDirectBorrow field to given value.

### HasCanDirectBorrow

`func (o *Asset) HasCanDirectBorrow() bool`

HasCanDirectBorrow returns a boolean if a field has been set.

### GetCanOnboard

`func (o *Asset) GetCanOnboard() bool`

GetCanOnboard returns the CanOnboard field if non-nil, zero value otherwise.

### GetCanOnboardOk

`func (o *Asset) GetCanOnboardOk() (*bool, bool)`

GetCanOnboardOk returns a tuple with the CanOnboard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanOnboard

`func (o *Asset) SetCanOnboard(v bool)`

SetCanOnboard sets CanOnboard field to given value.

### HasCanOnboard

`func (o *Asset) HasCanOnboard() bool`

HasCanOnboard returns a boolean if a field has been set.

### GetCanTrade

`func (o *Asset) GetCanTrade() bool`

GetCanTrade returns the CanTrade field if non-nil, zero value otherwise.

### GetCanTradeOk

`func (o *Asset) GetCanTradeOk() (*bool, bool)`

GetCanTradeOk returns a tuple with the CanTrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanTrade

`func (o *Asset) SetCanTrade(v bool)`

SetCanTrade sets CanTrade field to given value.

### HasCanTrade

`func (o *Asset) HasCanTrade() bool`

HasCanTrade returns a boolean if a field has been set.

### GetCanVirtualBorrow

`func (o *Asset) GetCanVirtualBorrow() bool`

GetCanVirtualBorrow returns the CanVirtualBorrow field if non-nil, zero value otherwise.

### GetCanVirtualBorrowOk

`func (o *Asset) GetCanVirtualBorrowOk() (*bool, bool)`

GetCanVirtualBorrowOk returns a tuple with the CanVirtualBorrow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanVirtualBorrow

`func (o *Asset) SetCanVirtualBorrow(v bool)`

SetCanVirtualBorrow sets CanVirtualBorrow field to given value.

### HasCanVirtualBorrow

`func (o *Asset) HasCanVirtualBorrow() bool`

HasCanVirtualBorrow returns a boolean if a field has been set.

### GetMaxLeverage

`func (o *Asset) GetMaxLeverage() float32`

GetMaxLeverage returns the MaxLeverage field if non-nil, zero value otherwise.

### GetMaxLeverageOk

`func (o *Asset) GetMaxLeverageOk() (*float32, bool)`

GetMaxLeverageOk returns a tuple with the MaxLeverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLeverage

`func (o *Asset) SetMaxLeverage(v float32)`

SetMaxLeverage sets MaxLeverage field to given value.

### HasMaxLeverage

`func (o *Asset) HasMaxLeverage() bool`

HasMaxLeverage returns a boolean if a field has been set.

### GetBond

`func (o *Asset) GetBond() Bond`

GetBond returns the Bond field if non-nil, zero value otherwise.

### GetBondOk

`func (o *Asset) GetBondOk() (*Bond, bool)`

GetBondOk returns a tuple with the Bond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBond

`func (o *Asset) SetBond(v Bond)`

SetBond sets Bond field to given value.

### HasBond

`func (o *Asset) HasBond() bool`

HasBond returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


