# UpdateUserKYCResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** |  | 
**KycCompleted** | **bool** |  | 

## Methods

### NewUpdateUserKYCResponse

`func NewUpdateUserKYCResponse(userId string, kycCompleted bool, ) *UpdateUserKYCResponse`

NewUpdateUserKYCResponse instantiates a new UpdateUserKYCResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserKYCResponseWithDefaults

`func NewUpdateUserKYCResponseWithDefaults() *UpdateUserKYCResponse`

NewUpdateUserKYCResponseWithDefaults instantiates a new UpdateUserKYCResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *UpdateUserKYCResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UpdateUserKYCResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UpdateUserKYCResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetKycCompleted

`func (o *UpdateUserKYCResponse) GetKycCompleted() bool`

GetKycCompleted returns the KycCompleted field if non-nil, zero value otherwise.

### GetKycCompletedOk

`func (o *UpdateUserKYCResponse) GetKycCompletedOk() (*bool, bool)`

GetKycCompletedOk returns a tuple with the KycCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycCompleted

`func (o *UpdateUserKYCResponse) SetKycCompleted(v bool)`

SetKycCompleted sets KycCompleted field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


