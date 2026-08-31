# TradingChallengeRegistrationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**TradingChallengeId** | **string** |  | 
**TradingChallengeName** | Pointer to **string** |  | [optional] 
**TradingChallengeType** | Pointer to **string** |  | [optional] 
**TradingChallengeStatus** | Pointer to **string** |  | [optional] 
**UserId** | **string** |  | 
**UserEmail** | Pointer to **string** |  | [optional] 
**UserName** | Pointer to **string** |  | [optional] 
**TenantId** | **string** |  | 
**Status** | **string** |  | 
**ReviewedBy** | Pointer to **string** | Who settled the request. Absent while it is PENDING. | [optional] 
**ReviewedAt** | Pointer to **time.Time** | When it was settled. Absent while it is PENDING. | [optional] 
**ReviewReason** | Pointer to **string** | Free-text note kept for the audit trail. Optional on both decisions. | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewTradingChallengeRegistrationRequest

`func NewTradingChallengeRegistrationRequest(id string, tradingChallengeId string, userId string, tenantId string, status string, createdAt time.Time, updatedAt time.Time, ) *TradingChallengeRegistrationRequest`

NewTradingChallengeRegistrationRequest instantiates a new TradingChallengeRegistrationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradingChallengeRegistrationRequestWithDefaults

`func NewTradingChallengeRegistrationRequestWithDefaults() *TradingChallengeRegistrationRequest`

NewTradingChallengeRegistrationRequestWithDefaults instantiates a new TradingChallengeRegistrationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TradingChallengeRegistrationRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TradingChallengeRegistrationRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TradingChallengeRegistrationRequest) SetId(v string)`

SetId sets Id field to given value.


### GetTradingChallengeId

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeId() string`

GetTradingChallengeId returns the TradingChallengeId field if non-nil, zero value otherwise.

### GetTradingChallengeIdOk

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeIdOk() (*string, bool)`

GetTradingChallengeIdOk returns a tuple with the TradingChallengeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeId

`func (o *TradingChallengeRegistrationRequest) SetTradingChallengeId(v string)`

SetTradingChallengeId sets TradingChallengeId field to given value.


### GetTradingChallengeName

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeName() string`

GetTradingChallengeName returns the TradingChallengeName field if non-nil, zero value otherwise.

### GetTradingChallengeNameOk

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeNameOk() (*string, bool)`

GetTradingChallengeNameOk returns a tuple with the TradingChallengeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeName

`func (o *TradingChallengeRegistrationRequest) SetTradingChallengeName(v string)`

SetTradingChallengeName sets TradingChallengeName field to given value.

### HasTradingChallengeName

`func (o *TradingChallengeRegistrationRequest) HasTradingChallengeName() bool`

HasTradingChallengeName returns a boolean if a field has been set.

### GetTradingChallengeType

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeType() string`

GetTradingChallengeType returns the TradingChallengeType field if non-nil, zero value otherwise.

### GetTradingChallengeTypeOk

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeTypeOk() (*string, bool)`

GetTradingChallengeTypeOk returns a tuple with the TradingChallengeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeType

`func (o *TradingChallengeRegistrationRequest) SetTradingChallengeType(v string)`

SetTradingChallengeType sets TradingChallengeType field to given value.

### HasTradingChallengeType

`func (o *TradingChallengeRegistrationRequest) HasTradingChallengeType() bool`

HasTradingChallengeType returns a boolean if a field has been set.

### GetTradingChallengeStatus

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeStatus() string`

GetTradingChallengeStatus returns the TradingChallengeStatus field if non-nil, zero value otherwise.

### GetTradingChallengeStatusOk

`func (o *TradingChallengeRegistrationRequest) GetTradingChallengeStatusOk() (*string, bool)`

GetTradingChallengeStatusOk returns a tuple with the TradingChallengeStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeStatus

`func (o *TradingChallengeRegistrationRequest) SetTradingChallengeStatus(v string)`

SetTradingChallengeStatus sets TradingChallengeStatus field to given value.

### HasTradingChallengeStatus

