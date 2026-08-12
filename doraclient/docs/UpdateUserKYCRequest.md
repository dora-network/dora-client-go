# UpdateUserKYCRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedKyc** | **bool** | If true, sets kyc_completed_at to now; if false, clears it. | 

## Methods

### NewUpdateUserKYCRequest

`func NewUpdateUserKYCRequest(completedKyc bool, ) *UpdateUserKYCRequest`

NewUpdateUserKYCRequest instantiates a new UpdateUserKYCRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserKYCRequestWithDefaults

`func NewUpdateUserKYCRequestWithDefaults() *UpdateUserKYCRequest`

NewUpdateUserKYCRequestWithDefaults instantiates a new UpdateUserKYCRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedKyc

`func (o *UpdateUserKYCRequest) GetCompletedKyc() bool`

GetCompletedKyc returns the CompletedKyc field if non-nil, zero value otherwise.

### GetCompletedKycOk

`func (o *UpdateUserKYCRequest) GetCompletedKycOk() (*bool, bool)`

GetCompletedKycOk returns a tuple with the CompletedKyc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedKyc

`func (o *UpdateUserKYCRequest) SetCompletedKyc(v bool)`

SetCompletedKyc sets CompletedKyc field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


