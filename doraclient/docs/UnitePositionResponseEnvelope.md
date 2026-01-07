# UnitePositionResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**UnitedPosition**](UnitedPosition.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewUnitePositionResponseEnvelope

`func NewUnitePositionResponseEnvelope() *UnitePositionResponseEnvelope`

NewUnitePositionResponseEnvelope instantiates a new UnitePositionResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUnitePositionResponseEnvelopeWithDefaults

`func NewUnitePositionResponseEnvelopeWithDefaults() *UnitePositionResponseEnvelope`

NewUnitePositionResponseEnvelopeWithDefaults instantiates a new UnitePositionResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *UnitePositionResponseEnvelope) GetData() UnitedPosition`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UnitePositionResponseEnvelope) GetDataOk() (*UnitedPosition, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UnitePositionResponseEnvelope) SetData(v UnitedPosition)`

SetData sets Data field to given value.

### HasData

`func (o *UnitePositionResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *UnitePositionResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UnitePositionResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UnitePositionResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *UnitePositionResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *UnitePositionResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *UnitePositionResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *UnitePositionResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *UnitePositionResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


