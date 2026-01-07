# StreamOrdersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StreamOrdersEntry** | Pointer to [**[]StreamOrdersEntry**](StreamOrdersEntry.md) |  | [optional] 

## Methods

### NewStreamOrdersResponse

`func NewStreamOrdersResponse() *StreamOrdersResponse`

NewStreamOrdersResponse instantiates a new StreamOrdersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamOrdersResponseWithDefaults

`func NewStreamOrdersResponseWithDefaults() *StreamOrdersResponse`

NewStreamOrdersResponseWithDefaults instantiates a new StreamOrdersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStreamOrdersEntry

`func (o *StreamOrdersResponse) GetStreamOrdersEntry() []StreamOrdersEntry`

GetStreamOrdersEntry returns the StreamOrdersEntry field if non-nil, zero value otherwise.

### GetStreamOrdersEntryOk

`func (o *StreamOrdersResponse) GetStreamOrdersEntryOk() (*[]StreamOrdersEntry, bool)`

GetStreamOrdersEntryOk returns a tuple with the StreamOrdersEntry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreamOrdersEntry

`func (o *StreamOrdersResponse) SetStreamOrdersEntry(v []StreamOrdersEntry)`

SetStreamOrdersEntry sets StreamOrdersEntry field to given value.

### HasStreamOrdersEntry

`func (o *StreamOrdersResponse) HasStreamOrdersEntry() bool`

HasStreamOrdersEntry returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


