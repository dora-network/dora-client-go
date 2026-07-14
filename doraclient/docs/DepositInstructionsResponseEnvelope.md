# DepositInstructionsResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**DepositInstructionsResponse**](DepositInstructionsResponse.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewDepositInstructionsResponseEnvelope

`func NewDepositInstructionsResponseEnvelope(metadata Metadata, ) *DepositInstructionsResponseEnvelope`

NewDepositInstructionsResponseEnvelope instantiates a new DepositInstructionsResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDepositInstructionsResponseEnvelopeWithDefaults

`func NewDepositInstructionsResponseEnvelopeWithDefaults() *DepositInstructionsResponseEnvelope`

NewDepositInstructionsResponseEnvelopeWithDefaults instantiates a new DepositInstructionsResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DepositInstructionsResponseEnvelope) GetData() DepositInstructionsResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DepositInstructionsResponseEnvelope) GetDataOk() (*DepositInstructionsResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DepositInstructionsResponseEnvelope) SetData(v DepositInstructionsResponse)`

SetData sets Data field to given value.

### HasData

`func (o *DepositInstructionsResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *DepositInstructionsResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DepositInstructionsResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DepositInstructionsResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *DepositInstructionsResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *DepositInstructionsResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DepositInstructionsResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DepositInstructionsResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


