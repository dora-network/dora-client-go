# ClaimTradingChallengeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TradingChallengeId** | **string** |  | 
**UserId** | **string** |  | 
**Status** | **string** |  | 
**RewardAmount** | Pointer to **string** | Fixed QR reward, present for REWARD_PENDING_KYC. | [optional] 
**KycUrl** | Pointer to **string** |  | [optional] 
**RewardDeadlineAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewClaimTradingChallengeResponse

`func NewClaimTradingChallengeResponse(tradingChallengeId string, userId string, status string, ) *ClaimTradingChallengeResponse`

NewClaimTradingChallengeResponse instantiates a new ClaimTradingChallengeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClaimTradingChallengeResponseWithDefaults

`func NewClaimTradingChallengeResponseWithDefaults() *ClaimTradingChallengeResponse`

NewClaimTradingChallengeResponseWithDefaults instantiates a new ClaimTradingChallengeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTradingChallengeId

`func (o *ClaimTradingChallengeResponse) GetTradingChallengeId() string`

GetTradingChallengeId returns the TradingChallengeId field if non-nil, zero value otherwise.

### GetTradingChallengeIdOk

`func (o *ClaimTradingChallengeResponse) GetTradingChallengeIdOk() (*string, bool)`

GetTradingChallengeIdOk returns a tuple with the TradingChallengeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeId

`func (o *ClaimTradingChallengeResponse) SetTradingChallengeId(v string)`

SetTradingChallengeId sets TradingChallengeId field to given value.


### GetUserId

`func (o *ClaimTradingChallengeResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ClaimTradingChallengeResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ClaimTradingChallengeResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetStatus

`func (o *ClaimTradingChallengeResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClaimTradingChallengeResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClaimTradingChallengeResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetRewardAmount

`func (o *ClaimTradingChallengeResponse) GetRewardAmount() string`

GetRewardAmount returns the RewardAmount field if non-nil, zero value otherwise.

### GetRewardAmountOk

`func (o *ClaimTradingChallengeResponse) GetRewardAmountOk() (*string, bool)`

GetRewardAmountOk returns a tuple with the RewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewardAmount

`func (o *ClaimTradingChallengeResponse) SetRewardAmount(v string)`

SetRewardAmount sets RewardAmount field to given value.

### HasRewardAmount

`func (o *ClaimTradingChallengeResponse) HasRewardAmount() bool`

HasRewardAmount returns a boolean if a field has been set.

### GetKycUrl

`func (o *ClaimTradingChallengeResponse) GetKycUrl() string`

GetKycUrl returns the KycUrl field if non-nil, zero value otherwise.

### GetKycUrlOk

`func (o *ClaimTradingChallengeResponse) GetKycUrlOk() (*string, bool)`

GetKycUrlOk returns a tuple with the KycUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycUrl

`func (o *ClaimTradingChallengeResponse) SetKycUrl(v string)`

SetKycUrl sets KycUrl field to given value.

### HasKycUrl

`func (o *ClaimTradingChallengeResponse) HasKycUrl() bool`

HasKycUrl returns a boolean if a field has been set.

### GetRewardDeadlineAt

`func (o *ClaimTradingChallengeResponse) GetRewardDeadlineAt() time.Time`

GetRewardDeadlineAt returns the RewardDeadlineAt field if non-nil, zero value otherwise.

### GetRewardDeadlineAtOk

`func (o *ClaimTradingChallengeResponse) GetRewardDeadlineAtOk() (*time.Time, bool)`

GetRewardDeadlineAtOk returns a tuple with the RewardDeadlineAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewardDeadlineAt

`func (o *ClaimTradingChallengeResponse) SetRewardDeadlineAt(v time.Time)`

SetRewardDeadlineAt sets RewardDeadlineAt field to given value.

### HasRewardDeadlineAt

`func (o *ClaimTradingChallengeResponse) HasRewardDeadlineAt() bool`

HasRewardDeadlineAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


