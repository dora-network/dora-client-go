# ClaimLeverageAccruedInterestResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**ClaimLeverageAccruedInterest**](ClaimLeverageAccruedInterest.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewClaimLeverageAccruedInterestResponseEnvelope

`func NewClaimLeverageAccruedInterestResponseEnvelope() *ClaimLeverageAccruedInterestResponseEnvelope`

NewClaimLeverageAccruedInterestResponseEnvelope instantiates a new ClaimLeverageAccruedInterestResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClaimLeverageAccruedInterestResponseEnvelopeWithDefaults

`func NewClaimLeverageAccruedInterestResponseEnvelopeWithDefaults() *ClaimLeverageAccruedInterestResponseEnvelope`

NewClaimLeverageAccruedInterestResponseEnvelopeWithDefaults instantiates a new ClaimLeverageAccruedInterestResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) GetData() ClaimLeverageAccruedInterest`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) GetDataOk() (*ClaimLeverageAccruedInterest, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) SetData(v ClaimLeverageAccruedInterest)`

SetData sets Data field to given value.

### HasData

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ClaimLeverageAccruedInterestResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


