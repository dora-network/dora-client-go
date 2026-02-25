# CreateOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** |  | 
**InverseLeverage** | **string** |  | 
**Price** | Pointer to **string** |  | [optional] 
**Kind** | [**OrderKind**](OrderKind.md) |  | 
**Side** | [**Side**](Side.md) | Required: Must be either &#39;BUY&#39; or &#39;SELL&#39; | 
**FromGlobalPosition** | **bool** | use global position for the order or isolated. required. | 
**OrderBookId** | **string** | Required: the order book to submit the order to | 
**OrderModifiers** | Pointer to [**[]OrderModifierKind**](OrderModifierKind.md) |  | [optional] 
**GoodTillDate** | Pointer to **time.Time** |  | [optional] 
**ClientOrderId** | Pointer to **string** | An optional client-provided identifier for the order. | [optional] 
**StopLossPrice** | Pointer to **string** | Stop loss price | [optional] 
**TakeProfitPrice** | Pointer to **string** | Take profit price | [optional] 

## Methods

### NewCreateOrderRequest

`func NewCreateOrderRequest(quantity string, inverseLeverage string, kind OrderKind, side Side, fromGlobalPosition bool, orderBookId string, ) *CreateOrderRequest`

NewCreateOrderRequest instantiates a new CreateOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderRequestWithDefaults

`func NewCreateOrderRequestWithDefaults() *CreateOrderRequest`

NewCreateOrderRequestWithDefaults instantiates a new CreateOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuantity

`func (o *CreateOrderRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateOrderRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateOrderRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetInverseLeverage

`func (o *CreateOrderRequest) GetInverseLeverage() string`

GetInverseLeverage returns the InverseLeverage field if non-nil, zero value otherwise.

### GetInverseLeverageOk

`func (o *CreateOrderRequest) GetInverseLeverageOk() (*string, bool)`

GetInverseLeverageOk returns a tuple with the InverseLeverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInverseLeverage

`func (o *CreateOrderRequest) SetInverseLeverage(v string)`

SetInverseLeverage sets InverseLeverage field to given value.


### GetPrice

`func (o *CreateOrderRequest) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CreateOrderRequest) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CreateOrderRequest) SetPrice(v string)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *CreateOrderRequest) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetKind

`func (o *CreateOrderRequest) GetKind() OrderKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CreateOrderRequest) GetKindOk() (*OrderKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CreateOrderRequest) SetKind(v OrderKind)`

SetKind sets Kind field to given value.


### GetSide

`func (o *CreateOrderRequest) GetSide() Side`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *CreateOrderRequest) GetSideOk() (*Side, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *CreateOrderRequest) SetSide(v Side)`

SetSide sets Side field to given value.


### GetFromGlobalPosition

`func (o *CreateOrderRequest) GetFromGlobalPosition() bool`

GetFromGlobalPosition returns the FromGlobalPosition field if non-nil, zero value otherwise.

### GetFromGlobalPositionOk

`func (o *CreateOrderRequest) GetFromGlobalPositionOk() (*bool, bool)`

GetFromGlobalPositionOk returns a tuple with the FromGlobalPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromGlobalPosition

`func (o *CreateOrderRequest) SetFromGlobalPosition(v bool)`

SetFromGlobalPosition sets FromGlobalPosition field to given value.


### GetOrderBookId

`func (o *CreateOrderRequest) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *CreateOrderRequest) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *CreateOrderRequest) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.


### GetOrderModifiers

`func (o *CreateOrderRequest) GetOrderModifiers() []OrderModifierKind`

GetOrderModifiers returns the OrderModifiers field if non-nil, zero value otherwise.

### GetOrderModifiersOk

`func (o *CreateOrderRequest) GetOrderModifiersOk() (*[]OrderModifierKind, bool)`

GetOrderModifiersOk returns a tuple with the OrderModifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderModifiers

`func (o *CreateOrderRequest) SetOrderModifiers(v []OrderModifierKind)`

SetOrderModifiers sets OrderModifiers field to given value.

### HasOrderModifiers

`func (o *CreateOrderRequest) HasOrderModifiers() bool`

HasOrderModifiers returns a boolean if a field has been set.

### GetGoodTillDate

`func (o *CreateOrderRequest) GetGoodTillDate() time.Time`

GetGoodTillDate returns the GoodTillDate field if non-nil, zero value otherwise.

### GetGoodTillDateOk

`func (o *CreateOrderRequest) GetGoodTillDateOk() (*time.Time, bool)`

GetGoodTillDateOk returns a tuple with the GoodTillDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoodTillDate

`func (o *CreateOrderRequest) SetGoodTillDate(v time.Time)`

SetGoodTillDate sets GoodTillDate field to given value.

### HasGoodTillDate

`func (o *CreateOrderRequest) HasGoodTillDate() bool`

HasGoodTillDate returns a boolean if a field has been set.

### GetClientOrderId

`func (o *CreateOrderRequest) GetClientOrderId() string`

GetClientOrderId returns the ClientOrderId field if non-nil, zero value otherwise.

### GetClientOrderIdOk

`func (o *CreateOrderRequest) GetClientOrderIdOk() (*string, bool)`

GetClientOrderIdOk returns a tuple with the ClientOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientOrderId

`func (o *CreateOrderRequest) SetClientOrderId(v string)`

SetClientOrderId sets ClientOrderId field to given value.

### HasClientOrderId

`func (o *CreateOrderRequest) HasClientOrderId() bool`

HasClientOrderId returns a boolean if a field has been set.

### GetStopLossPrice

`func (o *CreateOrderRequest) GetStopLossPrice() string`

GetStopLossPrice returns the StopLossPrice field if non-nil, zero value otherwise.

### GetStopLossPriceOk

`func (o *CreateOrderRequest) GetStopLossPriceOk() (*string, bool)`

GetStopLossPriceOk returns a tuple with the StopLossPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopLossPrice

`func (o *CreateOrderRequest) SetStopLossPrice(v string)`

SetStopLossPrice sets StopLossPrice field to given value.

### HasStopLossPrice

`func (o *CreateOrderRequest) HasStopLossPrice() bool`

HasStopLossPrice returns a boolean if a field has been set.

### GetTakeProfitPrice

`func (o *CreateOrderRequest) GetTakeProfitPrice() string`

GetTakeProfitPrice returns the TakeProfitPrice field if non-nil, zero value otherwise.

### GetTakeProfitPriceOk

`func (o *CreateOrderRequest) GetTakeProfitPriceOk() (*string, bool)`

GetTakeProfitPriceOk returns a tuple with the TakeProfitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakeProfitPrice

`func (o *CreateOrderRequest) SetTakeProfitPrice(v string)`

SetTakeProfitPrice sets TakeProfitPrice field to given value.

### HasTakeProfitPrice

`func (o *CreateOrderRequest) HasTakeProfitPrice() bool`

HasTakeProfitPrice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


