# ListPositionAccountsResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**PositionAccounts**](PositionAccounts.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewListPositionAccountsResponseEnvelope

`func NewListPositionAccountsResponseEnvelope() *ListPositionAccountsResponseEnvelope`

NewListPositionAccountsResponseEnvelope instantiates a new ListPositionAccountsResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListPositionAccountsResponseEnvelopeWithDefaults

`func NewListPositionAccountsResponseEnvelopeWithDefaults() *ListPositionAccountsResponseEnvelope`

NewListPositionAccountsResponseEnvelopeWithDefaults instantiates a new ListPositionAccountsResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListPositionAccountsResponseEnvelope) GetData() PositionAccounts`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListPositionAccountsResponseEnvelope) GetDataOk() (*PositionAccounts, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListPositionAccountsResponseEnvelope) SetData(v PositionAccounts)`

SetData sets Data field to given value.

### HasData

`func (o *ListPositionAccountsResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ListPositionAccountsResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListPositionAccountsResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListPositionAccountsResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ListPositionAccountsResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *ListPositionAccountsResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ListPositionAccountsResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ListPositionAccountsResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ListPositionAccountsResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


