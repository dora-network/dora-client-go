# QRRewardPreview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TradingChallengeId** | **string** |  | 
**State** | **string** |  | 
**CurrentEquity** | Pointer to **string** |  | [optional] 
**PromoCredit** | **string** |  | 
**EligibleProfit** | Pointer to **string** |  | [optional] 
**ProjectedReward** | Pointer to **string** |  | [optional] 
**RewardAmount** | Pointer to **string** |  | [optional] 
**MinRewardAmount** | **string** |  | 
**MaxRewardAmount** | **string** |  | 
**RewardDeadlineAt** | **time.Time** |  | 
**KycCompleted** | **bool** |  | 
**KycUrl** | Pointer to **string** |  | [optional] 
**Blockers** | **[]string** |  | 

## Methods

### NewQRRewardPreview

`func NewQRRewardPreview(tradingChallengeId string, state string, promoCredit string, minRewardAmount string, maxRewardAmount string, rewardDeadlineAt time.Time, kycCompleted bool, blockers []string, ) *QRRewardPreview`

NewQRRewardPreview instantiates a new QRRewardPreview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQRRewardPreviewWithDefaults

`func NewQRRewardPreviewWithDefaults() *QRRewardPreview`

NewQRRewardPreviewWithDefaults instantiates a new QRRewardPreview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTradingChallengeId

`func (o *QRRewardPreview) GetTradingChallengeId() string`

GetTradingChallengeId returns the TradingChallengeId field if non-nil, zero value otherwise.

### GetTradingChallengeIdOk

`func (o *QRRewardPreview) GetTradingChallengeIdOk() (*string, bool)`

GetTradingChallengeIdOk returns a tuple with the TradingChallengeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeId

`func (o *QRRewardPreview) SetTradingChallengeId(v string)`

SetTradingChallengeId sets TradingChallengeId field to given value.


### GetState

`func (o *QRRewardPreview) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *QRRewardPreview) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *QRRewardPreview) SetState(v string)`

SetState sets State field to given value.


### GetCurrentEquity

`func (o *QRRewardPreview) GetCurrentEquity() string`

GetCurrentEquity returns the CurrentEquity field if non-nil, zero value otherwise.

### GetCurrentEquityOk

`func (o *QRRewardPreview) GetCurrentEquityOk() (*string, bool)`

GetCurrentEquityOk returns a tuple with the CurrentEquity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentEquity

`func (o *QRRewardPreview) SetCurrentEquity(v string)`

SetCurrentEquity sets CurrentEquity field to given value.

### HasCurrentEquity

`func (o *QRRewardPreview) HasCurrentEquity() bool`

HasCurrentEquity returns a boolean if a field has been set.

### GetPromoCredit

`func (o *QRRewardPreview) GetPromoCredit() string`

GetPromoCredit returns the PromoCredit field if non-nil, zero value otherwise.

### GetPromoCreditOk

`func (o *QRRewardPreview) GetPromoCreditOk() (*string, bool)`

GetPromoCreditOk returns a tuple with the PromoCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoCredit

`func (o *QRRewardPreview) SetPromoCredit(v string)`

SetPromoCredit sets PromoCredit field to given value.


### GetEligibleProfit

`func (o *QRRewardPreview) GetEligibleProfit() string`

GetEligibleProfit returns the EligibleProfit field if non-nil, zero value otherwise.

### GetEligibleProfitOk

`func (o *QRRewardPreview) GetEligibleProfitOk() (*string, bool)`

GetEligibleProfitOk returns a tuple with the EligibleProfit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEligibleProfit

`func (o *QRRewardPreview) SetEligibleProfit(v string)`

SetEligibleProfit sets EligibleProfit field to given value.

### HasEligibleProfit

`func (o *QRRewardPreview) HasEligibleProfit() bool`

HasEligibleProfit returns a boolean if a field has been set.

### GetProjectedReward

`func (o *QRRewardPreview) GetProjectedReward() string`

GetProjectedReward returns the ProjectedReward field if non-nil, zero value otherwise.

### GetProjectedRewardOk

`func (o *QRRewardPreview) GetProjectedRewardOk() (*string, bool)`

GetProjectedRewardOk returns a tuple with the ProjectedReward field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectedReward

