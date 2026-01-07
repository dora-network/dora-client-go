# StreamTransactionsEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Val** | Pointer to [**Transaction**](Transaction.md) |  | [optional] 
**Time** | Pointer to **time.Time** | The timestamp when the data was created | [optional] 

## Methods

### NewStreamTransactionsEntry

`func NewStreamTransactionsEntry() *StreamTransactionsEntry`

NewStreamTransactionsEntry instantiates a new StreamTransactionsEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamTransactionsEntryWithDefaults

`func NewStreamTransactionsEntryWithDefaults() *StreamTransactionsEntry`

NewStreamTransactionsEntryWithDefaults instantiates a new StreamTransactionsEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVal

`func (o *StreamTransactionsEntry) GetVal() Transaction`

GetVal returns the Val field if non-nil, zero value otherwise.

### GetValOk

`func (o *StreamTransactionsEntry) GetValOk() (*Transaction, bool)`

GetValOk returns a tuple with the Val field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVal

`func (o *StreamTransactionsEntry) SetVal(v Transaction)`

SetVal sets Val field to given value.

### HasVal

`func (o *StreamTransactionsEntry) HasVal() bool`

HasVal returns a boolean if a field has been set.

### GetTime

`func (o *StreamTransactionsEntry) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *StreamTransactionsEntry) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *StreamTransactionsEntry) SetTime(v time.Time)`

SetTime sets Time field to given value.

### HasTime

`func (o *StreamTransactionsEntry) HasTime() bool`

HasTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


