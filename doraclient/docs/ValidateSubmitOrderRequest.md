# ValidateSubmitOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** |  | 
**Tick** | **string** | Minimum tradable increment for the selected order book | 
**Kind** | [**OrderKind**](OrderKind.md) | Must be LIMIT or MARKET | 
**Side** | Pointer to [**Side**](Side.md) | Must be BUY or SELL | [optional] 
**Price** | **string** | If kind is LIMIT, must be &gt; 0; if MARKET it must be 0 or omitted | 
**GoodTillDate** | Pointer to **time.Time** |  | [optional] 
**InverseLeverage** | **string** |  | 
**UserBalance** | **string** | User balance used to ensure they can afford the requested quantity | 
**BaseAssetId** | Pointer to **string** | base asset of orderbook | [optional] 
**QuoteAssetId** | Pointer to **string** | quote asset of orderbook | [optional] 
**ClientOrderId** | Pointer to **string** | An optional client-provided identifier for the order. | [optional] 
**PositionAssets** | Pointer to [**[]PositionAsset**](PositionAsset.md) | Full list of assets in the position with their price and collateral weight, required when inverse_leverage &lt; 1 for leverage health checks | [optional] 
**AssetsConfig** | Pointer to [**[]AssetConfig**](AssetConfig.md) | Configuration for the assets in the order | [optional] 
**StopLossPrice** | Pointer to **string** | Stop loss price | [optional] 
**TakeProfitPrice** | Pointer to **string** | Take profit price | [optional] 

## Methods

### NewValidateSubmitOrderRequest

`func NewValidateSubmitOrderRequest(quantity string, tick string, kind OrderKind, price string, inverseLeverage string, userBalance string, ) *ValidateSubmitOrderRequest`

NewValidateSubmitOrderRequest instantiates a new ValidateSubmitOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateSubmitOrderRequestWithDefaults

`func NewValidateSubmitOrderRequestWithDefaults() *ValidateSubmitOrderRequest`

NewValidateSubmitOrderRequestWithDefaults instantiates a new ValidateSubmitOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuantity

`func (o *ValidateSubmitOrderRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ValidateSubmitOrderRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ValidateSubmitOrderRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetTick

`func (o *ValidateSubmitOrderRequest) GetTick() string`

GetTick returns the Tick field if non-nil, zero value otherwise.

### GetTickOk

`func (o *ValidateSubmitOrderRequest) GetTickOk() (*string, bool)`

GetTickOk returns a tuple with the Tick field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTick

`func (o *ValidateSubmitOrderRequest) SetTick(v string)`

SetTick sets Tick field to given value.


### GetKind

`func (o *ValidateSubmitOrderRequest) GetKind() OrderKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ValidateSubmitOrderRequest) GetKindOk() (*OrderKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ValidateSubmitOrderRequest) SetKind(v OrderKind)`

SetKind sets Kind field to given value.


### GetSide

`func (o *ValidateSubmitOrderRequest) GetSide() Side`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *ValidateSubmitOrderRequest) GetSideOk() (*Side, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *ValidateSubmitOrderRequest) SetSide(v Side)`

SetSide sets Side field to given value.

### HasSide

`func (o *ValidateSubmitOrderRequest) HasSide() bool`

HasSide returns a boolean if a field has been set.

### GetPrice

