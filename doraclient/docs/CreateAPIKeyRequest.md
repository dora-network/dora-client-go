# CreateAPIKeyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Label** | **string** |  | 
**Expires** | Pointer to **time.Time** | Date at which the api-key will expire | [optional] 

## Methods

### NewCreateAPIKeyRequest

`func NewCreateAPIKeyRequest(label string, ) *CreateAPIKeyRequest`

NewCreateAPIKeyRequest instantiates a new CreateAPIKeyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAPIKeyRequestWithDefaults

`func NewCreateAPIKeyRequestWithDefaults() *CreateAPIKeyRequest`

NewCreateAPIKeyRequestWithDefaults instantiates a new CreateAPIKeyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLabel

`func (o *CreateAPIKeyRequest) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateAPIKeyRequest) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateAPIKeyRequest) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetExpires

`func (o *CreateAPIKeyRequest) GetExpires() time.Time`

GetExpires returns the Expires field if non-nil, zero value otherwise.

### GetExpiresOk

`func (o *CreateAPIKeyRequest) GetExpiresOk() (*time.Time, bool)`

GetExpiresOk returns a tuple with the Expires field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpires

`func (o *CreateAPIKeyRequest) SetExpires(v time.Time)`

SetExpires sets Expires field to given value.

### HasExpires

`func (o *CreateAPIKeyRequest) HasExpires() bool`

HasExpires returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


