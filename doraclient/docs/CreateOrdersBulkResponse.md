# CreateOrdersBulkResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**CreateOrdersBulkResponseAllOfData**](CreateOrdersBulkResponseAllOfData.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewCreateOrdersBulkResponse

`func NewCreateOrdersBulkResponse(metadata Metadata, ) *CreateOrdersBulkResponse`

NewCreateOrdersBulkResponse instantiates a new CreateOrdersBulkResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrdersBulkResponseWithDefaults

`func NewCreateOrdersBulkResponseWithDefaults() *CreateOrdersBulkResponse`

NewCreateOrdersBulkResponseWithDefaults instantiates a new CreateOrdersBulkResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CreateOrdersBulkResponse) GetData() CreateOrdersBulkResponseAllOfData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateOrdersBulkResponse) GetDataOk() (*CreateOrdersBulkResponseAllOfData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateOrdersBulkResponse) SetData(v CreateOrdersBulkResponseAllOfData)`

SetData sets Data field to given value.

### HasData

`func (o *CreateOrdersBulkResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *CreateOrdersBulkResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CreateOrdersBulkResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CreateOrdersBulkResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *CreateOrdersBulkResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateOrdersBulkResponse) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateOrdersBulkResponse) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateOrdersBulkResponse) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


