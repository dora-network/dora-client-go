# Order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | **string** |  | 
**OrderBookId** | **string** |  | 
**Kind** | [**OrderKind**](OrderKind.md) |  | 
**OriginalPrice** | **string** | If Kind is LIMIT, this is the original limit price. If Kind is MARKET, this may be 0 or omitted. | 
**AvgFillPrice** | **string** |  | 
**CancelledQuantity** | **string** | Quantity that was cancelled, if any. | 
**OpenQuantity** | **string** | Quantity that is still open, i.e., not filled or cancelled. | 
**OriginalQuantity** | **string** | The original quantity of the order when it was created. | 
**FilledQuantity** | **string** | Quantity that has been filled so far. | 
**FilledNotional** | **string** | Quote quantity that has been filled so far. | 
**LastUpdateAt** | Pointer to **time.Time** |  | [optional] 
**OpenedAt** | **time.Time** |  | 
**InverseLeverage** | **string** |  | 
**Side** | [**Side**](Side.md) |  | 
**Status** | [**OrderStatus**](OrderStatus.md) |  | 
**UserId** | **string** |  | 
**OrderModifiers** | Pointer to [**[]OrderModifierKind**](OrderModifierKind.md) |  | [optional] 
**PositionId** | **string** |  | 
**OrderInfo** | Pointer to **string** |  | [optional] 
**GoodTillDate** | Pointer to **time.Time** |  | [optional] 
**TriggerPrice** | Pointer to **string** |  | [optional] 
**TriggerType** | Pointer to [**TriggerType**](TriggerType.md) |  | [optional] 
**ClientOrderId** | Pointer to **string** | An optional client-provided identifier for the order. | [optional] 

## Methods

### NewOrder

`func NewOrder(orderId string, orderBookId string, kind OrderKind, originalPrice string, avgFillPrice string, cancelledQuantity string, openQuantity string, originalQuantity string, filledQuantity string, filledNotional string, openedAt time.Time, inverseLeverage string, side Side, status OrderStatus, userId string, positionId string, ) *Order`

NewOrder instantiates a new Order object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderWithDefaults

`func NewOrderWithDefaults() *Order`

NewOrderWithDefaults instantiates a new Order object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderId

`func (o *Order) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *Order) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *Order) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetOrderBookId

`func (o *Order) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *Order) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *Order) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.


### GetKind

`func (o *Order) GetKind() OrderKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Order) GetKindOk() (*OrderKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Order) SetKind(v OrderKind)`

SetKind sets Kind field to given value.


### GetOriginalPrice

`func (o *Order) GetOriginalPrice() string`

GetOriginalPrice returns the OriginalPrice field if non-nil, zero value otherwise.

### GetOriginalPriceOk

`func (o *Order) GetOriginalPriceOk() (*string, bool)`

GetOriginalPriceOk returns a tuple with the OriginalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPrice

`func (o *Order) SetOriginalPrice(v string)`

SetOriginalPrice sets OriginalPrice field to given value.


### GetAvgFillPrice

`func (o *Order) GetAvgFillPrice() string`

GetAvgFillPrice returns the AvgFillPrice field if non-nil, zero value otherwise.

### GetAvgFillPriceOk

`func (o *Order) GetAvgFillPriceOk() (*string, bool)`

GetAvgFillPriceOk returns a tuple with the AvgFillPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgFillPrice

`func (o *Order) SetAvgFillPrice(v string)`

SetAvgFillPrice sets AvgFillPrice field to given value.


### GetCancelledQuantity

`func (o *Order) GetCancelledQuantity() string`

GetCancelledQuantity returns the CancelledQuantity field if non-nil, zero value otherwise.

### GetCancelledQuantityOk

`func (o *Order) GetCancelledQuantityOk() (*string, bool)`

GetCancelledQuantityOk returns a tuple with the CancelledQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelledQuantity

`func (o *Order) SetCancelledQuantity(v string)`

SetCancelledQuantity sets CancelledQuantity field to given value.


### GetOpenQuantity

`func (o *Order) GetOpenQuantity() string`

GetOpenQuantity returns the OpenQuantity field if non-nil, zero value otherwise.

### GetOpenQuantityOk

`func (o *Order) GetOpenQuantityOk() (*string, bool)`

GetOpenQuantityOk returns a tuple with the OpenQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenQuantity

`func (o *Order) SetOpenQuantity(v string)`

SetOpenQuantity sets OpenQuantity field to given value.


### GetOriginalQuantity

`func (o *Order) GetOriginalQuantity() string`

GetOriginalQuantity returns the OriginalQuantity field if non-nil, zero value otherwise.

### GetOriginalQuantityOk

`func (o *Order) GetOriginalQuantityOk() (*string, bool)`

GetOriginalQuantityOk returns a tuple with the OriginalQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalQuantity

`func (o *Order) SetOriginalQuantity(v string)`

SetOriginalQuantity sets OriginalQuantity field to given value.


### GetFilledQuantity

`func (o *Order) GetFilledQuantity() string`

GetFilledQuantity returns the FilledQuantity field if non-nil, zero value otherwise.

### GetFilledQuantityOk

`func (o *Order) GetFilledQuantityOk() (*string, bool)`

GetFilledQuantityOk returns a tuple with the FilledQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilledQuantity

`func (o *Order) SetFilledQuantity(v string)`

SetFilledQuantity sets FilledQuantity field to given value.


### GetFilledNotional

`func (o *Order) GetFilledNotional() string`

GetFilledNotional returns the FilledNotional field if non-nil, zero value otherwise.

### GetFilledNotionalOk

`func (o *Order) GetFilledNotionalOk() (*string, bool)`

GetFilledNotionalOk returns a tuple with the FilledNotional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilledNotional

`func (o *Order) SetFilledNotional(v string)`

