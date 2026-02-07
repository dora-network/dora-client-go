# AssetPriceResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**AssetPrice**](AssetPrice.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewAssetPriceResponseEnvelope

`func NewAssetPriceResponseEnvelope(metadata Metadata, ) *AssetPriceResponseEnvelope`

NewAssetPriceResponseEnvelope instantiates a new AssetPriceResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetPriceResponseEnvelopeWithDefaults

`func NewAssetPriceResponseEnvelopeWithDefaults() *AssetPriceResponseEnvelope`

NewAssetPriceResponseEnvelopeWithDefaults instantiates a new AssetPriceResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AssetPriceResponseEnvelope) GetData() AssetPrice`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AssetPriceResponseEnvelope) GetDataOk() (*AssetPrice, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AssetPriceResponseEnvelope) SetData(v AssetPrice)`

SetData sets Data field to given value.

### HasData

`func (o *AssetPriceResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *AssetPriceResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AssetPriceResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AssetPriceResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *AssetPriceResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *AssetPriceResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AssetPriceResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AssetPriceResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


