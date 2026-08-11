# CashReserveResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**CashReserveResponse**](CashReserveResponse.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewCashReserveResponseEnvelope

`func NewCashReserveResponseEnvelope(metadata Metadata, ) *CashReserveResponseEnvelope`

NewCashReserveResponseEnvelope instantiates a new CashReserveResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCashReserveResponseEnvelopeWithDefaults

`func NewCashReserveResponseEnvelopeWithDefaults() *CashReserveResponseEnvelope`

NewCashReserveResponseEnvelopeWithDefaults instantiates a new CashReserveResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CashReserveResponseEnvelope) GetData() CashReserveResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CashReserveResponseEnvelope) GetDataOk() (*CashReserveResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CashReserveResponseEnvelope) SetData(v CashReserveResponse)`

SetData sets Data field to given value.

### HasData

`func (o *CashReserveResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *CashReserveResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CashReserveResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CashReserveResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *CashReserveResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *CashReserveResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CashReserveResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CashReserveResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


