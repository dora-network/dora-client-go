# OrderbookStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | Pointer to **string** |  | [optional] 
**OpenPrice** | Pointer to **string** | Open price of the orderbook | [optional] 
**LastPrice** | Pointer to **string** | Price of the most recent executed trade. | [optional] 
**High24h** | Pointer to **string** | Highest price of the orderbook in the last 24 hours. | [optional] 
**Low24h** | Pointer to **string** | Lowest price of the orderbook in the last 24 hours. | [optional] 
**Change24h** | Pointer to **string** | Change in price of the orderbook in the last 24 hours. | [optional] 
**ChangePct24h** | Pointer to **string** | Change percentage in price of the orderbook in the last 24 hours. | [optional] 
**Volume24hBase** | Pointer to **string** | Total volume of the orderbook in the last 24 hours. | [optional] 
**Volume24hUsd** | Pointer to **string** | Total volume of the orderbook in the last 24 hours in USD. | [optional] 

## Methods

### NewOrderbookStats

`func NewOrderbookStats() *OrderbookStats`

NewOrderbookStats instantiates a new OrderbookStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderbookStatsWithDefaults

`func NewOrderbookStatsWithDefaults() *OrderbookStats`

NewOrderbookStatsWithDefaults instantiates a new OrderbookStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *OrderbookStats) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *OrderbookStats) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *OrderbookStats) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.

### HasOrderBookId

`func (o *OrderbookStats) HasOrderBookId() bool`

HasOrderBookId returns a boolean if a field has been set.

### GetOpenPrice

`func (o *OrderbookStats) GetOpenPrice() string`

GetOpenPrice returns the OpenPrice field if non-nil, zero value otherwise.

### GetOpenPriceOk

`func (o *OrderbookStats) GetOpenPriceOk() (*string, bool)`

GetOpenPriceOk returns a tuple with the OpenPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenPrice

`func (o *OrderbookStats) SetOpenPrice(v string)`

SetOpenPrice sets OpenPrice field to given value.

### HasOpenPrice

`func (o *OrderbookStats) HasOpenPrice() bool`

HasOpenPrice returns a boolean if a field has been set.

### GetLastPrice

`func (o *OrderbookStats) GetLastPrice() string`

GetLastPrice returns the LastPrice field if non-nil, zero value otherwise.

### GetLastPriceOk

`func (o *OrderbookStats) GetLastPriceOk() (*string, bool)`

GetLastPriceOk returns a tuple with the LastPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPrice

`func (o *OrderbookStats) SetLastPrice(v string)`

SetLastPrice sets LastPrice field to given value.

### HasLastPrice

`func (o *OrderbookStats) HasLastPrice() bool`

HasLastPrice returns a boolean if a field has been set.

### GetHigh24h

`func (o *OrderbookStats) GetHigh24h() string`

GetHigh24h returns the High24h field if non-nil, zero value otherwise.

### GetHigh24hOk

`func (o *OrderbookStats) GetHigh24hOk() (*string, bool)`

GetHigh24hOk returns a tuple with the High24h field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHigh24h

`func (o *OrderbookStats) SetHigh24h(v string)`

SetHigh24h sets High24h field to given value.

### HasHigh24h

`func (o *OrderbookStats) HasHigh24h() bool`

HasHigh24h returns a boolean if a field has been set.

### GetLow24h

`func (o *OrderbookStats) GetLow24h() string`

GetLow24h returns the Low24h field if non-nil, zero value otherwise.

### GetLow24hOk

`func (o *OrderbookStats) GetLow24hOk() (*string, bool)`

GetLow24hOk returns a tuple with the Low24h field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLow24h

`func (o *OrderbookStats) SetLow24h(v string)`

SetLow24h sets Low24h field to given value.

### HasLow24h

`func (o *OrderbookStats) HasLow24h() bool`

HasLow24h returns a boolean if a field has been set.

### GetChange24h

`func (o *OrderbookStats) GetChange24h() string`

GetChange24h returns the Change24h field if non-nil, zero value otherwise.

### GetChange24hOk

`func (o *OrderbookStats) GetChange24hOk() (*string, bool)`

GetChange24hOk returns a tuple with the Change24h field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChange24h

`func (o *OrderbookStats) SetChange24h(v string)`

SetChange24h sets Change24h field to given value.

### HasChange24h

`func (o *OrderbookStats) HasChange24h() bool`

HasChange24h returns a boolean if a field has been set.

### GetChangePct24h

`func (o *OrderbookStats) GetChangePct24h() string`

GetChangePct24h returns the ChangePct24h field if non-nil, zero value otherwise.

### GetChangePct24hOk

`func (o *OrderbookStats) GetChangePct24hOk() (*string, bool)`

GetChangePct24hOk returns a tuple with the ChangePct24h field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangePct24h

`func (o *OrderbookStats) SetChangePct24h(v string)`

SetChangePct24h sets ChangePct24h field to given value.

### HasChangePct24h

`func (o *OrderbookStats) HasChangePct24h() bool`

HasChangePct24h returns a boolean if a field has been set.

### GetVolume24hBase

`func (o *OrderbookStats) GetVolume24hBase() string`

GetVolume24hBase returns the Volume24hBase field if non-nil, zero value otherwise.

### GetVolume24hBaseOk

`func (o *OrderbookStats) GetVolume24hBaseOk() (*string, bool)`

GetVolume24hBaseOk returns a tuple with the Volume24hBase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume24hBase

`func (o *OrderbookStats) SetVolume24hBase(v string)`

SetVolume24hBase sets Volume24hBase field to given value.

### HasVolume24hBase

`func (o *OrderbookStats) HasVolume24hBase() bool`

HasVolume24hBase returns a boolean if a field has been set.

### GetVolume24hUsd

`func (o *OrderbookStats) GetVolume24hUsd() string`

GetVolume24hUsd returns the Volume24hUsd field if non-nil, zero value otherwise.

### GetVolume24hUsdOk

`func (o *OrderbookStats) GetVolume24hUsdOk() (*string, bool)`

GetVolume24hUsdOk returns a tuple with the Volume24hUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume24hUsd

`func (o *OrderbookStats) SetVolume24hUsd(v string)`

SetVolume24hUsd sets Volume24hUsd field to given value.

### HasVolume24hUsd

`func (o *OrderbookStats) HasVolume24hUsd() bool`

HasVolume24hUsd returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


