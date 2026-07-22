# Candle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | **string** |  | 
**StartTimestamp** | **time.Time** |  | 
**Open** | **float64** |  | 
**High** | **float64** |  | 
**Low** | **float64** |  | 
**Close** | **float64** |  | 
**Ytm** | Pointer to **float64** | DEPRECATED: Use close_ytm instead. | [optional] 
**OpenYtm** | **float64** |  | 
**CloseYtm** | **float64** |  | 
**HighYtm** | **float64** |  | 
**LowYtm** | **float64** |  | 
**Volume** | **float64** |  | 

## Methods

### NewCandle

`func NewCandle(orderBookId string, startTimestamp time.Time, open float64, high float64, low float64, close float64, openYtm float64, closeYtm float64, highYtm float64, lowYtm float64, volume float64, ) *Candle`

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


### GetYtm

`func (o *Candle) GetYtm() float64`

GetYtm returns the Ytm field if non-nil, zero value otherwise.

### GetYtmOk

`func (o *Candle) GetYtmOk() (*float64, bool)`

GetYtmOk returns a tuple with the Ytm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYtm

`func (o *Candle) SetYtm(v float64)`

SetYtm sets Ytm field to given value.

### HasYtm

`func (o *Candle) HasYtm() bool`

HasYtm returns a boolean if a field has been set.

### GetOpenYtm

`func (o *Candle) GetOpenYtm() float64`

GetOpenYtm returns the OpenYtm field if non-nil, zero value otherwise.

### GetOpenYtmOk

`func (o *Candle) GetOpenYtmOk() (*float64, bool)`

GetOpenYtmOk returns a tuple with the OpenYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenYtm

`func (o *Candle) SetOpenYtm(v float64)`

SetOpenYtm sets OpenYtm field to given value.


### GetCloseYtm

`func (o *Candle) GetCloseYtm() float64`

GetCloseYtm returns the CloseYtm field if non-nil, zero value otherwise.

### GetCloseYtmOk

`func (o *Candle) GetCloseYtmOk() (*float64, bool)`

GetCloseYtmOk returns a tuple with the CloseYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloseYtm

`func (o *Candle) SetCloseYtm(v float64)`

SetCloseYtm sets CloseYtm field to given value.


### GetHighYtm

`func (o *Candle) GetHighYtm() float64`

GetHighYtm returns the HighYtm field if non-nil, zero value otherwise.

### GetHighYtmOk

`func (o *Candle) GetHighYtmOk() (*float64, bool)`

GetHighYtmOk returns a tuple with the HighYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighYtm

`func (o *Candle) SetHighYtm(v float64)`

SetHighYtm sets HighYtm field to given value.


### GetLowYtm

`func (o *Candle) GetLowYtm() float64`

GetLowYtm returns the LowYtm field if non-nil, zero value otherwise.

### GetLowYtmOk

`func (o *Candle) GetLowYtmOk() (*float64, bool)`

GetLowYtmOk returns a tuple with the LowYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLowYtm

`func (o *Candle) SetLowYtm(v float64)`

SetLowYtm sets LowYtm field to given value.


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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


