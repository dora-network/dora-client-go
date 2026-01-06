# UpdateUserConfigRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PhotoUrl** | [**UpdateFieldString**](UpdateFieldString.md) |  | 
**Timezone** | [**UpdateFieldString**](UpdateFieldString.md) |  | 

## Methods

### NewUpdateUserConfigRequest

`func NewUpdateUserConfigRequest(photoUrl UpdateFieldString, timezone UpdateFieldString, ) *UpdateUserConfigRequest`

NewUpdateUserConfigRequest instantiates a new UpdateUserConfigRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserConfigRequestWithDefaults

`func NewUpdateUserConfigRequestWithDefaults() *UpdateUserConfigRequest`

NewUpdateUserConfigRequestWithDefaults instantiates a new UpdateUserConfigRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhotoUrl

`func (o *UpdateUserConfigRequest) GetPhotoUrl() UpdateFieldString`

GetPhotoUrl returns the PhotoUrl field if non-nil, zero value otherwise.

### GetPhotoUrlOk

`func (o *UpdateUserConfigRequest) GetPhotoUrlOk() (*UpdateFieldString, bool)`

GetPhotoUrlOk returns a tuple with the PhotoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotoUrl

`func (o *UpdateUserConfigRequest) SetPhotoUrl(v UpdateFieldString)`

SetPhotoUrl sets PhotoUrl field to given value.


### GetTimezone

`func (o *UpdateUserConfigRequest) GetTimezone() UpdateFieldString`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *UpdateUserConfigRequest) GetTimezoneOk() (*UpdateFieldString, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *UpdateUserConfigRequest) SetTimezone(v UpdateFieldString)`

SetTimezone sets Timezone field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


