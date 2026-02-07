# Liquidity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | **string** |  | 
**PositionId** | **string** |  | 
**TransactionId** | **string** |  | 
**BaseQuantity** | **string** |  | 
**QuoteQuantity** | **string** |  | 
**SharesQuantity** | **string** |  | 

## Methods

### NewLiquidity

`func NewLiquidity(orderBookId string, positionId string, transactionId string, baseQuantity string, quoteQuantity string, sharesQuantity string, ) *Liquidity`

NewLiquidity instantiates a new Liquidity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLiquidityWithDefaults

`func NewLiquidityWithDefaults() *Liquidity`

NewLiquidityWithDefaults instantiates a new Liquidity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *Liquidity) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *Liquidity) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *Liquidity) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.


### GetPositionId

`func (o *Liquidity) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *Liquidity) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *Liquidity) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetTransactionId

`func (o *Liquidity) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *Liquidity) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *Liquidity) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetBaseQuantity

`func (o *Liquidity) GetBaseQuantity() string`

GetBaseQuantity returns the BaseQuantity field if non-nil, zero value otherwise.

### GetBaseQuantityOk

`func (o *Liquidity) GetBaseQuantityOk() (*string, bool)`

GetBaseQuantityOk returns a tuple with the BaseQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseQuantity

`func (o *Liquidity) SetBaseQuantity(v string)`

SetBaseQuantity sets BaseQuantity field to given value.


### GetQuoteQuantity

`func (o *Liquidity) GetQuoteQuantity() string`

GetQuoteQuantity returns the QuoteQuantity field if non-nil, zero value otherwise.

### GetQuoteQuantityOk

`func (o *Liquidity) GetQuoteQuantityOk() (*string, bool)`

GetQuoteQuantityOk returns a tuple with the QuoteQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteQuantity

`func (o *Liquidity) SetQuoteQuantity(v string)`

SetQuoteQuantity sets QuoteQuantity field to given value.


### GetSharesQuantity

`func (o *Liquidity) GetSharesQuantity() string`

GetSharesQuantity returns the SharesQuantity field if non-nil, zero value otherwise.

### GetSharesQuantityOk

`func (o *Liquidity) GetSharesQuantityOk() (*string, bool)`

GetSharesQuantityOk returns a tuple with the SharesQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharesQuantity

`func (o *Liquidity) SetSharesQuantity(v string)`

SetSharesQuantity sets SharesQuantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


