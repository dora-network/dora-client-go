# CreateConditionalOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Price** | **float64** |  | 
**OrderBookId** | **string** | Required: the order book to submit the order to | 
**PositionId** | **string** | Required: the position to submit the order to | 
**AssetId** | **string** | Required: the asset to submit the order to | 
**StopLossPrice** | Pointer to **float64** | Stop loss price | [optional] 
**TakeProfitPrice** | Pointer to **float64** | Take profit price | [optional] 

## Methods

### NewCreateConditionalOrderRequest

`func NewCreateConditionalOrderRequest(price float64, orderBookId string, positionId string, assetId string, ) *CreateConditionalOrderRequest`

NewCreateConditionalOrderRequest instantiates a new CreateConditionalOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateConditionalOrderRequestWithDefaults

`func NewCreateConditionalOrderRequestWithDefaults() *CreateConditionalOrderRequest`

NewCreateConditionalOrderRequestWithDefaults instantiates a new CreateConditionalOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrice

`func (o *CreateConditionalOrderRequest) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CreateConditionalOrderRequest) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CreateConditionalOrderRequest) SetPrice(v float64)`

SetPrice sets Price field to given value.


### GetOrderBookId

`func (o *CreateConditionalOrderRequest) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *CreateConditionalOrderRequest) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *CreateConditionalOrderRequest) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.


### GetPositionId

`func (o *CreateConditionalOrderRequest) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *CreateConditionalOrderRequest) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *CreateConditionalOrderRequest) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetAssetId

`func (o *CreateConditionalOrderRequest) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *CreateConditionalOrderRequest) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *CreateConditionalOrderRequest) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetStopLossPrice

`func (o *CreateConditionalOrderRequest) GetStopLossPrice() float64`

GetStopLossPrice returns the StopLossPrice field if non-nil, zero value otherwise.

### GetStopLossPriceOk

`func (o *CreateConditionalOrderRequest) GetStopLossPriceOk() (*float64, bool)`

GetStopLossPriceOk returns a tuple with the StopLossPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopLossPrice

`func (o *CreateConditionalOrderRequest) SetStopLossPrice(v float64)`

SetStopLossPrice sets StopLossPrice field to given value.

### HasStopLossPrice

`func (o *CreateConditionalOrderRequest) HasStopLossPrice() bool`

HasStopLossPrice returns a boolean if a field has been set.

### GetTakeProfitPrice

`func (o *CreateConditionalOrderRequest) GetTakeProfitPrice() float64`

GetTakeProfitPrice returns the TakeProfitPrice field if non-nil, zero value otherwise.

### GetTakeProfitPriceOk

`func (o *CreateConditionalOrderRequest) GetTakeProfitPriceOk() (*float64, bool)`

GetTakeProfitPriceOk returns a tuple with the TakeProfitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakeProfitPrice

`func (o *CreateConditionalOrderRequest) SetTakeProfitPrice(v float64)`

SetTakeProfitPrice sets TakeProfitPrice field to given value.

### HasTakeProfitPrice

`func (o *CreateConditionalOrderRequest) HasTakeProfitPrice() bool`

HasTakeProfitPrice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


