# ListAssetPriceResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]AssetPrice**](AssetPrice.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) |  | [optional] 

## Methods

### NewListAssetPriceResponseEnvelope

`func NewListAssetPriceResponseEnvelope() *ListAssetPriceResponseEnvelope`

NewListAssetPriceResponseEnvelope instantiates a new ListAssetPriceResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAssetPriceResponseEnvelopeWithDefaults

`func NewListAssetPriceResponseEnvelopeWithDefaults() *ListAssetPriceResponseEnvelope`

NewListAssetPriceResponseEnvelopeWithDefaults instantiates a new ListAssetPriceResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAssetPriceResponseEnvelope) GetData() []AssetPrice`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAssetPriceResponseEnvelope) GetDataOk() (*[]AssetPrice, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAssetPriceResponseEnvelope) SetData(v []AssetPrice)`

SetData sets Data field to given value.

### HasData

`func (o *ListAssetPriceResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ListAssetPriceResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListAssetPriceResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListAssetPriceResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ListAssetPriceResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *ListAssetPriceResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ListAssetPriceResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ListAssetPriceResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ListAssetPriceResponseEnvelope) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


