# ListAssetYieldResponseEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]AssetYield**](AssetYield.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewListAssetYieldResponseEnvelope

`func NewListAssetYieldResponseEnvelope(metadata Metadata, ) *ListAssetYieldResponseEnvelope`

NewListAssetYieldResponseEnvelope instantiates a new ListAssetYieldResponseEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAssetYieldResponseEnvelopeWithDefaults

`func NewListAssetYieldResponseEnvelopeWithDefaults() *ListAssetYieldResponseEnvelope`

NewListAssetYieldResponseEnvelopeWithDefaults instantiates a new ListAssetYieldResponseEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAssetYieldResponseEnvelope) GetData() []AssetYield`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAssetYieldResponseEnvelope) GetDataOk() (*[]AssetYield, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAssetYieldResponseEnvelope) SetData(v []AssetYield)`

SetData sets Data field to given value.

### HasData

`func (o *ListAssetYieldResponseEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ListAssetYieldResponseEnvelope) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListAssetYieldResponseEnvelope) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListAssetYieldResponseEnvelope) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ListAssetYieldResponseEnvelope) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *ListAssetYieldResponseEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ListAssetYieldResponseEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ListAssetYieldResponseEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


