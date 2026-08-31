# UpdateFieldInteger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Update** | **bool** | Whether to update the field. | 
**Value** | Pointer to **int32** | The new value to set for the field. | [optional] 

## Methods

### NewUpdateFieldInteger

`func NewUpdateFieldInteger(update bool, ) *UpdateFieldInteger`

NewUpdateFieldInteger instantiates a new UpdateFieldInteger object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateFieldIntegerWithDefaults

`func NewUpdateFieldIntegerWithDefaults() *UpdateFieldInteger`

NewUpdateFieldIntegerWithDefaults instantiates a new UpdateFieldInteger object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUpdate

`func (o *UpdateFieldInteger) GetUpdate() bool`

GetUpdate returns the Update field if non-nil, zero value otherwise.

### GetUpdateOk

`func (o *UpdateFieldInteger) GetUpdateOk() (*bool, bool)`

GetUpdateOk returns a tuple with the Update field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdate

`func (o *UpdateFieldInteger) SetUpdate(v bool)`

SetUpdate sets Update field to given value.


### GetValue

`func (o *UpdateFieldInteger) GetValue() int32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateFieldInteger) GetValueOk() (*int32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateFieldInteger) SetValue(v int32)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateFieldInteger) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


