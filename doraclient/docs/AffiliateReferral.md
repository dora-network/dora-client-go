# AffiliateReferral

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** |  | 
**ProgramId** | **string** |  | 
**ReferrerId** | **string** |  | 
**ReferrerUserId** | **string** |  | 
**SignupSource** | **string** | Client-reported signup hostname. Empty means unknown. | 
**FirstName** | **string** |  | 
**LastName** | **string** |  | 
**Email** | **string** |  | 
**SignedUpAt** | **time.Time** |  | 
**KycCompleted** | **bool** |  | 
**KycCompletedAt** | **time.Time** |  | 
**DiscordStatus** | **string** | No Discord membership integration is currently available. Unknown must not be interpreted as not joined. | 
**DepositCount** | **int64** |  | 
**WithdrawalCount** | **int64** |  | 
**HasTraded** | **bool** |  | 
**FirstDepositAt** | **time.Time** |  | 
**LastDepositAt** | **time.Time** |  | 
**FirstWithdrawalAt** | **time.Time** |  | 
**LastWithdrawalAt** | **time.Time** |  | 
**DailyVolumeUsd** | **string** | Sum of absolute executed FILL quantity1 on USD-quoted trades during the selected UTC day. Both buy and sell executions count, once per user-side fill. | 
**MonthlyVolumeUsd** | **string** | Same executed USD quote-notional definition for the calendar month containing date. | 
**DailyRealizedPnlUsd** | **string** | Sum of realized_pnl_settlements.realized_usd created during the selected UTC day, matching the existing PnL ranking convention. Excludes unrealized PnL; this is not total account equity change. | 
**AttributedAt** | **time.Time** | Immutable referral assignment time. Earlier activity is excluded from affiliate metrics and cash flows. | 
**MonthlyRealizedPnlUsd** | **string** | Realized PnL for the UTC calendar month containing date, including only settlements at or after attributed_at. | 

## Methods

### NewAffiliateReferral

`func NewAffiliateReferral(userId string, programId string, referrerId string, referrerUserId string, signupSource string, firstName string, lastName string, email string, signedUpAt time.Time, kycCompleted bool, kycCompletedAt time.Time, discordStatus string, depositCount int64, withdrawalCount int64, hasTraded bool, firstDepositAt time.Time, lastDepositAt time.Time, firstWithdrawalAt time.Time, lastWithdrawalAt time.Time, dailyVolumeUsd string, monthlyVolumeUsd string, dailyRealizedPnlUsd string, attributedAt time.Time, monthlyRealizedPnlUsd string, ) *AffiliateReferral`

NewAffiliateReferral instantiates a new AffiliateReferral object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliateReferralWithDefaults

`func NewAffiliateReferralWithDefaults() *AffiliateReferral`

NewAffiliateReferralWithDefaults instantiates a new AffiliateReferral object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *AffiliateReferral) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AffiliateReferral) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AffiliateReferral) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetProgramId

`func (o *AffiliateReferral) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *AffiliateReferral) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *AffiliateReferral) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetReferrerId

`func (o *AffiliateReferral) GetReferrerId() string`

GetReferrerId returns the ReferrerId field if non-nil, zero value otherwise.

### GetReferrerIdOk

`func (o *AffiliateReferral) GetReferrerIdOk() (*string, bool)`

GetReferrerIdOk returns a tuple with the ReferrerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerId

`func (o *AffiliateReferral) SetReferrerId(v string)`

SetReferrerId sets ReferrerId field to given value.


### GetReferrerUserId

`func (o *AffiliateReferral) GetReferrerUserId() string`

GetReferrerUserId returns the ReferrerUserId field if non-nil, zero value otherwise.

### GetReferrerUserIdOk

`func (o *AffiliateReferral) GetReferrerUserIdOk() (*string, bool)`

GetReferrerUserIdOk returns a tuple with the ReferrerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerUserId

`func (o *AffiliateReferral) SetReferrerUserId(v string)`

SetReferrerUserId sets ReferrerUserId field to given value.


### GetSignupSource

`func (o *AffiliateReferral) GetSignupSource() string`

GetSignupSource returns the SignupSource field if non-nil, zero value otherwise.

### GetSignupSourceOk

`func (o *AffiliateReferral) GetSignupSourceOk() (*string, bool)`

GetSignupSourceOk returns a tuple with the SignupSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignupSource

`func (o *AffiliateReferral) SetSignupSource(v string)`

SetSignupSource sets SignupSource field to given value.


### GetFirstName

`func (o *AffiliateReferral) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *AffiliateReferral) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *AffiliateReferral) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *AffiliateReferral) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *AffiliateReferral) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *AffiliateReferral) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetEmail

