# OrderBookBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | Pointer to **string** | The ID of the order book. | [optional] 
**BaseQuantity** | Pointer to **float64** | The quantity of the base asset. | [optional] 
**QuoteQuantity** | Pointer to **float64** | The quantity of the quote asset. | [optional] 
**SharesQuantity** | Pointer to **float64** | The quantity of pool shares. | [optional] 

## Methods

### NewOrderBookBalance

`func NewOrderBookBalance() *OrderBookBalance`

NewOrderBookBalance instantiates a new OrderBookBalance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderBookBalanceWithDefaults

`func NewOrderBookBalanceWithDefaults() *OrderBookBalance`

NewOrderBookBalanceWithDefaults instantiates a new OrderBookBalance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *OrderBookBalance) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *OrderBookBalance) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *OrderBookBalance) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.

### HasOrderBookId

`func (o *OrderBookBalance) HasOrderBookId() bool`

HasOrderBookId returns a boolean if a field has been set.

### GetBaseQuantity

`func (o *OrderBookBalance) GetBaseQuantity() float64`

GetBaseQuantity returns the BaseQuantity field if non-nil, zero value otherwise.

### GetBaseQuantityOk

`func (o *OrderBookBalance) GetBaseQuantityOk() (*float64, bool)`

GetBaseQuantityOk returns a tuple with the BaseQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseQuantity

`func (o *OrderBookBalance) SetBaseQuantity(v float64)`

SetBaseQuantity sets BaseQuantity field to given value.

### HasBaseQuantity

`func (o *OrderBookBalance) HasBaseQuantity() bool`

HasBaseQuantity returns a boolean if a field has been set.

### GetQuoteQuantity

`func (o *OrderBookBalance) GetQuoteQuantity() float64`

GetQuoteQuantity returns the QuoteQuantity field if non-nil, zero value otherwise.

### GetQuoteQuantityOk

`func (o *OrderBookBalance) GetQuoteQuantityOk() (*float64, bool)`

GetQuoteQuantityOk returns a tuple with the QuoteQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteQuantity

`func (o *OrderBookBalance) SetQuoteQuantity(v float64)`

SetQuoteQuantity sets QuoteQuantity field to given value.

### HasQuoteQuantity

`func (o *OrderBookBalance) HasQuoteQuantity() bool`

HasQuoteQuantity returns a boolean if a field has been set.

### GetSharesQuantity

`func (o *OrderBookBalance) GetSharesQuantity() float64`

GetSharesQuantity returns the SharesQuantity field if non-nil, zero value otherwise.

### GetSharesQuantityOk

`func (o *OrderBookBalance) GetSharesQuantityOk() (*float64, bool)`

GetSharesQuantityOk returns a tuple with the SharesQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharesQuantity

`func (o *OrderBookBalance) SetSharesQuantity(v float64)`

SetSharesQuantity sets SharesQuantity field to given value.

### HasSharesQuantity

`func (o *OrderBookBalance) HasSharesQuantity() bool`

HasSharesQuantity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


