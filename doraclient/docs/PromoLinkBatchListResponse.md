# PromoLinkBatchListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**PromoLinkBatchListResponseAllOfData**](PromoLinkBatchListResponseAllOfData.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewPromoLinkBatchListResponse

`func NewPromoLinkBatchListResponse(metadata Metadata, ) *PromoLinkBatchListResponse`

NewPromoLinkBatchListResponse instantiates a new PromoLinkBatchListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoLinkBatchListResponseWithDefaults

`func NewPromoLinkBatchListResponseWithDefaults() *PromoLinkBatchListResponse`

NewPromoLinkBatchListResponseWithDefaults instantiates a new PromoLinkBatchListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *PromoLinkBatchListResponse) GetData() PromoLinkBatchListResponseAllOfData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PromoLinkBatchListResponse) GetDataOk() (*PromoLinkBatchListResponseAllOfData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PromoLinkBatchListResponse) SetData(v PromoLinkBatchListResponseAllOfData)`

SetData sets Data field to given value.

### HasData

`func (o *PromoLinkBatchListResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *PromoLinkBatchListResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PromoLinkBatchListResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PromoLinkBatchListResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PromoLinkBatchListResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *PromoLinkBatchListResponse) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *PromoLinkBatchListResponse) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *PromoLinkBatchListResponse) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


