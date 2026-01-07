# TradeRequestError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **interface{}** | The response data. Present for successful (2xx) responses. | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewTradeRequestError

`func NewTradeRequestError() *TradeRequestError`

NewTradeRequestError instantiates a new TradeRequestError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradeRequestErrorWithDefaults

`func NewTradeRequestErrorWithDefaults() *TradeRequestError`

NewTradeRequestErrorWithDefaults instantiates a new TradeRequestError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TradeRequestError) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TradeRequestError) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TradeRequestError) SetData(v interface{})`

SetData sets Data field to given value.

### HasData

`func (o *TradeRequestError) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *TradeRequestError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *TradeRequestError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *TradeRequestError) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *TradeRequestError) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *TradeRequestError) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TradeRequestError) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TradeRequestError) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *TradeRequestError) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


