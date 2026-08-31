# UpdateFieldDateTime

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Update** | **bool** | Whether to update the field. | 
**Value** | Pointer to **time.Time** | The new value to set for the field. | [optional] 

## Methods

### NewUpdateFieldDateTime

`func NewUpdateFieldDateTime(update bool, ) *UpdateFieldDateTime`

NewUpdateFieldDateTime instantiates a new UpdateFieldDateTime object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateFieldDateTimeWithDefaults

`func NewUpdateFieldDateTimeWithDefaults() *UpdateFieldDateTime`

NewUpdateFieldDateTimeWithDefaults instantiates a new UpdateFieldDateTime object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUpdate

`func (o *UpdateFieldDateTime) GetUpdate() bool`

GetUpdate returns the Update field if non-nil, zero value otherwise.

### GetUpdateOk

`func (o *UpdateFieldDateTime) GetUpdateOk() (*bool, bool)`

GetUpdateOk returns a tuple with the Update field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdate

`func (o *UpdateFieldDateTime) SetUpdate(v bool)`

SetUpdate sets Update field to given value.


### GetValue

`func (o *UpdateFieldDateTime) GetValue() time.Time`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateFieldDateTime) GetValueOk() (*time.Time, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateFieldDateTime) SetValue(v time.Time)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateFieldDateTime) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


