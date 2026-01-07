# UpdateRolesString

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Update** | **bool** | Whether to update the field. | 
**Value** | Pointer to [**UserRole**](UserRole.md) | The new value to set for the field. | [optional] 

## Methods

### NewUpdateRolesString

`func NewUpdateRolesString(update bool, ) *UpdateRolesString`

NewUpdateRolesString instantiates a new UpdateRolesString object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateRolesStringWithDefaults

`func NewUpdateRolesStringWithDefaults() *UpdateRolesString`

NewUpdateRolesStringWithDefaults instantiates a new UpdateRolesString object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUpdate

`func (o *UpdateRolesString) GetUpdate() bool`

GetUpdate returns the Update field if non-nil, zero value otherwise.

### GetUpdateOk

`func (o *UpdateRolesString) GetUpdateOk() (*bool, bool)`

GetUpdateOk returns a tuple with the Update field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdate

`func (o *UpdateRolesString) SetUpdate(v bool)`

SetUpdate sets Update field to given value.


### GetValue

`func (o *UpdateRolesString) GetValue() UserRole`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateRolesString) GetValueOk() (*UserRole, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateRolesString) SetValue(v UserRole)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateRolesString) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


