# ValidateSubmitOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **float64** |  | 
**Tick** | **float64** | Minimum tradable increment for the selected order book | 
**Kind** | [**OrderKind**](OrderKind.md) |  | 
**Side** | Pointer to [**Side**](Side.md) |  | [optional] 
**Price** | **float64** | If kind is LIMIT, must be &gt; 0; if MARKET it must be 0 or omitted | 
**GoodTillDate** | Pointer to **time.Time** |  | [optional] 
**InverseLeverage** | **float64** |  | 
**UserBalance** | **float64** | User balance used to ensure they can afford the requested quantity | 

## Methods

### NewValidateSubmitOrderRequest

`func NewValidateSubmitOrderRequest(quantity float64, tick float64, kind OrderKind, price float64, inverseLeverage float64, userBalance float64, ) *ValidateSubmitOrderRequest`

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

`func (o *ValidateSubmitOrderRequest) GetQuantity() float64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ValidateSubmitOrderRequest) GetQuantityOk() (*float64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ValidateSubmitOrderRequest) SetQuantity(v float64)`

SetQuantity sets Quantity field to given value.


### GetTick

`func (o *ValidateSubmitOrderRequest) GetTick() float64`

GetTick returns the Tick field if non-nil, zero value otherwise.

### GetTickOk

`func (o *ValidateSubmitOrderRequest) GetTickOk() (*float64, bool)`

GetTickOk returns a tuple with the Tick field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTick

`func (o *ValidateSubmitOrderRequest) SetTick(v float64)`

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

`func (o *ValidateSubmitOrderRequest) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ValidateSubmitOrderRequest) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ValidateSubmitOrderRequest) SetPrice(v float64)`

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

`func (o *ValidateSubmitOrderRequest) GetInverseLeverage() float64`

GetInverseLeverage returns the InverseLeverage field if non-nil, zero value otherwise.

### GetInverseLeverageOk

`func (o *ValidateSubmitOrderRequest) GetInverseLeverageOk() (*float64, bool)`

GetInverseLeverageOk returns a tuple with the InverseLeverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInverseLeverage

`func (o *ValidateSubmitOrderRequest) SetInverseLeverage(v float64)`

SetInverseLeverage sets InverseLeverage field to given value.


### GetUserBalance

`func (o *ValidateSubmitOrderRequest) GetUserBalance() float64`

GetUserBalance returns the UserBalance field if non-nil, zero value otherwise.

### GetUserBalanceOk

`func (o *ValidateSubmitOrderRequest) GetUserBalanceOk() (*float64, bool)`

GetUserBalanceOk returns a tuple with the UserBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserBalance

`func (o *ValidateSubmitOrderRequest) SetUserBalance(v float64)`

SetUserBalance sets UserBalance field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


