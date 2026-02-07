# OrderBookResumeResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **bool** |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewOrderBookResumeResponseEnvelope

`func NewOrderBookResumeResponseEnvelope(metadata Metadata, ) *OrderBookResumeResponseEnvelope`

NewOrderBookResumeResponseEnvelope instantiates a new OrderBookResumeResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderBookResumeResponseEnvelopeWithDefaults

`func NewOrderBookResumeResponseEnvelopeWithDefaults() *OrderBookResumeResponseEnvelope`

NewOrderBookResumeResponseEnvelopeWithDefaults instantiates a new OrderBookResumeResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *OrderBookResumeResponseEnvelope) GetData() bool`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OrderBookResumeResponseEnvelope) GetDataOk() (*bool, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OrderBookResumeResponseEnvelope) SetData(v bool)`

SetData sets Data field to given value.

### HasData

`func (o *OrderBookResumeResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *OrderBookResumeResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *OrderBookResumeResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *OrderBookResumeResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *OrderBookResumeResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *OrderBookResumeResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OrderBookResumeResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OrderBookResumeResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


