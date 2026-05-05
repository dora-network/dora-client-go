# NewIsolatedAccountResponseV2Envelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**AccountV2**](AccountV2.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewNewIsolatedAccountResponseV2Envelope

`func NewNewIsolatedAccountResponseV2Envelope(metadata Metadata, ) *NewIsolatedAccountResponseV2Envelope`

NewNewIsolatedAccountResponseV2Envelope instantiates a new NewIsolatedAccountResponseV2Envelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNewIsolatedAccountResponseV2EnvelopeWithDefaults

`func NewNewIsolatedAccountResponseV2EnvelopeWithDefaults() *NewIsolatedAccountResponseV2Envelope`

NewNewIsolatedAccountResponseV2EnvelopeWithDefaults instantiates a new NewIsolatedAccountResponseV2Envelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *NewIsolatedAccountResponseV2Envelope) GetData() AccountV2`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *NewIsolatedAccountResponseV2Envelope) GetDataOk() (*AccountV2, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *NewIsolatedAccountResponseV2Envelope) SetData(v AccountV2)`

SetData sets Data field to given value.

### HasData

`func (o *NewIsolatedAccountResponseV2Envelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *NewIsolatedAccountResponseV2Envelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *NewIsolatedAccountResponseV2Envelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *NewIsolatedAccountResponseV2Envelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *NewIsolatedAccountResponseV2Envelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *NewIsolatedAccountResponseV2Envelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *NewIsolatedAccountResponseV2Envelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *NewIsolatedAccountResponseV2Envelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