`func (o *TradingChallengeRegistrationRequest) HasTradingChallengeStatus() bool`

HasTradingChallengeStatus returns a boolean if a field has been set.

### GetUserId

`func (o *TradingChallengeRegistrationRequest) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *TradingChallengeRegistrationRequest) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *TradingChallengeRegistrationRequest) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetUserEmail

`func (o *TradingChallengeRegistrationRequest) GetUserEmail() string`

GetUserEmail returns the UserEmail field if non-nil, zero value otherwise.

### GetUserEmailOk

`func (o *TradingChallengeRegistrationRequest) GetUserEmailOk() (*string, bool)`

GetUserEmailOk returns a tuple with the UserEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserEmail

`func (o *TradingChallengeRegistrationRequest) SetUserEmail(v string)`

SetUserEmail sets UserEmail field to given value.

### HasUserEmail

`func (o *TradingChallengeRegistrationRequest) HasUserEmail() bool`

HasUserEmail returns a boolean if a field has been set.

### GetUserName

`func (o *TradingChallengeRegistrationRequest) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *TradingChallengeRegistrationRequest) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *TradingChallengeRegistrationRequest) SetUserName(v string)`

SetUserName sets UserName field to given value.

### HasUserName

`func (o *TradingChallengeRegistrationRequest) HasUserName() bool`

HasUserName returns a boolean if a field has been set.

### GetTenantId

`func (o *TradingChallengeRegistrationRequest) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *TradingChallengeRegistrationRequest) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *TradingChallengeRegistrationRequest) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetStatus

`func (o *TradingChallengeRegistrationRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TradingChallengeRegistrationRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TradingChallengeRegistrationRequest) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReviewedBy

`func (o *TradingChallengeRegistrationRequest) GetReviewedBy() string`

GetReviewedBy returns the ReviewedBy field if non-nil, zero value otherwise.

### GetReviewedByOk

`func (o *TradingChallengeRegistrationRequest) GetReviewedByOk() (*string, bool)`

GetReviewedByOk returns a tuple with the ReviewedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewedBy

`func (o *TradingChallengeRegistrationRequest) SetReviewedBy(v string)`

SetReviewedBy sets ReviewedBy field to given value.

### HasReviewedBy

`func (o *TradingChallengeRegistrationRequest) HasReviewedBy() bool`

HasReviewedBy returns a boolean if a field has been set.

### GetReviewedAt

`func (o *TradingChallengeRegistrationRequest) GetReviewedAt() time.Time`

GetReviewedAt returns the ReviewedAt field if non-nil, zero value otherwise.

### GetReviewedAtOk

`func (o *TradingChallengeRegistrationRequest) GetReviewedAtOk() (*time.Time, bool)`

GetReviewedAtOk returns a tuple with the ReviewedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewedAt

`func (o *TradingChallengeRegistrationRequest) SetReviewedAt(v time.Time)`

SetReviewedAt sets ReviewedAt field to given value.

### HasReviewedAt

`func (o *TradingChallengeRegistrationRequest) HasReviewedAt() bool`

HasReviewedAt returns a boolean if a field has been set.

### GetReviewReason

`func (o *TradingChallengeRegistrationRequest) GetReviewReason() string`

GetReviewReason returns the ReviewReason field if non-nil, zero value otherwise.

### GetReviewReasonOk

`func (o *TradingChallengeRegistrationRequest) GetReviewReasonOk() (*string, bool)`

GetReviewReasonOk returns a tuple with the ReviewReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewReason

`func (o *TradingChallengeRegistrationRequest) SetReviewReason(v string)`

SetReviewReason sets ReviewReason field to given value.

### HasReviewReason

`func (o *TradingChallengeRegistrationRequest) HasReviewReason() bool`

HasReviewReason returns a boolean if a field has been set.

### GetCreatedAt

`func (o *TradingChallengeRegistrationRequest) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TradingChallengeRegistrationRequest) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TradingChallengeRegistrationRequest) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *TradingChallengeRegistrationRequest) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TradingChallengeRegistrationRequest) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TradingChallengeRegistrationRequest) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


