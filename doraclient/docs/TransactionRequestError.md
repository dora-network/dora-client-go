# TransactionRequestError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **interface{}** | The response data. Present for successful (2xx) responses. | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to [**Metadata**](Metadata.md) |  | [optional] 

## Methods

### NewTransactionRequestError

`func NewTransactionRequestError() *TransactionRequestError`

NewTransactionRequestError instantiates a new TransactionRequestError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransactionRequestErrorWithDefaults

`func NewTransactionRequestErrorWithDefaults() *TransactionRequestError`

NewTransactionRequestErrorWithDefaults instantiates a new TransactionRequestError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TransactionRequestError) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TransactionRequestError) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TransactionRequestError) SetData(v interface{})`

SetData sets Data field to given value.

### HasData

`func (o *TransactionRequestError) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *TransactionRequestError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *TransactionRequestError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *TransactionRequestError) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *TransactionRequestError) HasError() bool`

HasError returns a boolean if a field has been set.

### GetMetadata

`func (o *TransactionRequestError) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TransactionRequestError) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TransactionRequestError) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *TransactionRequestError) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