SetFilledNotional sets FilledNotional field to given value.


### GetLastUpdateAt

`func (o *Order) GetLastUpdateAt() time.Time`

GetLastUpdateAt returns the LastUpdateAt field if non-nil, zero value otherwise.

### GetLastUpdateAtOk

`func (o *Order) GetLastUpdateAtOk() (*time.Time, bool)`

GetLastUpdateAtOk returns a tuple with the LastUpdateAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdateAt

`func (o *Order) SetLastUpdateAt(v time.Time)`

SetLastUpdateAt sets LastUpdateAt field to given value.

### HasLastUpdateAt

`func (o *Order) HasLastUpdateAt() bool`

HasLastUpdateAt returns a boolean if a field has been set.

### GetOpenedAt

`func (o *Order) GetOpenedAt() time.Time`

GetOpenedAt returns the OpenedAt field if non-nil, zero value otherwise.

### GetOpenedAtOk

`func (o *Order) GetOpenedAtOk() (*time.Time, bool)`

GetOpenedAtOk returns a tuple with the OpenedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenedAt

`func (o *Order) SetOpenedAt(v time.Time)`

SetOpenedAt sets OpenedAt field to given value.


### GetInverseLeverage

`func (o *Order) GetInverseLeverage() string`

GetInverseLeverage returns the InverseLeverage field if non-nil, zero value otherwise.

### GetInverseLeverageOk

`func (o *Order) GetInverseLeverageOk() (*string, bool)`

GetInverseLeverageOk returns a tuple with the InverseLeverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInverseLeverage

`func (o *Order) SetInverseLeverage(v string)`

SetInverseLeverage sets InverseLeverage field to given value.


### GetSide

`func (o *Order) GetSide() Side`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *Order) GetSideOk() (*Side, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *Order) SetSide(v Side)`

SetSide sets Side field to given value.


### GetStatus

`func (o *Order) GetStatus() OrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Order) GetStatusOk() (*OrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Order) SetStatus(v OrderStatus)`

SetStatus sets Status field to given value.


### GetUserId

`func (o *Order) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Order) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Order) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetOrderModifiers

`func (o *Order) GetOrderModifiers() []OrderModifierKind`

GetOrderModifiers returns the OrderModifiers field if non-nil, zero value otherwise.

### GetOrderModifiersOk

`func (o *Order) GetOrderModifiersOk() (*[]OrderModifierKind, bool)`

GetOrderModifiersOk returns a tuple with the OrderModifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderModifiers

`func (o *Order) SetOrderModifiers(v []OrderModifierKind)`

SetOrderModifiers sets OrderModifiers field to given value.

### HasOrderModifiers

`func (o *Order) HasOrderModifiers() bool`

HasOrderModifiers returns a boolean if a field has been set.

### GetPositionId

`func (o *Order) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *Order) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *Order) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetOrderInfo

`func (o *Order) GetOrderInfo() string`

GetOrderInfo returns the OrderInfo field if non-nil, zero value otherwise.

### GetOrderInfoOk

`func (o *Order) GetOrderInfoOk() (*string, bool)`

GetOrderInfoOk returns a tuple with the OrderInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderInfo

`func (o *Order) SetOrderInfo(v string)`

SetOrderInfo sets OrderInfo field to given value.

### HasOrderInfo

`func (o *Order) HasOrderInfo() bool`

HasOrderInfo returns a boolean if a field has been set.

### GetGoodTillDate

`func (o *Order) GetGoodTillDate() time.Time`

GetGoodTillDate returns the GoodTillDate field if non-nil, zero value otherwise.

### GetGoodTillDateOk

`func (o *Order) GetGoodTillDateOk() (*time.Time, bool)`

GetGoodTillDateOk returns a tuple with the GoodTillDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoodTillDate

`func (o *Order) SetGoodTillDate(v time.Time)`

SetGoodTillDate sets GoodTillDate field to given value.

### HasGoodTillDate

`func (o *Order) HasGoodTillDate() bool`

HasGoodTillDate returns a boolean if a field has been set.

### GetTriggerPrice

`func (o *Order) GetTriggerPrice() string`

GetTriggerPrice returns the TriggerPrice field if non-nil, zero value otherwise.

### GetTriggerPriceOk

`func (o *Order) GetTriggerPriceOk() (*string, bool)`

GetTriggerPriceOk returns a tuple with the TriggerPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerPrice

`func (o *Order) SetTriggerPrice(v string)`

SetTriggerPrice sets TriggerPrice field to given value.

### HasTriggerPrice

`func (o *Order) HasTriggerPrice() bool`

HasTriggerPrice returns a boolean if a field has been set.

### GetTriggerType

`func (o *Order) GetTriggerType() TriggerType`

GetTriggerType returns the TriggerType field if non-nil, zero value otherwise.

### GetTriggerTypeOk

`func (o *Order) GetTriggerTypeOk() (*TriggerType, bool)`

GetTriggerTypeOk returns a tuple with the TriggerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerType

`func (o *Order) SetTriggerType(v TriggerType)`

SetTriggerType sets TriggerType field to given value.

### HasTriggerType

`func (o *Order) HasTriggerType() bool`

HasTriggerType returns a boolean if a field has been set.

### GetClientOrderId

`func (o *Order) GetClientOrderId() string`

GetClientOrderId returns the ClientOrderId field if non-nil, zero value otherwise.

### GetClientOrderIdOk

`func (o *Order) GetClientOrderIdOk() (*string, bool)`

GetClientOrderIdOk returns a tuple with the ClientOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientOrderId

`func (o *Order) SetClientOrderId(v string)`

SetClientOrderId sets ClientOrderId field to given value.

### HasClientOrderId

`func (o *Order) HasClientOrderId() bool`

HasClientOrderId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


