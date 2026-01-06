# UserInterest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | Pointer to **map[string]int32** |  | [optional] 
**Value** | Pointer to **map[string]string** |  | [optional] 

## Methods

### NewUserInterest

`func NewUserInterest() *UserInterest`

NewUserInterest instantiates a new UserInterest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserInterestWithDefaults

`func NewUserInterestWithDefaults() *UserInterest`

NewUserInterestWithDefaults instantiates a new UserInterest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *UserInterest) GetAvailable() map[string]int32`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *UserInterest) GetAvailableOk() (*map[string]int32, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *UserInterest) SetAvailable(v map[string]int32)`

SetAvailable sets Available field to given value.

### HasAvailable

`func (o *UserInterest) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

### GetValue

`func (o *UserInterest) GetValue() map[string]string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UserInterest) GetValueOk() (*map[string]string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UserInterest) SetValue(v map[string]string)`

SetValue sets Value field to given value.

### HasValue

`func (o *UserInterest) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


