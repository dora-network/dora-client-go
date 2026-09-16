# CreateTradingChallengeQRRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MinRewardAmount** | **string** | Must be greater than zero and greater than initial_user_balance. | 
**MaxRewardAmount** | **string** | Must be greater than or equal to min_reward_amount. | 
**RewardClaimGraceDays** | Pointer to **int32** |  | [optional] [default to 14]

## Methods

### NewCreateTradingChallengeQRRequest

`func NewCreateTradingChallengeQRRequest(minRewardAmount string, maxRewardAmount string, ) *CreateTradingChallengeQRRequest`

NewCreateTradingChallengeQRRequest instantiates a new CreateTradingChallengeQRRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTradingChallengeQRRequestWithDefaults

`func NewCreateTradingChallengeQRRequestWithDefaults() *CreateTradingChallengeQRRequest`

NewCreateTradingChallengeQRRequestWithDefaults instantiates a new CreateTradingChallengeQRRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMinRewardAmount

`func (o *CreateTradingChallengeQRRequest) GetMinRewardAmount() string`

GetMinRewardAmount returns the MinRewardAmount field if non-nil, zero value otherwise.

### GetMinRewardAmountOk

`func (o *CreateTradingChallengeQRRequest) GetMinRewardAmountOk() (*string, bool)`

GetMinRewardAmountOk returns a tuple with the MinRewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinRewardAmount

`func (o *CreateTradingChallengeQRRequest) SetMinRewardAmount(v string)`

SetMinRewardAmount sets MinRewardAmount field to given value.


### GetMaxRewardAmount

`func (o *CreateTradingChallengeQRRequest) GetMaxRewardAmount() string`

GetMaxRewardAmount returns the MaxRewardAmount field if non-nil, zero value otherwise.

### GetMaxRewardAmountOk

`func (o *CreateTradingChallengeQRRequest) GetMaxRewardAmountOk() (*string, bool)`

GetMaxRewardAmountOk returns a tuple with the MaxRewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRewardAmount

`func (o *CreateTradingChallengeQRRequest) SetMaxRewardAmount(v string)`

SetMaxRewardAmount sets MaxRewardAmount field to given value.


### GetRewardClaimGraceDays

`func (o *CreateTradingChallengeQRRequest) GetRewardClaimGraceDays() int32`

GetRewardClaimGraceDays returns the RewardClaimGraceDays field if non-nil, zero value otherwise.

### GetRewardClaimGraceDaysOk

`func (o *CreateTradingChallengeQRRequest) GetRewardClaimGraceDaysOk() (*int32, bool)`

GetRewardClaimGraceDaysOk returns a tuple with the RewardClaimGraceDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewardClaimGraceDays

`func (o *CreateTradingChallengeQRRequest) SetRewardClaimGraceDays(v int32)`

SetRewardClaimGraceDays sets RewardClaimGraceDays field to given value.

### HasRewardClaimGraceDays

`func (o *CreateTradingChallengeQRRequest) HasRewardClaimGraceDays() bool`

HasRewardClaimGraceDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


