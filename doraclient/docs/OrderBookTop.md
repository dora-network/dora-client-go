# OrderBookTop

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | Pointer to **string** |  | [optional] 
**BestBid** | Pointer to **string** |  | [optional] 
**BestAsk** | Pointer to **string** |  | [optional] 
**Timestamp** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewOrderBookTop

`func NewOrderBookTop() *OrderBookTop`

NewOrderBookTop instantiates a new OrderBookTop object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderBookTopWithDefaults

`func NewOrderBookTopWithDefaults() *OrderBookTop`

NewOrderBookTopWithDefaults instantiates a new OrderBookTop object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *OrderBookTop) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *OrderBookTop) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *OrderBookTop) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.

### HasOrderBookId

`func (o *OrderBookTop) HasOrderBookId() bool`

HasOrderBookId returns a boolean if a field has been set.

### GetBestBid

`func (o *OrderBookTop) GetBestBid() string`

GetBestBid returns the BestBid field if non-nil, zero value otherwise.

### GetBestBidOk

`func (o *OrderBookTop) GetBestBidOk() (*string, bool)`

GetBestBidOk returns a tuple with the BestBid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestBid

`func (o *OrderBookTop) SetBestBid(v string)`

SetBestBid sets BestBid field to given value.

### HasBestBid

`func (o *OrderBookTop) HasBestBid() bool`

HasBestBid returns a boolean if a field has been set.

### GetBestAsk

`func (o *OrderBookTop) GetBestAsk() string`

GetBestAsk returns the BestAsk field if non-nil, zero value otherwise.

### GetBestAskOk

`func (o *OrderBookTop) GetBestAskOk() (*string, bool)`

GetBestAskOk returns a tuple with the BestAsk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestAsk

`func (o *OrderBookTop) SetBestAsk(v string)`

SetBestAsk sets BestAsk field to given value.

### HasBestAsk

`func (o *OrderBookTop) HasBestAsk() bool`

HasBestAsk returns a boolean if a field has been set.

### GetTimestamp

`func (o *OrderBookTop) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *OrderBookTop) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *OrderBookTop) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *OrderBookTop) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


