# TradeResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**Trade**](Trade.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewTradeResponseEnvelope

`func NewTradeResponseEnvelope() *TradeResponseEnvelope`

NewTradeResponseEnvelope instantiates a new TradeResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradeResponseEnvelopeWithDefaults

`func NewTradeResponseEnvelopeWithDefaults() *TradeResponseEnvelope`

NewTradeResponseEnvelopeWithDefaults instantiates a new TradeResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TradeResponseEnvelope) GetData() Trade`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TradeResponseEnvelope) GetDataOk() (*Trade, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TradeResponseEnvelope) SetData(v Trade)`

SetData sets Data field to given value.

### HasData

`func (o *TradeResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *TradeResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *TradeResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *TradeResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *TradeResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *TradeResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TradeResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TradeResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *TradeResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


