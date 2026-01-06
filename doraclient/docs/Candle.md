# Candle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | Pointer to **string** |  | [optional] 
**StartTimestamp** | Pointer to **time.Time** |  | [optional] 
**Open** | Pointer to **float64** |  | [optional] 
**High** | Pointer to **float64** |  | [optional] 
**Low** | Pointer to **float64** |  | [optional] 
**Close** | Pointer to **float64** |  | [optional] 
**Volume** | Pointer to **float64** |  | [optional] 

## Methods

### NewCandle

`func NewCandle() *Candle`

NewCandle instantiates a new Candle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCandleWithDefaults

`func NewCandleWithDefaults() *Candle`

NewCandleWithDefaults instantiates a new Candle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBookId

`func (o *Candle) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *Candle) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *Candle) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.

### HasOrderBookId

`func (o *Candle) HasOrderBookId() bool`

HasOrderBookId returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *Candle) GetStartTimestamp() time.Time`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *Candle) GetStartTimestampOk() (*time.Time, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *Candle) SetStartTimestamp(v time.Time)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *Candle) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetOpen

`func (o *Candle) GetOpen() float64`

GetOpen returns the Open field if non-nil, zero value otherwise.

### GetOpenOk

`func (o *Candle) GetOpenOk() (*float64, bool)`

GetOpenOk returns a tuple with the Open field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpen

`func (o *Candle) SetOpen(v float64)`

SetOpen sets Open field to given value.

### HasOpen

`func (o *Candle) HasOpen() bool`

HasOpen returns a boolean if a field has been set.

### GetHigh

`func (o *Candle) GetHigh() float64`

GetHigh returns the High field if non-nil, zero value otherwise.

### GetHighOk

`func (o *Candle) GetHighOk() (*float64, bool)`

GetHighOk returns a tuple with the High field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHigh

`func (o *Candle) SetHigh(v float64)`

SetHigh sets High field to given value.

### HasHigh

`func (o *Candle) HasHigh() bool`

HasHigh returns a boolean if a field has been set.

### GetLow

`func (o *Candle) GetLow() float64`

GetLow returns the Low field if non-nil, zero value otherwise.

### GetLowOk

`func (o *Candle) GetLowOk() (*float64, bool)`

GetLowOk returns a tuple with the Low field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLow

`func (o *Candle) SetLow(v float64)`

SetLow sets Low field to given value.

### HasLow

`func (o *Candle) HasLow() bool`

HasLow returns a boolean if a field has been set.

### GetClose

`func (o *Candle) GetClose() float64`

GetClose returns the Close field if non-nil, zero value otherwise.

### GetCloseOk

`func (o *Candle) GetCloseOk() (*float64, bool)`

GetCloseOk returns a tuple with the Close field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClose

`func (o *Candle) SetClose(v float64)`

SetClose sets Close field to given value.

### HasClose

`func (o *Candle) HasClose() bool`

HasClose returns a boolean if a field has been set.

### GetVolume

`func (o *Candle) GetVolume() float64`

GetVolume returns the Volume field if non-nil, zero value otherwise.

### GetVolumeOk

`func (o *Candle) GetVolumeOk() (*float64, bool)`

GetVolumeOk returns a tuple with the Volume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume

`func (o *Candle) SetVolume(v float64)`

SetVolume sets Volume field to given value.

### HasVolume

`func (o *Candle) HasVolume() bool`

HasVolume returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


