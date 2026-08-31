# UserDeactivation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeactivationId** | **string** |  | 
**UserId** | **string** |  | 
**RequestedBy** | **string** | Admin that requested the deactivation. | 
**Reason** | **string** |  | 
**Status** | **string** | PENDING: wind-down in progress. FAILED: wind-down gave up; admin can re-trigger. COMPLETED: account deactivated. REACTIVATED: blocks lifted. | 
**Attempts** | **int32** | Wind-down attempts performed so far. | 
**Result** | Pointer to **string** | Latest wind-down outcome or error summary. | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**CompletedAt** | Pointer to **time.Time** |  | [optional] 
**ReactivatedBy** | Pointer to **string** |  | [optional] 
**ReactivatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewUserDeactivation

`func NewUserDeactivation(deactivationId string, userId string, requestedBy string, reason string, status string, attempts int32, createdAt time.Time, updatedAt time.Time, ) *UserDeactivation`

NewUserDeactivation instantiates a new UserDeactivation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserDeactivationWithDefaults

`func NewUserDeactivationWithDefaults() *UserDeactivation`

NewUserDeactivationWithDefaults instantiates a new UserDeactivation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeactivationId

`func (o *UserDeactivation) GetDeactivationId() string`

GetDeactivationId returns the DeactivationId field if non-nil, zero value otherwise.

### GetDeactivationIdOk

`func (o *UserDeactivation) GetDeactivationIdOk() (*string, bool)`

GetDeactivationIdOk returns a tuple with the DeactivationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeactivationId

`func (o *UserDeactivation) SetDeactivationId(v string)`

SetDeactivationId sets DeactivationId field to given value.


### GetUserId

`func (o *UserDeactivation) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UserDeactivation) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UserDeactivation) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetRequestedBy

`func (o *UserDeactivation) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *UserDeactivation) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *UserDeactivation) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetReason

`func (o *UserDeactivation) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *UserDeactivation) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *UserDeactivation) SetReason(v string)`

SetReason sets Reason field to given value.


### GetStatus

`func (o *UserDeactivation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UserDeactivation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UserDeactivation) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAttempts

`func (o *UserDeactivation) GetAttempts() int32`

GetAttempts returns the Attempts field if non-nil, zero value otherwise.

### GetAttemptsOk

`func (o *UserDeactivation) GetAttemptsOk() (*int32, bool)`

GetAttemptsOk returns a tuple with the Attempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempts

`func (o *UserDeactivation) SetAttempts(v int32)`

SetAttempts sets Attempts field to given value.


### GetResult

`func (o *UserDeactivation) GetResult() string`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *UserDeactivation) GetResultOk() (*string, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *UserDeactivation) SetResult(v string)`

SetResult sets Result field to given value.

### HasResult

`func (o *UserDeactivation) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetCreatedAt

`func (o *UserDeactivation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UserDeactivation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UserDeactivation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *UserDeactivation) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UserDeactivation) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UserDeactivation) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetCompletedAt

`func (o *UserDeactivation) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *UserDeactivation) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *UserDeactivation) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *UserDeactivation) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### GetReactivatedBy

`func (o *UserDeactivation) GetReactivatedBy() string`

GetReactivatedBy returns the ReactivatedBy field if non-nil, zero value otherwise.

### GetReactivatedByOk

`func (o *UserDeactivation) GetReactivatedByOk() (*string, bool)`

GetReactivatedByOk returns a tuple with the ReactivatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactivatedBy

`func (o *UserDeactivation) SetReactivatedBy(v string)`

SetReactivatedBy sets ReactivatedBy field to given value.

### HasReactivatedBy

`func (o *UserDeactivation) HasReactivatedBy() bool`

HasReactivatedBy returns a boolean if a field has been set.

### GetReactivatedAt

`func (o *UserDeactivation) GetReactivatedAt() time.Time`

GetReactivatedAt returns the ReactivatedAt field if non-nil, zero value otherwise.

### GetReactivatedAtOk

`func (o *UserDeactivation) GetReactivatedAtOk() (*time.Time, bool)`

GetReactivatedAtOk returns a tuple with the ReactivatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactivatedAt

`func (o *UserDeactivation) SetReactivatedAt(v time.Time)`

SetReactivatedAt sets ReactivatedAt field to given value.

### HasReactivatedAt

`func (o *UserDeactivation) HasReactivatedAt() bool`

HasReactivatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


