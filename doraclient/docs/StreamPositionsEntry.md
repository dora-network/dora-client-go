# StreamPositionsEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Val** | [**Position**](Position.md) |  | 
**Time** | **time.Time** | The timestamp when the data was created | 

## Methods

### NewStreamPositionsEntry

`func NewStreamPositionsEntry(val Position, time time.Time, ) *StreamPositionsEntry`

NewStreamPositionsEntry instantiates a new StreamPositionsEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamPositionsEntryWithDefaults

`func NewStreamPositionsEntryWithDefaults() *StreamPositionsEntry`

NewStreamPositionsEntryWithDefaults instantiates a new StreamPositionsEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVal

`func (o *StreamPositionsEntry) GetVal() Position`

GetVal returns the Val field if non-nil, zero value otherwise.

### GetValOk

`func (o *StreamPositionsEntry) GetValOk() (*Position, bool)`

GetValOk returns a tuple with the Val field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVal

`func (o *StreamPositionsEntry) SetVal(v Position)`

SetVal sets Val field to given value.


### GetTime

`func (o *StreamPositionsEntry) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *StreamPositionsEntry) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *StreamPositionsEntry) SetTime(v time.Time)`

SetTime sets Time field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


