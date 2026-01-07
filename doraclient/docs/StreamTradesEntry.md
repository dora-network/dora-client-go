# StreamTradesEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Val** | Pointer to [**Trade**](Trade.md) |  | [optional] 
**Time** | Pointer to **time.Time** | The timestamp when the data was created | [optional] 

## Methods

### NewStreamTradesEntry

`func NewStreamTradesEntry() *StreamTradesEntry`

NewStreamTradesEntry instantiates a new StreamTradesEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamTradesEntryWithDefaults

`func NewStreamTradesEntryWithDefaults() *StreamTradesEntry`

NewStreamTradesEntryWithDefaults instantiates a new StreamTradesEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVal

`func (o *StreamTradesEntry) GetVal() Trade`

GetVal returns the Val field if non-nil, zero value otherwise.

### GetValOk

`func (o *StreamTradesEntry) GetValOk() (*Trade, bool)`

GetValOk returns a tuple with the Val field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVal

`func (o *StreamTradesEntry) SetVal(v Trade)`

SetVal sets Val field to given value.

### HasVal

`func (o *StreamTradesEntry) HasVal() bool`

HasVal returns a boolean if a field has been set.

### GetTime

`func (o *StreamTradesEntry) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *StreamTradesEntry) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *StreamTradesEntry) SetTime(v time.Time)`

SetTime sets Time field to given value.

### HasTime

`func (o *StreamTradesEntry) HasTime() bool`

HasTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