`func (o *QRRewardPreview) SetProjectedReward(v string)`

SetProjectedReward sets ProjectedReward field to given value.

### HasProjectedReward

`func (o *QRRewardPreview) HasProjectedReward() bool`

HasProjectedReward returns a boolean if a field has been set.

### GetRewardAmount

`func (o *QRRewardPreview) GetRewardAmount() string`

GetRewardAmount returns the RewardAmount field if non-nil, zero value otherwise.

### GetRewardAmountOk

`func (o *QRRewardPreview) GetRewardAmountOk() (*string, bool)`

GetRewardAmountOk returns a tuple with the RewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewardAmount

`func (o *QRRewardPreview) SetRewardAmount(v string)`

SetRewardAmount sets RewardAmount field to given value.

### HasRewardAmount

`func (o *QRRewardPreview) HasRewardAmount() bool`

HasRewardAmount returns a boolean if a field has been set.

### GetMinRewardAmount

`func (o *QRRewardPreview) GetMinRewardAmount() string`

GetMinRewardAmount returns the MinRewardAmount field if non-nil, zero value otherwise.

### GetMinRewardAmountOk

`func (o *QRRewardPreview) GetMinRewardAmountOk() (*string, bool)`

GetMinRewardAmountOk returns a tuple with the MinRewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinRewardAmount

`func (o *QRRewardPreview) SetMinRewardAmount(v string)`

SetMinRewardAmount sets MinRewardAmount field to given value.


### GetMaxRewardAmount

`func (o *QRRewardPreview) GetMaxRewardAmount() string`

GetMaxRewardAmount returns the MaxRewardAmount field if non-nil, zero value otherwise.

### GetMaxRewardAmountOk

`func (o *QRRewardPreview) GetMaxRewardAmountOk() (*string, bool)`

GetMaxRewardAmountOk returns a tuple with the MaxRewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRewardAmount

`func (o *QRRewardPreview) SetMaxRewardAmount(v string)`

SetMaxRewardAmount sets MaxRewardAmount field to given value.


### GetRewardDeadlineAt

`func (o *QRRewardPreview) GetRewardDeadlineAt() time.Time`

GetRewardDeadlineAt returns the RewardDeadlineAt field if non-nil, zero value otherwise.

### GetRewardDeadlineAtOk

`func (o *QRRewardPreview) GetRewardDeadlineAtOk() (*time.Time, bool)`

GetRewardDeadlineAtOk returns a tuple with the RewardDeadlineAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewardDeadlineAt

`func (o *QRRewardPreview) SetRewardDeadlineAt(v time.Time)`

SetRewardDeadlineAt sets RewardDeadlineAt field to given value.


### GetKycCompleted

`func (o *QRRewardPreview) GetKycCompleted() bool`

GetKycCompleted returns the KycCompleted field if non-nil, zero value otherwise.

### GetKycCompletedOk

`func (o *QRRewardPreview) GetKycCompletedOk() (*bool, bool)`

GetKycCompletedOk returns a tuple with the KycCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycCompleted

`func (o *QRRewardPreview) SetKycCompleted(v bool)`

SetKycCompleted sets KycCompleted field to given value.


### GetKycUrl

`func (o *QRRewardPreview) GetKycUrl() string`

GetKycUrl returns the KycUrl field if non-nil, zero value otherwise.

### GetKycUrlOk

`func (o *QRRewardPreview) GetKycUrlOk() (*string, bool)`

GetKycUrlOk returns a tuple with the KycUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycUrl

`func (o *QRRewardPreview) SetKycUrl(v string)`

SetKycUrl sets KycUrl field to given value.

### HasKycUrl

`func (o *QRRewardPreview) HasKycUrl() bool`

HasKycUrl returns a boolean if a field has been set.

### GetBlockers

`func (o *QRRewardPreview) GetBlockers() []string`

GetBlockers returns the Blockers field if non-nil, zero value otherwise.

### GetBlockersOk

`func (o *QRRewardPreview) GetBlockersOk() (*[]string, bool)`

GetBlockersOk returns a tuple with the Blockers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockers

`func (o *QRRewardPreview) SetBlockers(v []string)`

SetBlockers sets Blockers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