`func (o *AffiliateReferral) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *AffiliateReferral) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *AffiliateReferral) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetSignedUpAt

`func (o *AffiliateReferral) GetSignedUpAt() time.Time`

GetSignedUpAt returns the SignedUpAt field if non-nil, zero value otherwise.

### GetSignedUpAtOk

`func (o *AffiliateReferral) GetSignedUpAtOk() (*time.Time, bool)`

GetSignedUpAtOk returns a tuple with the SignedUpAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignedUpAt

`func (o *AffiliateReferral) SetSignedUpAt(v time.Time)`

SetSignedUpAt sets SignedUpAt field to given value.


### GetKycCompleted

`func (o *AffiliateReferral) GetKycCompleted() bool`

GetKycCompleted returns the KycCompleted field if non-nil, zero value otherwise.

### GetKycCompletedOk

`func (o *AffiliateReferral) GetKycCompletedOk() (*bool, bool)`

GetKycCompletedOk returns a tuple with the KycCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycCompleted

`func (o *AffiliateReferral) SetKycCompleted(v bool)`

SetKycCompleted sets KycCompleted field to given value.


### GetKycCompletedAt

`func (o *AffiliateReferral) GetKycCompletedAt() time.Time`

GetKycCompletedAt returns the KycCompletedAt field if non-nil, zero value otherwise.

### GetKycCompletedAtOk

`func (o *AffiliateReferral) GetKycCompletedAtOk() (*time.Time, bool)`

GetKycCompletedAtOk returns a tuple with the KycCompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycCompletedAt

`func (o *AffiliateReferral) SetKycCompletedAt(v time.Time)`

SetKycCompletedAt sets KycCompletedAt field to given value.


### GetDiscordStatus

`func (o *AffiliateReferral) GetDiscordStatus() string`

GetDiscordStatus returns the DiscordStatus field if non-nil, zero value otherwise.

### GetDiscordStatusOk

`func (o *AffiliateReferral) GetDiscordStatusOk() (*string, bool)`

GetDiscordStatusOk returns a tuple with the DiscordStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordStatus

`func (o *AffiliateReferral) SetDiscordStatus(v string)`

SetDiscordStatus sets DiscordStatus field to given value.


### GetDepositCount

`func (o *AffiliateReferral) GetDepositCount() int64`

GetDepositCount returns the DepositCount field if non-nil, zero value otherwise.

### GetDepositCountOk

`func (o *AffiliateReferral) GetDepositCountOk() (*int64, bool)`

GetDepositCountOk returns a tuple with the DepositCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositCount

`func (o *AffiliateReferral) SetDepositCount(v int64)`

SetDepositCount sets DepositCount field to given value.


### GetWithdrawalCount

`func (o *AffiliateReferral) GetWithdrawalCount() int64`

GetWithdrawalCount returns the WithdrawalCount field if non-nil, zero value otherwise.

### GetWithdrawalCountOk

`func (o *AffiliateReferral) GetWithdrawalCountOk() (*int64, bool)`

GetWithdrawalCountOk returns a tuple with the WithdrawalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithdrawalCount

`func (o *AffiliateReferral) SetWithdrawalCount(v int64)`

SetWithdrawalCount sets WithdrawalCount field to given value.


### GetHasTraded

`func (o *AffiliateReferral) GetHasTraded() bool`

GetHasTraded returns the HasTraded field if non-nil, zero value otherwise.

### GetHasTradedOk

`func (o *AffiliateReferral) GetHasTradedOk() (*bool, bool)`

GetHasTradedOk returns a tuple with the HasTraded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasTraded

`func (o *AffiliateReferral) SetHasTraded(v bool)`

SetHasTraded sets HasTraded field to given value.


### GetFirstDepositAt

`func (o *AffiliateReferral) GetFirstDepositAt() time.Time`

GetFirstDepositAt returns the FirstDepositAt field if non-nil, zero value otherwise.

### GetFirstDepositAtOk

`func (o *AffiliateReferral) GetFirstDepositAtOk() (*time.Time, bool)`

GetFirstDepositAtOk returns a tuple with the FirstDepositAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstDepositAt

`func (o *AffiliateReferral) SetFirstDepositAt(v time.Time)`

SetFirstDepositAt sets FirstDepositAt field to given value.


### GetLastDepositAt

`func (o *AffiliateReferral) GetLastDepositAt() time.Time`

GetLastDepositAt returns the LastDepositAt field if non-nil, zero value otherwise.

### GetLastDepositAtOk

`func (o *AffiliateReferral) GetLastDepositAtOk() (*time.Time, bool)`

GetLastDepositAtOk returns a tuple with the LastDepositAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDepositAt

`func (o *AffiliateReferral) SetLastDepositAt(v time.Time)`

SetLastDepositAt sets LastDepositAt field to given value.


### GetFirstWithdrawalAt

`func (o *AffiliateReferral) GetFirstWithdrawalAt() time.Time`

GetFirstWithdrawalAt returns the FirstWithdrawalAt field if non-nil, zero value otherwise.

### GetFirstWithdrawalAtOk

`func (o *AffiliateReferral) GetFirstWithdrawalAtOk() (*time.Time, bool)`

GetFirstWithdrawalAtOk returns a tuple with the FirstWithdrawalAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstWithdrawalAt

`func (o *AffiliateReferral) SetFirstWithdrawalAt(v time.Time)`

SetFirstWithdrawalAt sets FirstWithdrawalAt field to given value.


### GetLastWithdrawalAt

`func (o *AffiliateReferral) GetLastWithdrawalAt() time.Time`

GetLastWithdrawalAt returns the LastWithdrawalAt field if non-nil, zero value otherwise.

### GetLastWithdrawalAtOk

`func (o *AffiliateReferral) GetLastWithdrawalAtOk() (*time.Time, bool)`

GetLastWithdrawalAtOk returns a tuple with the LastWithdrawalAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastWithdrawalAt

`func (o *AffiliateReferral) SetLastWithdrawalAt(v time.Time)`

SetLastWithdrawalAt sets LastWithdrawalAt field to given value.


### GetDailyVolumeUsd

`func (o *AffiliateReferral) GetDailyVolumeUsd() string`

GetDailyVolumeUsd returns the DailyVolumeUsd field if non-nil, zero value otherwise.

### GetDailyVolumeUsdOk

`func (o *AffiliateReferral) GetDailyVolumeUsdOk() (*string, bool)`

GetDailyVolumeUsdOk returns a tuple with the DailyVolumeUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyVolumeUsd

`func (o *AffiliateReferral) SetDailyVolumeUsd(v string)`

SetDailyVolumeUsd sets DailyVolumeUsd field to given value.


### GetMonthlyVolumeUsd

`func (o *AffiliateReferral) GetMonthlyVolumeUsd() string`

GetMonthlyVolumeUsd returns the MonthlyVolumeUsd field if non-nil, zero value otherwise.

### GetMonthlyVolumeUsdOk

`func (o *AffiliateReferral) GetMonthlyVolumeUsdOk() (*string, bool)`

GetMonthlyVolumeUsdOk returns a tuple with the MonthlyVolumeUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyVolumeUsd

`func (o *AffiliateReferral) SetMonthlyVolumeUsd(v string)`

SetMonthlyVolumeUsd sets MonthlyVolumeUsd field to given value.


### GetDailyRealizedPnlUsd

`func (o *AffiliateReferral) GetDailyRealizedPnlUsd() string`

GetDailyRealizedPnlUsd returns the DailyRealizedPnlUsd field if non-nil, zero value otherwise.

### GetDailyRealizedPnlUsdOk

`func (o *AffiliateReferral) GetDailyRealizedPnlUsdOk() (*string, bool)`

GetDailyRealizedPnlUsdOk returns a tuple with the DailyRealizedPnlUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyRealizedPnlUsd

`func (o *AffiliateReferral) SetDailyRealizedPnlUsd(v string)`

SetDailyRealizedPnlUsd sets DailyRealizedPnlUsd field to given value.


### GetAttributedAt

`func (o *AffiliateReferral) GetAttributedAt() time.Time`

GetAttributedAt returns the AttributedAt field if non-nil, zero value otherwise.

### GetAttributedAtOk

`func (o *AffiliateReferral) GetAttributedAtOk() (*time.Time, bool)`

GetAttributedAtOk returns a tuple with the AttributedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributedAt

`func (o *AffiliateReferral) SetAttributedAt(v time.Time)`

SetAttributedAt sets AttributedAt field to given value.


### GetMonthlyRealizedPnlUsd

`func (o *AffiliateReferral) GetMonthlyRealizedPnlUsd() string`

GetMonthlyRealizedPnlUsd returns the MonthlyRealizedPnlUsd field if non-nil, zero value otherwise.

### GetMonthlyRealizedPnlUsdOk

`func (o *AffiliateReferral) GetMonthlyRealizedPnlUsdOk() (*string, bool)`

GetMonthlyRealizedPnlUsdOk returns a tuple with the MonthlyRealizedPnlUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyRealizedPnlUsd

`func (o *AffiliateReferral) SetMonthlyRealizedPnlUsd(v string)`

SetMonthlyRealizedPnlUsd sets MonthlyRealizedPnlUsd field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


