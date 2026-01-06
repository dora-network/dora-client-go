# PositionAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PositionId** | Pointer to **string** | The ID of the position account | [optional] 
**PositionName** | Pointer to **string** | The name of the position account | [optional] 
**IsGlobal** | Pointer to **bool** | Whether the position account is the global or an isolated account | [optional] 

## Methods

### NewPositionAccount

`func NewPositionAccount() *PositionAccount`

NewPositionAccount instantiates a new PositionAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPositionAccountWithDefaults

`func NewPositionAccountWithDefaults() *PositionAccount`

NewPositionAccountWithDefaults instantiates a new PositionAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPositionId

`func (o *PositionAccount) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *PositionAccount) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *PositionAccount) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.

### HasPositionId

`func (o *PositionAccount) HasPositionId() bool`

HasPositionId returns a boolean if a field has been set.

### GetPositionName

`func (o *PositionAccount) GetPositionName() string`

GetPositionName returns the PositionName field if non-nil, zero value otherwise.

### GetPositionNameOk

`func (o *PositionAccount) GetPositionNameOk() (*string, bool)`

GetPositionNameOk returns a tuple with the PositionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionName

`func (o *PositionAccount) SetPositionName(v string)`

SetPositionName sets PositionName field to given value.

### HasPositionName

`func (o *PositionAccount) HasPositionName() bool`

HasPositionName returns a boolean if a field has been set.

### GetIsGlobal

`func (o *PositionAccount) GetIsGlobal() bool`

GetIsGlobal returns the IsGlobal field if non-nil, zero value otherwise.

### GetIsGlobalOk

`func (o *PositionAccount) GetIsGlobalOk() (*bool, bool)`

GetIsGlobalOk returns a tuple with the IsGlobal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobal

`func (o *PositionAccount) SetIsGlobal(v bool)`

SetIsGlobal sets IsGlobal field to given value.

### HasIsGlobal

`func (o *PositionAccount) HasIsGlobal() bool`

HasIsGlobal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


