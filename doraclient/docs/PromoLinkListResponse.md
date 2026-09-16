# PromoLinkListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**PromoLinkListResponseAllOfData**](PromoLinkListResponseAllOfData.md) |  | [optional] 
**Error** | Pointer to **string** | The error message. Present for error (non-2xx) responses. | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewPromoLinkListResponse

`func NewPromoLinkListResponse(metadata Metadata, ) *PromoLinkListResponse`

NewPromoLinkListResponse instantiates a new PromoLinkListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoLinkListResponseWithDefaults

`func NewPromoLinkListResponseWithDefaults() *PromoLinkListResponse`

NewPromoLinkListResponseWithDefaults instantiates a new PromoLinkListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *PromoLinkListResponse) GetData() PromoLinkListResponseAllOfData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PromoLinkListResponse) GetDataOk() (*PromoLinkListResponseAllOfData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PromoLinkListResponse) SetData(v PromoLinkListResponseAllOfData)`

SetData sets Data field to given value.

### HasData

`func (o *PromoLinkListResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *PromoLinkListResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PromoLinkListResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PromoLinkListResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PromoLinkListResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *PromoLinkListResponse) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *PromoLinkListResponse) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *PromoLinkListResponse) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


