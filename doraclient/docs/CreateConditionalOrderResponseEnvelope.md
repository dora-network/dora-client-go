# CreateConditionalOrderResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**CreateConditionalOrderResponseEnvelopeAllOfData**](CreateConditionalOrderResponseEnvelopeAllOfData.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewCreateConditionalOrderResponseEnvelope

`func NewCreateConditionalOrderResponseEnvelope(metadata Metadata, ) *CreateConditionalOrderResponseEnvelope`

NewCreateConditionalOrderResponseEnvelope instantiates a new CreateConditionalOrderResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateConditionalOrderResponseEnvelopeWithDefaults

`func NewCreateConditionalOrderResponseEnvelopeWithDefaults() *CreateConditionalOrderResponseEnvelope`

NewCreateConditionalOrderResponseEnvelopeWithDefaults instantiates a new CreateConditionalOrderResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CreateConditionalOrderResponseEnvelope) GetData() CreateConditionalOrderResponseEnvelopeAllOfData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateConditionalOrderResponseEnvelope) GetDataOk() (*CreateConditionalOrderResponseEnvelopeAllOfData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateConditionalOrderResponseEnvelope) SetData(v CreateConditionalOrderResponseEnvelopeAllOfData)`

SetData sets Data field to given value.

### HasData

`func (o *CreateConditionalOrderResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *CreateConditionalOrderResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CreateConditionalOrderResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CreateConditionalOrderResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *CreateConditionalOrderResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateConditionalOrderResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateConditionalOrderResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateConditionalOrderResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


