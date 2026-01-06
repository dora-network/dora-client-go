# LedgerModuleResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]LeverageModuleResponse**](LeverageModuleResponse.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) |  | [optional] 

## Methods

### NewLedgerModuleResponseEnvelope

`func NewLedgerModuleResponseEnvelope() *LedgerModuleResponseEnvelope`

NewLedgerModuleResponseEnvelope instantiates a new LedgerModuleResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLedgerModuleResponseEnvelopeWithDefaults

`func NewLedgerModuleResponseEnvelopeWithDefaults() *LedgerModuleResponseEnvelope`

NewLedgerModuleResponseEnvelopeWithDefaults instantiates a new LedgerModuleResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *LedgerModuleResponseEnvelope) GetData() []LeverageModuleResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *LedgerModuleResponseEnvelope) GetDataOk() (*[]LeverageModuleResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *LedgerModuleResponseEnvelope) SetData(v []LeverageModuleResponse)`

SetData sets Data field to given value.

### HasData

`func (o *LedgerModuleResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *LedgerModuleResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *LedgerModuleResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *LedgerModuleResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *LedgerModuleResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *LedgerModuleResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LedgerModuleResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LedgerModuleResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LedgerModuleResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


