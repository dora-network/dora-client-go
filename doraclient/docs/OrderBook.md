# OrderBook

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | Pointer to **string** |  | [optional] 
**BaseQuantity** | Pointer to **float32** |  | [optional] 
**BaseAssetId** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**DisplayName** | Pointer to **string** |  | [optional] 
**FeeFactor** | Pointer to **float32** |  | [optional] 
**InitialAssetsRatio** | Pointer to **float32** |  | [optional] 
**MaturityAt** | Pointer to **time.Time** |  | [optional] 
**QuoteQuantity** | Pointer to **float32** |  | [optional] 
**QuoteAssetId** | Pointer to **string** |  | [optional] 
**SharesQuantity** | Pointer to **float32** |  | [optional] 
**Status** | Pointer to [**OrderBookStatus**](OrderBookStatus.md) |  | [optional] 
**TickSize** | Pointer to **float32** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**HaltedAt** | Pointer to **time.Time** |  | [optional] 
**TerminatedAt** | Pointer to **time.Time** |  | [optional] 
**PoolUpdatedAt** | Pointer to **time.Time** |  | [optional] 
**SharesAssetId** | Pointer to **string** |  | [optional] 

## Methods

### NewOrderBook

`func NewOrderBook() *OrderBook`

NewOrderBook instantiates a new OrderBook object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderBookWithDefaults

`func NewOrderBookWithDefaults() *OrderBook`

NewOrderBookWithDefaults instantiates a new OrderBook object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *OrderBook) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *OrderBook) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *OrderBook) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.

### HasOrderBookId

`func (o *OrderBook) HasOrderBookId() bool`

HasOrderBookId returns a boolean if a field has been set.

### GetBaseQuantity

`func (o *OrderBook) GetBaseQuantity() float32`

GetBaseQuantity returns the BaseQuantity field if non-nil, zero value otherwise.

### GetBaseQuantityOk

`func (o *OrderBook) GetBaseQuantityOk() (*float32, bool)`

GetBaseQuantityOk returns a tuple with the BaseQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseQuantity

`func (o *OrderBook) SetBaseQuantity(v float32)`

SetBaseQuantity sets BaseQuantity field to given value.

### HasBaseQuantity

`func (o *OrderBook) HasBaseQuantity() bool`

HasBaseQuantity returns a boolean if a field has been set.

### GetBaseAssetId

`func (o *OrderBook) GetBaseAssetId() string`

GetBaseAssetId returns the BaseAssetId field if non-nil, zero value otherwise.

### GetBaseAssetIdOk

`func (o *OrderBook) GetBaseAssetIdOk() (*string, bool)`

GetBaseAssetIdOk returns a tuple with the BaseAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseAssetId

`func (o *OrderBook) SetBaseAssetId(v string)`

SetBaseAssetId sets BaseAssetId field to given value.

### HasBaseAssetId

`func (o *OrderBook) HasBaseAssetId() bool`

HasBaseAssetId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OrderBook) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OrderBook) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OrderBook) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *OrderBook) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDisplayName

`func (o *OrderBook) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *OrderBook) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *OrderBook) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *OrderBook) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetFeeFactor

`func (o *OrderBook) GetFeeFactor() float32`

GetFeeFactor returns the FeeFactor field if non-nil, zero value otherwise.

### GetFeeFactorOk

`func (o *OrderBook) GetFeeFactorOk() (*float32, bool)`

GetFeeFactorOk returns a tuple with the FeeFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeFactor

`func (o *OrderBook) SetFeeFactor(v float32)`

SetFeeFactor sets FeeFactor field to given value.

### HasFeeFactor

`func (o *OrderBook) HasFeeFactor() bool`

HasFeeFactor returns a boolean if a field has been set.

### GetInitialAssetsRatio

`func (o *OrderBook) GetInitialAssetsRatio() float32`

GetInitialAssetsRatio returns the InitialAssetsRatio field if non-nil, zero value otherwise.

### GetInitialAssetsRatioOk

`func (o *OrderBook) GetInitialAssetsRatioOk() (*float32, bool)`

GetInitialAssetsRatioOk returns a tuple with the InitialAssetsRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialAssetsRatio

`func (o *OrderBook) SetInitialAssetsRatio(v float32)`

SetInitialAssetsRatio sets InitialAssetsRatio field to given value.

### HasInitialAssetsRatio

`func (o *OrderBook) HasInitialAssetsRatio() bool`

HasInitialAssetsRatio returns a boolean if a field has been set.

### GetMaturityAt

`func (o *OrderBook) GetMaturityAt() time.Time`

GetMaturityAt returns the MaturityAt field if non-nil, zero value otherwise.

### GetMaturityAtOk

`func (o *OrderBook) GetMaturityAtOk() (*time.Time, bool)`

GetMaturityAtOk returns a tuple with the MaturityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaturityAt

`func (o *OrderBook) SetMaturityAt(v time.Time)`

SetMaturityAt sets MaturityAt field to given value.

### HasMaturityAt

`func (o *OrderBook) HasMaturityAt() bool`

HasMaturityAt returns a boolean if a field has been set.

### GetQuoteQuantity

`func (o *OrderBook) GetQuoteQuantity() float32`

GetQuoteQuantity returns the QuoteQuantity field if non-nil, zero value otherwise.

### GetQuoteQuantityOk

`func (o *OrderBook) GetQuoteQuantityOk() (*float32, bool)`

GetQuoteQuantityOk returns a tuple with the QuoteQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteQuantity

`func (o *OrderBook) SetQuoteQuantity(v float32)`

SetQuoteQuantity sets QuoteQuantity field to given value.

### HasQuoteQuantity

`func (o *OrderBook) HasQuoteQuantity() bool`

HasQuoteQuantity returns a boolean if a field has been set.

### GetQuoteAssetId

`func (o *OrderBook) GetQuoteAssetId() string`

GetQuoteAssetId returns the QuoteAssetId field if non-nil, zero value otherwise.

### GetQuoteAssetIdOk

`func (o *OrderBook) GetQuoteAssetIdOk() (*string, bool)`

GetQuoteAssetIdOk returns a tuple with the QuoteAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteAssetId

`func (o *OrderBook) SetQuoteAssetId(v string)`

SetQuoteAssetId sets QuoteAssetId field to given value.

### HasQuoteAssetId

`func (o *OrderBook) HasQuoteAssetId() bool`

HasQuoteAssetId returns a boolean if a field has been set.

### GetSharesQuantity

`func (o *OrderBook) GetSharesQuantity() float32`

GetSharesQuantity returns the SharesQuantity field if non-nil, zero value otherwise.

### GetSharesQuantityOk

`func (o *OrderBook) GetSharesQuantityOk() (*float32, bool)`

GetSharesQuantityOk returns a tuple with the SharesQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharesQuantity

`func (o *OrderBook) SetSharesQuantity(v float32)`

SetSharesQuantity sets SharesQuantity field to given value.

### HasSharesQuantity

`func (o *OrderBook) HasSharesQuantity() bool`

HasSharesQuantity returns a boolean if a field has been set.

### GetStatus

`func (o *OrderBook) GetStatus() OrderBookStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrderBook) GetStatusOk() (*OrderBookStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrderBook) SetStatus(v OrderBookStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OrderBook) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTickSize

