# LedgerAccountsResponseV2Envelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**AccountPortfolioResponseV2**](AccountPortfolioResponseV2.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewLedgerAccountsResponseV2Envelope

`func NewLedgerAccountsResponseV2Envelope(metadata Metadata, ) *LedgerAccountsResponseV2Envelope`

NewLedgerAccountsResponseV2Envelope instantiates a new LedgerAccountsResponseV2Envelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLedgerAccountsResponseV2EnvelopeWithDefaults

`func NewLedgerAccountsResponseV2EnvelopeWithDefaults() *LedgerAccountsResponseV2Envelope`

NewLedgerAccountsResponseV2EnvelopeWithDefaults instantiates a new LedgerAccountsResponseV2Envelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *LedgerAccountsResponseV2Envelope) GetData() AccountPortfolioResponseV2`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *LedgerAccountsResponseV2Envelope) GetDataOk() (*AccountPortfolioResponseV2, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *LedgerAccountsResponseV2Envelope) SetData(v AccountPortfolioResponseV2)`

SetData sets Data field to given value.

### HasData

`func (o *LedgerAccountsResponseV2Envelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *LedgerAccountsResponseV2Envelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *LedgerAccountsResponseV2Envelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *LedgerAccountsResponseV2Envelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *LedgerAccountsResponseV2Envelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *LedgerAccountsResponseV2Envelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LedgerAccountsResponseV2Envelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LedgerAccountsResponseV2Envelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


