# WithdrawalResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**WithdrawalResponse**](WithdrawalResponse.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewWithdrawalResponseEnvelope

`func NewWithdrawalResponseEnvelope(metadata Metadata, ) *WithdrawalResponseEnvelope`

NewWithdrawalResponseEnvelope instantiates a new WithdrawalResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawalResponseEnvelopeWithDefaults

`func NewWithdrawalResponseEnvelopeWithDefaults() *WithdrawalResponseEnvelope`

NewWithdrawalResponseEnvelopeWithDefaults instantiates a new WithdrawalResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *WithdrawalResponseEnvelope) GetData() WithdrawalResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *WithdrawalResponseEnvelope) GetDataOk() (*WithdrawalResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *WithdrawalResponseEnvelope) SetData(v WithdrawalResponse)`

SetData sets Data field to given value.

### HasData

`func (o *WithdrawalResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *WithdrawalResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *WithdrawalResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *WithdrawalResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *WithdrawalResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *WithdrawalResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *WithdrawalResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *WithdrawalResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


