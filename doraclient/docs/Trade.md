# Trade

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | **string** |  | 
**Asset0** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**OrderBookId** | **string** |  | 
**OrderId** | **string** |  | 
**OrderSeq** | **int32** |  | 
**Price** | **string** |  | 
**Quantity0** | **string** |  | 
**UserId** | **string** |  | 
**Side** | [**Side**](Side.md) |  | 
**AggressorIndicator** | **bool** | If true, then this order is the aggressor (taker); otherwise it is the maker. | 

## Methods

### NewTrade

`func NewTrade(transactionId string, asset0 string, createdAt time.Time, orderBookId string, orderId string, orderSeq int32, price string, quantity0 string, userId string, side Side, aggressorIndicator bool, ) *Trade`

NewTrade instantiates a new Trade object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradeWithDefaults

`func NewTradeWithDefaults() *Trade`

NewTradeWithDefaults instantiates a new Trade object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *Trade) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *Trade) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *Trade) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetAsset0

`func (o *Trade) GetAsset0() string`

GetAsset0 returns the Asset0 field if non-nil, zero value otherwise.

### GetAsset0Ok

`func (o *Trade) GetAsset0Ok() (*string, bool)`

GetAsset0Ok returns a tuple with the Asset0 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsset0

`func (o *Trade) SetAsset0(v string)`

SetAsset0 sets Asset0 field to given value.


### GetCreatedAt

`func (o *Trade) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Trade) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Trade) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetOrderBookId

`func (o *Trade) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *Trade) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *Trade) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.


### GetOrderId

`func (o *Trade) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *Trade) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *Trade) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetOrderSeq

`func (o *Trade) GetOrderSeq() int32`

GetOrderSeq returns the OrderSeq field if non-nil, zero value otherwise.

### GetOrderSeqOk

`func (o *Trade) GetOrderSeqOk() (*int32, bool)`

GetOrderSeqOk returns a tuple with the OrderSeq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderSeq

`func (o *Trade) SetOrderSeq(v int32)`

SetOrderSeq sets OrderSeq field to given value.


### GetPrice

`func (o *Trade) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *Trade) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *Trade) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetQuantity0

`func (o *Trade) GetQuantity0() string`

GetQuantity0 returns the Quantity0 field if non-nil, zero value otherwise.

### GetQuantity0Ok

`func (o *Trade) GetQuantity0Ok() (*string, bool)`

GetQuantity0Ok returns a tuple with the Quantity0 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity0

`func (o *Trade) SetQuantity0(v string)`

SetQuantity0 sets Quantity0 field to given value.


### GetUserId

`func (o *Trade) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Trade) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Trade) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetSide

`func (o *Trade) GetSide() Side`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *Trade) GetSideOk() (*Side, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *Trade) SetSide(v Side)`

SetSide sets Side field to given value.


### GetAggressorIndicator

`func (o *Trade) GetAggressorIndicator() bool`

GetAggressorIndicator returns the AggressorIndicator field if non-nil, zero value otherwise.

### GetAggressorIndicatorOk

`func (o *Trade) GetAggressorIndicatorOk() (*bool, bool)`

GetAggressorIndicatorOk returns a tuple with the AggressorIndicator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggressorIndicator

`func (o *Trade) SetAggressorIndicator(v bool)`

SetAggressorIndicator sets AggressorIndicator field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