`func (o *ValidateSubmitOrderRequest) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ValidateSubmitOrderRequest) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ValidateSubmitOrderRequest) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetGoodTillDate

`func (o *ValidateSubmitOrderRequest) GetGoodTillDate() time.Time`

GetGoodTillDate returns the GoodTillDate field if non-nil, zero value otherwise.

### GetGoodTillDateOk

`func (o *ValidateSubmitOrderRequest) GetGoodTillDateOk() (*time.Time, bool)`

GetGoodTillDateOk returns a tuple with the GoodTillDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoodTillDate

`func (o *ValidateSubmitOrderRequest) SetGoodTillDate(v time.Time)`

SetGoodTillDate sets GoodTillDate field to given value.

### HasGoodTillDate

`func (o *ValidateSubmitOrderRequest) HasGoodTillDate() bool`

HasGoodTillDate returns a boolean if a field has been set.

### GetInverseLeverage

`func (o *ValidateSubmitOrderRequest) GetInverseLeverage() string`

GetInverseLeverage returns the InverseLeverage field if non-nil, zero value otherwise.

### GetInverseLeverageOk

`func (o *ValidateSubmitOrderRequest) GetInverseLeverageOk() (*string, bool)`

GetInverseLeverageOk returns a tuple with the InverseLeverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInverseLeverage

`func (o *ValidateSubmitOrderRequest) SetInverseLeverage(v string)`

SetInverseLeverage sets InverseLeverage field to given value.


### GetUserBalance

`func (o *ValidateSubmitOrderRequest) GetUserBalance() string`

GetUserBalance returns the UserBalance field if non-nil, zero value otherwise.

### GetUserBalanceOk

`func (o *ValidateSubmitOrderRequest) GetUserBalanceOk() (*string, bool)`

GetUserBalanceOk returns a tuple with the UserBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserBalance

`func (o *ValidateSubmitOrderRequest) SetUserBalance(v string)`

SetUserBalance sets UserBalance field to given value.


### GetBaseAssetId

`func (o *ValidateSubmitOrderRequest) GetBaseAssetId() string`

GetBaseAssetId returns the BaseAssetId field if non-nil, zero value otherwise.

### GetBaseAssetIdOk

`func (o *ValidateSubmitOrderRequest) GetBaseAssetIdOk() (*string, bool)`

GetBaseAssetIdOk returns a tuple with the BaseAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseAssetId

`func (o *ValidateSubmitOrderRequest) SetBaseAssetId(v string)`

SetBaseAssetId sets BaseAssetId field to given value.

### HasBaseAssetId

`func (o *ValidateSubmitOrderRequest) HasBaseAssetId() bool`

HasBaseAssetId returns a boolean if a field has been set.

### GetQuoteAssetId

`func (o *ValidateSubmitOrderRequest) GetQuoteAssetId() string`

GetQuoteAssetId returns the QuoteAssetId field if non-nil, zero value otherwise.

### GetQuoteAssetIdOk

`func (o *ValidateSubmitOrderRequest) GetQuoteAssetIdOk() (*string, bool)`

GetQuoteAssetIdOk returns a tuple with the QuoteAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteAssetId

`func (o *ValidateSubmitOrderRequest) SetQuoteAssetId(v string)`

SetQuoteAssetId sets QuoteAssetId field to given value.

### HasQuoteAssetId

`func (o *ValidateSubmitOrderRequest) HasQuoteAssetId() bool`

HasQuoteAssetId returns a boolean if a field has been set.

### GetClientOrderId

`func (o *ValidateSubmitOrderRequest) GetClientOrderId() string`

GetClientOrderId returns the ClientOrderId field if non-nil, zero value otherwise.

### GetClientOrderIdOk

`func (o *ValidateSubmitOrderRequest) GetClientOrderIdOk() (*string, bool)`

GetClientOrderIdOk returns a tuple with the ClientOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientOrderId

`func (o *ValidateSubmitOrderRequest) SetClientOrderId(v string)`

SetClientOrderId sets ClientOrderId field to given value.

### HasClientOrderId

`func (o *ValidateSubmitOrderRequest) HasClientOrderId() bool`

HasClientOrderId returns a boolean if a field has been set.

### GetPositionAssets

`func (o *ValidateSubmitOrderRequest) GetPositionAssets() []PositionAsset`

GetPositionAssets returns the PositionAssets field if non-nil, zero value otherwise.

### GetPositionAssetsOk

`func (o *ValidateSubmitOrderRequest) GetPositionAssetsOk() (*[]PositionAsset, bool)`

GetPositionAssetsOk returns a tuple with the PositionAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionAssets

`func (o *ValidateSubmitOrderRequest) SetPositionAssets(v []PositionAsset)`

SetPositionAssets sets PositionAssets field to given value.

### HasPositionAssets

`func (o *ValidateSubmitOrderRequest) HasPositionAssets() bool`

HasPositionAssets returns a boolean if a field has been set.

### GetAssetsConfig

`func (o *ValidateSubmitOrderRequest) GetAssetsConfig() []AssetConfig`

GetAssetsConfig returns the AssetsConfig field if non-nil, zero value otherwise.

### GetAssetsConfigOk

`func (o *ValidateSubmitOrderRequest) GetAssetsConfigOk() (*[]AssetConfig, bool)`

GetAssetsConfigOk returns a tuple with the AssetsConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetsConfig

`func (o *ValidateSubmitOrderRequest) SetAssetsConfig(v []AssetConfig)`

SetAssetsConfig sets AssetsConfig field to given value.

### HasAssetsConfig

`func (o *ValidateSubmitOrderRequest) HasAssetsConfig() bool`

HasAssetsConfig returns a boolean if a field has been set.

### GetStopLossPrice

`func (o *ValidateSubmitOrderRequest) GetStopLossPrice() string`

GetStopLossPrice returns the StopLossPrice field if non-nil, zero value otherwise.

### GetStopLossPriceOk

`func (o *ValidateSubmitOrderRequest) GetStopLossPriceOk() (*string, bool)`

GetStopLossPriceOk returns a tuple with the StopLossPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopLossPrice

`func (o *ValidateSubmitOrderRequest) SetStopLossPrice(v string)`

SetStopLossPrice sets StopLossPrice field to given value.

### HasStopLossPrice

`func (o *ValidateSubmitOrderRequest) HasStopLossPrice() bool`

HasStopLossPrice returns a boolean if a field has been set.

### GetTakeProfitPrice

`func (o *ValidateSubmitOrderRequest) GetTakeProfitPrice() string`

GetTakeProfitPrice returns the TakeProfitPrice field if non-nil, zero value otherwise.

### GetTakeProfitPriceOk

`func (o *ValidateSubmitOrderRequest) GetTakeProfitPriceOk() (*string, bool)`

GetTakeProfitPriceOk returns a tuple with the TakeProfitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakeProfitPrice

`func (o *ValidateSubmitOrderRequest) SetTakeProfitPrice(v string)`

SetTakeProfitPrice sets TakeProfitPrice field to given value.

### HasTakeProfitPrice

`func (o *ValidateSubmitOrderRequest) HasTakeProfitPrice() bool`

HasTakeProfitPrice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


