# CreateOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **float64** |  | 
**InverseLeverage** | **float64** |  | 
**Price** | Pointer to **float64** |  | [optional] 
**Kind** | [**OrderKind**](OrderKind.md) |  | 
**Side** | [**Side**](Side.md) |  | 
**PositionId** | **string** | position ID to use for the order. required. | 
**OrderBookId** | **string** | Required: the order book to submit the order to | 
**OrderModifiers** | Pointer to [**[]OrderModifierKind**](OrderModifierKind.md) |  | [optional] 
**GoodTillDate** | Pointer to **time.Time** |  | [optional] 
**TriggerPrice** | Pointer to **float64** |  | [optional] 

## Methods

### NewCreateOrderRequest

`func NewCreateOrderRequest(quantity float64, inverseLeverage float64, kind OrderKind, side Side, positionId string, orderBookId string, ) *CreateOrderRequest`

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

`func (o *CreateOrderRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateOrderRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateOrderRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.


### GetInverseLeverage

`func (o *CreateOrderRequest) GetInverseLeverage() float64`

GetInverseLeverage returns the InverseLeverage field if non-nil, zero value otherwise.

### GetInverseLeverageOk

`func (o *CreateOrderRequest) GetInverseLeverageOk() (*float64, bool)`

GetInverseLeverageOk returns a tuple with the InverseLeverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInverseLeverage

`func (o *CreateOrderRequest) SetInverseLeverage(v float64)`

SetInverseLeverage sets InverseLeverage field to given value.


### GetPrice

`func (o *CreateOrderRequest) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CreateOrderRequest) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CreateOrderRequest) SetPrice(v float64)`

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


### GetPositionId

`func (o *CreateOrderRequest) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *CreateOrderRequest) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *CreateOrderRequest) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


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

### GetTriggerPrice

`func (o *CreateOrderRequest) GetTriggerPrice() float64`

GetTriggerPrice returns the TriggerPrice field if non-nil, zero value otherwise.

### GetTriggerPriceOk

`func (o *CreateOrderRequest) GetTriggerPriceOk() (*float64, bool)`

GetTriggerPriceOk returns a tuple with the TriggerPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerPrice

`func (o *CreateOrderRequest) SetTriggerPrice(v float64)`

SetTriggerPrice sets TriggerPrice field to given value.

### HasTriggerPrice

`func (o *CreateOrderRequest) HasTriggerPrice() bool`

HasTriggerPrice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


