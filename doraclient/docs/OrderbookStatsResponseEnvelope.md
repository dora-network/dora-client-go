# OrderbookStatsResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**OrderbookStats**](OrderbookStats.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewOrderbookStatsResponseEnvelope

`func NewOrderbookStatsResponseEnvelope(metadata Metadata, ) *OrderbookStatsResponseEnvelope`

NewOrderbookStatsResponseEnvelope instantiates a new OrderbookStatsResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderbookStatsResponseEnvelopeWithDefaults

`func NewOrderbookStatsResponseEnvelopeWithDefaults() *OrderbookStatsResponseEnvelope`

NewOrderbookStatsResponseEnvelopeWithDefaults instantiates a new OrderbookStatsResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *OrderbookStatsResponseEnvelope) GetData() OrderbookStats`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OrderbookStatsResponseEnvelope) GetDataOk() (*OrderbookStats, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OrderbookStatsResponseEnvelope) SetData(v OrderbookStats)`

SetData sets Data field to given value.

### HasData

`func (o *OrderbookStatsResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *OrderbookStatsResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *OrderbookStatsResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *OrderbookStatsResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *OrderbookStatsResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *OrderbookStatsResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OrderbookStatsResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OrderbookStatsResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


