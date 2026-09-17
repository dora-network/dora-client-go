# TradingChallengeAllResultsResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]TradingChallengeAllResult**](TradingChallengeAllResult.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewTradingChallengeAllResultsResponseEnvelope

`func NewTradingChallengeAllResultsResponseEnvelope(metadata Metadata, ) *TradingChallengeAllResultsResponseEnvelope`

NewTradingChallengeAllResultsResponseEnvelope instantiates a new TradingChallengeAllResultsResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradingChallengeAllResultsResponseEnvelopeWithDefaults

`func NewTradingChallengeAllResultsResponseEnvelopeWithDefaults() *TradingChallengeAllResultsResponseEnvelope`

NewTradingChallengeAllResultsResponseEnvelopeWithDefaults instantiates a new TradingChallengeAllResultsResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TradingChallengeAllResultsResponseEnvelope) GetData() []TradingChallengeAllResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TradingChallengeAllResultsResponseEnvelope) GetDataOk() (*[]TradingChallengeAllResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TradingChallengeAllResultsResponseEnvelope) SetData(v []TradingChallengeAllResult)`

SetData sets Data field to given value.

### HasData

`func (o *TradingChallengeAllResultsResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *TradingChallengeAllResultsResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *TradingChallengeAllResultsResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *TradingChallengeAllResultsResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *TradingChallengeAllResultsResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *TradingChallengeAllResultsResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TradingChallengeAllResultsResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TradingChallengeAllResultsResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


