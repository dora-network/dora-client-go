# Candle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBookId** | **string** |  | 
**StartTimestamp** | **time.Time** |  | 
**Open** | **string** |  | 
**High** | **string** |  | 
**Low** | **string** |  | 
**Close** | **string** |  | 
**Ytm** | Pointer to **string** | DEPRECATED: Use close_ytm instead. | [optional] 
**OpenYtm** | **string** |  | 
**CloseYtm** | **string** |  | 
**HighYtm** | **string** |  | 
**LowYtm** | **string** |  | 
**Volume** | **string** |  | 

## Methods

### NewCandle

`func NewCandle(orderBookId string, startTimestamp time.Time, open string, high string, low string, close string, openYtm string, closeYtm string, highYtm string, lowYtm string, volume string, ) *Candle`

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

`func (o *Candle) GetOpen() string`

GetOpen returns the Open field if non-nil, zero value otherwise.

### GetOpenOk

`func (o *Candle) GetOpenOk() (*string, bool)`

GetOpenOk returns a tuple with the Open field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpen

`func (o *Candle) SetOpen(v string)`

SetOpen sets Open field to given value.


### GetHigh

`func (o *Candle) GetHigh() string`

GetHigh returns the High field if non-nil, zero value otherwise.

### GetHighOk

`func (o *Candle) GetHighOk() (*string, bool)`

GetHighOk returns a tuple with the High field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHigh

`func (o *Candle) SetHigh(v string)`

SetHigh sets High field to given value.


### GetLow

`func (o *Candle) GetLow() string`

GetLow returns the Low field if non-nil, zero value otherwise.

### GetLowOk

`func (o *Candle) GetLowOk() (*string, bool)`

GetLowOk returns a tuple with the Low field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLow

`func (o *Candle) SetLow(v string)`

SetLow sets Low field to given value.


### GetClose

`func (o *Candle) GetClose() string`

GetClose returns the Close field if non-nil, zero value otherwise.

### GetCloseOk

`func (o *Candle) GetCloseOk() (*string, bool)`

GetCloseOk returns a tuple with the Close field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClose

`func (o *Candle) SetClose(v string)`

SetClose sets Close field to given value.


### GetYtm

`func (o *Candle) GetYtm() string`

GetYtm returns the Ytm field if non-nil, zero value otherwise.

### GetYtmOk

`func (o *Candle) GetYtmOk() (*string, bool)`

GetYtmOk returns a tuple with the Ytm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYtm

`func (o *Candle) SetYtm(v string)`

SetYtm sets Ytm field to given value.

### HasYtm

`func (o *Candle) HasYtm() bool`

HasYtm returns a boolean if a field has been set.

### GetOpenYtm

`func (o *Candle) GetOpenYtm() string`

GetOpenYtm returns the OpenYtm field if non-nil, zero value otherwise.

### GetOpenYtmOk

`func (o *Candle) GetOpenYtmOk() (*string, bool)`

GetOpenYtmOk returns a tuple with the OpenYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenYtm

`func (o *Candle) SetOpenYtm(v string)`

SetOpenYtm sets OpenYtm field to given value.


### GetCloseYtm

`func (o *Candle) GetCloseYtm() string`

GetCloseYtm returns the CloseYtm field if non-nil, zero value otherwise.

### GetCloseYtmOk

`func (o *Candle) GetCloseYtmOk() (*string, bool)`

GetCloseYtmOk returns a tuple with the CloseYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloseYtm

`func (o *Candle) SetCloseYtm(v string)`

SetCloseYtm sets CloseYtm field to given value.


### GetHighYtm

`func (o *Candle) GetHighYtm() string`

GetHighYtm returns the HighYtm field if non-nil, zero value otherwise.

### GetHighYtmOk

`func (o *Candle) GetHighYtmOk() (*string, bool)`

GetHighYtmOk returns a tuple with the HighYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighYtm

`func (o *Candle) SetHighYtm(v string)`

SetHighYtm sets HighYtm field to given value.


### GetLowYtm

`func (o *Candle) GetLowYtm() string`

GetLowYtm returns the LowYtm field if non-nil, zero value otherwise.

### GetLowYtmOk

`func (o *Candle) GetLowYtmOk() (*string, bool)`

GetLowYtmOk returns a tuple with the LowYtm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLowYtm

`func (o *Candle) SetLowYtm(v string)`

SetLowYtm sets LowYtm field to given value.


### GetVolume

`func (o *Candle) GetVolume() string`

GetVolume returns the Volume field if non-nil, zero value otherwise.

### GetVolumeOk

`func (o *Candle) GetVolumeOk() (*string, bool)`

GetVolumeOk returns a tuple with the Volume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume

`func (o *Candle) SetVolume(v string)`

SetVolume sets Volume field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


