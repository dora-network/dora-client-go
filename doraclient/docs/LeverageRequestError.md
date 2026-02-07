# LeverageRequestError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **interface{}** | The response data. Present for successful (2xx) responses. | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**Metadata** | [**Metadata**](Metadata.md) | Metadata about the response, including status code and trace information. | 

## Methods

### NewLeverageRequestError

`func NewLeverageRequestError(metadata Metadata, ) *LeverageRequestError`

NewLeverageRequestError instantiates a new LeverageRequestError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeverageRequestErrorWithDefaults

`func NewLeverageRequestErrorWithDefaults() *LeverageRequestError`

NewLeverageRequestErrorWithDefaults instantiates a new LeverageRequestError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *LeverageRequestError) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *LeverageRequestError) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *LeverageRequestError) SetData(v interface{})`

SetData sets Data field to given value.

### HasData

`func (o *LeverageRequestError) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *LeverageRequestError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *LeverageRequestError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *LeverageRequestError) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *LeverageRequestError) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *LeverageRequestError) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LeverageRequestError) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LeverageRequestError) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


