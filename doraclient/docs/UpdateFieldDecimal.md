# UpdateFieldDecimal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Update** | **bool** | Whether to update the field. | 
**Value** | Pointer to **string** | The new value to set for the field. | [optional] 

## Methods

### NewUpdateFieldDecimal

`func NewUpdateFieldDecimal(update bool, ) *UpdateFieldDecimal`

NewUpdateFieldDecimal instantiates a new UpdateFieldDecimal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateFieldDecimalWithDefaults

`func NewUpdateFieldDecimalWithDefaults() *UpdateFieldDecimal`

NewUpdateFieldDecimalWithDefaults instantiates a new UpdateFieldDecimal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUpdate

`func (o *UpdateFieldDecimal) GetUpdate() bool`

GetUpdate returns the Update field if non-nil, zero value otherwise.

### GetUpdateOk

`func (o *UpdateFieldDecimal) GetUpdateOk() (*bool, bool)`

GetUpdateOk returns a tuple with the Update field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdate

`func (o *UpdateFieldDecimal) SetUpdate(v bool)`

SetUpdate sets Update field to given value.


### GetValue

`func (o *UpdateFieldDecimal) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateFieldDecimal) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateFieldDecimal) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateFieldDecimal) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


