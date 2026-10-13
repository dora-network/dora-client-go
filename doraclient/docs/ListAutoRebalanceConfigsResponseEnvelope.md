# ListAutoRebalanceConfigsResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**AutoRebalanceConfigsData**](AutoRebalanceConfigsData.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewListAutoRebalanceConfigsResponseEnvelope

`func NewListAutoRebalanceConfigsResponseEnvelope(metadata Metadata, ) *ListAutoRebalanceConfigsResponseEnvelope`

NewListAutoRebalanceConfigsResponseEnvelope instantiates a new ListAutoRebalanceConfigsResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAutoRebalanceConfigsResponseEnvelopeWithDefaults

`func NewListAutoRebalanceConfigsResponseEnvelopeWithDefaults() *ListAutoRebalanceConfigsResponseEnvelope`

NewListAutoRebalanceConfigsResponseEnvelopeWithDefaults instantiates a new ListAutoRebalanceConfigsResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAutoRebalanceConfigsResponseEnvelope) GetData() AutoRebalanceConfigsData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAutoRebalanceConfigsResponseEnvelope) GetDataOk() (*AutoRebalanceConfigsData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAutoRebalanceConfigsResponseEnvelope) SetData(v AutoRebalanceConfigsData)`

SetData sets Data field to given value.

### HasData

`func (o *ListAutoRebalanceConfigsResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ListAutoRebalanceConfigsResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListAutoRebalanceConfigsResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListAutoRebalanceConfigsResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ListAutoRebalanceConfigsResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *ListAutoRebalanceConfigsResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ListAutoRebalanceConfigsResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ListAutoRebalanceConfigsResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