`func (o *OrderBook) GetTickSize() float32`

GetTickSize returns the TickSize field if non-nil, zero value otherwise.

### GetTickSizeOk

`func (o *OrderBook) GetTickSizeOk() (*float32, bool)`

GetTickSizeOk returns a tuple with the TickSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTickSize

`func (o *OrderBook) SetTickSize(v float32)`

SetTickSize sets TickSize field to given value.

### HasTickSize

`func (o *OrderBook) HasTickSize() bool`

HasTickSize returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *OrderBook) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OrderBook) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OrderBook) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *OrderBook) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetHaltedAt

`func (o *OrderBook) GetHaltedAt() time.Time`

GetHaltedAt returns the HaltedAt field if non-nil, zero value otherwise.

### GetHaltedAtOk

`func (o *OrderBook) GetHaltedAtOk() (*time.Time, bool)`

GetHaltedAtOk returns a tuple with the HaltedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHaltedAt

`func (o *OrderBook) SetHaltedAt(v time.Time)`

SetHaltedAt sets HaltedAt field to given value.

### HasHaltedAt

`func (o *OrderBook) HasHaltedAt() bool`

HasHaltedAt returns a boolean if a field has been set.

### GetTerminatedAt

`func (o *OrderBook) GetTerminatedAt() time.Time`

GetTerminatedAt returns the TerminatedAt field if non-nil, zero value otherwise.

### GetTerminatedAtOk

`func (o *OrderBook) GetTerminatedAtOk() (*time.Time, bool)`

GetTerminatedAtOk returns a tuple with the TerminatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerminatedAt

`func (o *OrderBook) SetTerminatedAt(v time.Time)`

SetTerminatedAt sets TerminatedAt field to given value.

### HasTerminatedAt

`func (o *OrderBook) HasTerminatedAt() bool`

HasTerminatedAt returns a boolean if a field has been set.

### GetPoolUpdatedAt

`func (o *OrderBook) GetPoolUpdatedAt() time.Time`

GetPoolUpdatedAt returns the PoolUpdatedAt field if non-nil, zero value otherwise.

### GetPoolUpdatedAtOk

`func (o *OrderBook) GetPoolUpdatedAtOk() (*time.Time, bool)`

GetPoolUpdatedAtOk returns a tuple with the PoolUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolUpdatedAt

`func (o *OrderBook) SetPoolUpdatedAt(v time.Time)`

SetPoolUpdatedAt sets PoolUpdatedAt field to given value.

### HasPoolUpdatedAt

`func (o *OrderBook) HasPoolUpdatedAt() bool`

HasPoolUpdatedAt returns a boolean if a field has been set.

### GetSharesAssetId

`func (o *OrderBook) GetSharesAssetId() string`

GetSharesAssetId returns the SharesAssetId field if non-nil, zero value otherwise.

### GetSharesAssetIdOk

`func (o *OrderBook) GetSharesAssetIdOk() (*string, bool)`

GetSharesAssetIdOk returns a tuple with the SharesAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharesAssetId

`func (o *OrderBook) SetSharesAssetId(v string)`

SetSharesAssetId sets SharesAssetId field to given value.

### HasSharesAssetId

`func (o *OrderBook) HasSharesAssetId() bool`

HasSharesAssetId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


