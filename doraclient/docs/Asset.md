# Asset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**CollateralWeight** | **float32** |  | 
**CreatedAt** | **time.Time** |  | 
**Decimals** | **int32** |  | 
**FractionalizedUnits** | **int32** |  | 
**Description** | **string** |  | 
**LiquidationWeight** | **float32** |  | 
**MaxSupply** | **int32** |  | 
**MaxUtilization** | **float32** |  | 
**MinimumRate** | **float32** |  | 
**KinkRate** | **float32** |  | 
**MaximumRate** | **float32** |  | 
**KinkUtilization** | **float32** |  | 
**Name** | **string** |  | 
**Symbol** | **string** |  | 
**Kind** | [**AssetKind**](AssetKind.md) |  | 
**Yield** | Pointer to **float32** |  | [optional] 
**CanAddLiquidity** | **bool** |  | 
**CanDirectBorrow** | **bool** |  | 
**CanOnboard** | **bool** |  | 
**CanTrade** | **bool** |  | 
**CanVirtualBorrow** | **bool** |  | 
**MaxLeverage** | **float32** |  | 
**LeverageInterestRate** | Pointer to **float32** |  | [optional] [default to 0]
**Bond** | Pointer to [**Bond**](Bond.md) |  | [optional] 

## Methods

### NewAsset

`func NewAsset(id string, collateralWeight float32, createdAt time.Time, decimals int32, fractionalizedUnits int32, description string, liquidationWeight float32, maxSupply int32, maxUtilization float32, minimumRate float32, kinkRate float32, maximumRate float32, kinkUtilization float32, name string, symbol string, kind AssetKind, canAddLiquidity bool, canDirectBorrow bool, canOnboard bool, canTrade bool, canVirtualBorrow bool, maxLeverage float32, ) *Asset`

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


### GetLiquidationWeight

`func (o *Asset) GetLiquidationWeight() float32`

GetLiquidationWeight returns the LiquidationWeight field if non-nil, zero value otherwise.

### GetLiquidationWeightOk

`func (o *Asset) GetLiquidationWeightOk() (*float32, bool)`

GetLiquidationWeightOk returns a tuple with the LiquidationWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiquidationWeight

`func (o *Asset) SetLiquidationWeight(v float32)`

SetLiquidationWeight sets LiquidationWeight field to given value.


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


### GetMaxUtilization

`func (o *Asset) GetMaxUtilization() float32`

GetMaxUtilization returns the MaxUtilization field if non-nil, zero value otherwise.

### GetMaxUtilizationOk

`func (o *Asset) GetMaxUtilizationOk() (*float32, bool)`

GetMaxUtilizationOk returns a tuple with the MaxUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUtilization

`func (o *Asset) SetMaxUtilization(v float32)`

SetMaxUtilization sets MaxUtilization field to given value.


### GetMinimumRate

`func (o *Asset) GetMinimumRate() float32`

GetMinimumRate returns the MinimumRate field if non-nil, zero value otherwise.

### GetMinimumRateOk

`func (o *Asset) GetMinimumRateOk() (*float32, bool)`

GetMinimumRateOk returns a tuple with the MinimumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumRate

`func (o *Asset) SetMinimumRate(v float32)`

SetMinimumRate sets MinimumRate field to given value.


### GetKinkRate

`func (o *Asset) GetKinkRate() float32`

GetKinkRate returns the KinkRate field if non-nil, zero value otherwise.

### GetKinkRateOk

`func (o *Asset) GetKinkRateOk() (*float32, bool)`

GetKinkRateOk returns a tuple with the KinkRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkRate

`func (o *Asset) SetKinkRate(v float32)`

SetKinkRate sets KinkRate field to given value.


### GetMaximumRate

`func (o *Asset) GetMaximumRate() float32`

GetMaximumRate returns the MaximumRate field if non-nil, zero value otherwise.

### GetMaximumRateOk

`func (o *Asset) GetMaximumRateOk() (*float32, bool)`

GetMaximumRateOk returns a tuple with the MaximumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRate

`func (o *Asset) SetMaximumRate(v float32)`

SetMaximumRate sets MaximumRate field to given value.


### GetKinkUtilization

`func (o *Asset) GetKinkUtilization() float32`

GetKinkUtilization returns the KinkUtilization field if non-nil, zero value otherwise.

### GetKinkUtilizationOk

`func (o *Asset) GetKinkUtilizationOk() (*float32, bool)`

GetKinkUtilizationOk returns a tuple with the KinkUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkUtilization

`func (o *Asset) SetKinkUtilization(v float32)`

SetKinkUtilization sets KinkUtilization field to given value.


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


### GetLeverageInterestRate

`func (o *Asset) GetLeverageInterestRate() float32`

GetLeverageInterestRate returns the LeverageInterestRate field if non-nil, zero value otherwise.

### GetLeverageInterestRateOk

`func (o *Asset) GetLeverageInterestRateOk() (*float32, bool)`

GetLeverageInterestRateOk returns a tuple with the LeverageInterestRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeverageInterestRate

`func (o *Asset) SetLeverageInterestRate(v float32)`

SetLeverageInterestRate sets LeverageInterestRate field to given value.

### HasLeverageInterestRate

`func (o *Asset) HasLeverageInterestRate() bool`

HasLeverageInterestRate returns a boolean if a field has been set.

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


