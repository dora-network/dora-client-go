# ListAccountsResponseV2Envelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]AccountSummaryV2**](AccountSummaryV2.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewListAccountsResponseV2Envelope

`func NewListAccountsResponseV2Envelope(metadata Metadata, ) *ListAccountsResponseV2Envelope`

NewListAccountsResponseV2Envelope instantiates a new ListAccountsResponseV2Envelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAccountsResponseV2EnvelopeWithDefaults

`func NewListAccountsResponseV2EnvelopeWithDefaults() *ListAccountsResponseV2Envelope`

NewListAccountsResponseV2EnvelopeWithDefaults instantiates a new ListAccountsResponseV2Envelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAccountsResponseV2Envelope) GetData() []AccountSummaryV2`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAccountsResponseV2Envelope) GetDataOk() (*[]AccountSummaryV2, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAccountsResponseV2Envelope) SetData(v []AccountSummaryV2)`

SetData sets Data field to given value.

### HasData

`func (o *ListAccountsResponseV2Envelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ListAccountsResponseV2Envelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListAccountsResponseV2Envelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListAccountsResponseV2Envelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ListAccountsResponseV2Envelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *ListAccountsResponseV2Envelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ListAccountsResponseV2Envelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ListAccountsResponseV2Envelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


