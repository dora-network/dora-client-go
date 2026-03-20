# AllPositionsResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**AllPositions**](AllPositions.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewAllPositionsResponseEnvelope

`func NewAllPositionsResponseEnvelope(metadata Metadata, ) *AllPositionsResponseEnvelope`

NewAllPositionsResponseEnvelope instantiates a new AllPositionsResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAllPositionsResponseEnvelopeWithDefaults

`func NewAllPositionsResponseEnvelopeWithDefaults() *AllPositionsResponseEnvelope`

NewAllPositionsResponseEnvelopeWithDefaults instantiates a new AllPositionsResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AllPositionsResponseEnvelope) GetData() AllPositions`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AllPositionsResponseEnvelope) GetDataOk() (*AllPositions, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AllPositionsResponseEnvelope) SetData(v AllPositions)`

SetData sets Data field to given value.

### HasData

`func (o *AllPositionsResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *AllPositionsResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AllPositionsResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AllPositionsResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *AllPositionsResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *AllPositionsResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AllPositionsResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AllPositionsResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


