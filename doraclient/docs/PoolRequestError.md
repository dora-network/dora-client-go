# PoolRequestError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **interface{}** | The response data. Present for successful (2xx) responses. | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | [optional] 

## Methods

### NewPoolRequestError

`func NewPoolRequestError() *PoolRequestError`

NewPoolRequestError instantiates a new PoolRequestError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoolRequestErrorWithDefaults

`func NewPoolRequestErrorWithDefaults() *PoolRequestError`

NewPoolRequestErrorWithDefaults instantiates a new PoolRequestError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *PoolRequestError) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PoolRequestError) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PoolRequestError) SetData(v interface{})`

SetData sets Data field to given value.

### HasData

`func (o *PoolRequestError) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *PoolRequestError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PoolRequestError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PoolRequestError) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PoolRequestError) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *PoolRequestError) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *PoolRequestError) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *PoolRequestError) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *PoolRequestError) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


