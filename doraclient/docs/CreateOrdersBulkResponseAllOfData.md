# CreateOrdersBulkResponseAllOfData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | Pointer to **int32** |  | [optional] 
**Rejected** | Pointer to **int32** |  | [optional] 
**Results** | Pointer to [**[]BulkOrderResult**](BulkOrderResult.md) |  | [optional] 

## Methods

### NewCreateOrdersBulkResponseAllOfData

`func NewCreateOrdersBulkResponseAllOfData() *CreateOrdersBulkResponseAllOfData`

NewCreateOrdersBulkResponseAllOfData instantiates a new CreateOrdersBulkResponseAllOfData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrdersBulkResponseAllOfDataWithDefaults

`func NewCreateOrdersBulkResponseAllOfDataWithDefaults() *CreateOrdersBulkResponseAllOfData`

NewCreateOrdersBulkResponseAllOfDataWithDefaults instantiates a new CreateOrdersBulkResponseAllOfData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *CreateOrdersBulkResponseAllOfData) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateOrdersBulkResponseAllOfData) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateOrdersBulkResponseAllOfData) SetCreated(v int32)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *CreateOrdersBulkResponseAllOfData) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetRejected

`func (o *CreateOrdersBulkResponseAllOfData) GetRejected() int32`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *CreateOrdersBulkResponseAllOfData) GetRejectedOk() (*int32, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *CreateOrdersBulkResponseAllOfData) SetRejected(v int32)`

SetRejected sets Rejected field to given value.

### HasRejected

`func (o *CreateOrdersBulkResponseAllOfData) HasRejected() bool`

HasRejected returns a boolean if a field has been set.

### GetResults

`func (o *CreateOrdersBulkResponseAllOfData) GetResults() []BulkOrderResult`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *CreateOrdersBulkResponseAllOfData) GetResultsOk() (*[]BulkOrderResult, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *CreateOrdersBulkResponseAllOfData) SetResults(v []BulkOrderResult)`

SetResults sets Results field to given value.

### HasResults

`func (o *CreateOrdersBulkResponseAllOfData) HasResults() bool`

HasResults returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


