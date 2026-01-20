# UserExistsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmailExists** | Pointer to **bool** |  | [optional] 
**FirebaseSet** | Pointer to **bool** |  | [optional] 
**ShouldCreateUser** | Pointer to **bool** |  | [optional] 

## Methods

### NewUserExistsResponse

`func NewUserExistsResponse() *UserExistsResponse`

NewUserExistsResponse instantiates a new UserExistsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserExistsResponseWithDefaults

`func NewUserExistsResponseWithDefaults() *UserExistsResponse`

NewUserExistsResponseWithDefaults instantiates a new UserExistsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmailExists

`func (o *UserExistsResponse) GetEmailExists() bool`

GetEmailExists returns the EmailExists field if non-nil, zero value otherwise.

### GetEmailExistsOk

`func (o *UserExistsResponse) GetEmailExistsOk() (*bool, bool)`

GetEmailExistsOk returns a tuple with the EmailExists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailExists

`func (o *UserExistsResponse) SetEmailExists(v bool)`

SetEmailExists sets EmailExists field to given value.

### HasEmailExists

`func (o *UserExistsResponse) HasEmailExists() bool`

HasEmailExists returns a boolean if a field has been set.

### GetFirebaseSet

`func (o *UserExistsResponse) GetFirebaseSet() bool`

GetFirebaseSet returns the FirebaseSet field if non-nil, zero value otherwise.

### GetFirebaseSetOk

`func (o *UserExistsResponse) GetFirebaseSetOk() (*bool, bool)`

GetFirebaseSetOk returns a tuple with the FirebaseSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirebaseSet

`func (o *UserExistsResponse) SetFirebaseSet(v bool)`

SetFirebaseSet sets FirebaseSet field to given value.

### HasFirebaseSet

`func (o *UserExistsResponse) HasFirebaseSet() bool`

HasFirebaseSet returns a boolean if a field has been set.

### GetShouldCreateUser

`func (o *UserExistsResponse) GetShouldCreateUser() bool`

GetShouldCreateUser returns the ShouldCreateUser field if non-nil, zero value otherwise.

### GetShouldCreateUserOk

`func (o *UserExistsResponse) GetShouldCreateUserOk() (*bool, bool)`

GetShouldCreateUserOk returns a tuple with the ShouldCreateUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldCreateUser

`func (o *UserExistsResponse) SetShouldCreateUser(v bool)`

SetShouldCreateUser sets ShouldCreateUser field to given value.

### HasShouldCreateUser

`func (o *UserExistsResponse) HasShouldCreateUser() bool`

HasShouldCreateUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


