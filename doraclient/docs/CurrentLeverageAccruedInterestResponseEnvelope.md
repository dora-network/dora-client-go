# CurrentLeverageAccruedInterestResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**CurrentLeverageAccruedInterest**](CurrentLeverageAccruedInterest.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewCurrentLeverageAccruedInterestResponseEnvelope

`func NewCurrentLeverageAccruedInterestResponseEnvelope() *CurrentLeverageAccruedInterestResponseEnvelope`

NewCurrentLeverageAccruedInterestResponseEnvelope instantiates a new CurrentLeverageAccruedInterestResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentLeverageAccruedInterestResponseEnvelopeWithDefaults

`func NewCurrentLeverageAccruedInterestResponseEnvelopeWithDefaults() *CurrentLeverageAccruedInterestResponseEnvelope`

NewCurrentLeverageAccruedInterestResponseEnvelopeWithDefaults instantiates a new CurrentLeverageAccruedInterestResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) GetData() CurrentLeverageAccruedInterest`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) GetDataOk() (*CurrentLeverageAccruedInterest, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) SetData(v CurrentLeverageAccruedInterest)`

SetData sets Data field to given value.

### HasData

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CurrentLeverageAccruedInterestResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


