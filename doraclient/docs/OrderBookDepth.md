# OrderBookDepth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | **string** |  | 
**Bids** | [**[]PriceLevel**](PriceLevel.md) |  | 
**Asks** | [**[]PriceLevel**](PriceLevel.md) |  | 
**Timestamp** | **time.Time** |  | 

## Methods

### NewOrderBookDepth

`func NewOrderBookDepth(orderBookId string, bids []PriceLevel, asks []PriceLevel, timestamp time.Time, ) *OrderBookDepth`

NewOrderBookDepth instantiates a new OrderBookDepth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderBookDepthWithDefaults

`func NewOrderBookDepthWithDefaults() *OrderBookDepth`

NewOrderBookDepthWithDefaults instantiates a new OrderBookDepth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *OrderBookDepth) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *OrderBookDepth) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *OrderBookDepth) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.


### GetBids

`func (o *OrderBookDepth) GetBids() []PriceLevel`

GetBids returns the Bids field if non-nil, zero value otherwise.

### GetBidsOk

`func (o *OrderBookDepth) GetBidsOk() (*[]PriceLevel, bool)`

GetBidsOk returns a tuple with the Bids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBids

`func (o *OrderBookDepth) SetBids(v []PriceLevel)`

SetBids sets Bids field to given value.


### GetAsks

`func (o *OrderBookDepth) GetAsks() []PriceLevel`

GetAsks returns the Asks field if non-nil, zero value otherwise.

### GetAsksOk

`func (o *OrderBookDepth) GetAsksOk() (*[]PriceLevel, bool)`

GetAsksOk returns a tuple with the Asks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsks

`func (o *OrderBookDepth) SetAsks(v []PriceLevel)`

SetAsks sets Asks field to given value.


### GetTimestamp

`func (o *OrderBookDepth) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *OrderBookDepth) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *OrderBookDepth) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


