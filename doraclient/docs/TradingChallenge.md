# TradingChallenge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | Pointer to **string** | Trading challenge name | [optional] 
**TenantId** | **string** |  | 
**Type** | [**TradingChallengeType**](TradingChallengeType.md) |  | 
**Status** | [**TradingChallengeStatus**](TradingChallengeStatus.md) |  | 
**MaxUsers** | **int32** |  | 
**StartAt** | **time.Time** |  | 
**EndAt** | **time.Time** |  | 
**InitialUserBalance** | **string** |  | 
**GoldPrizeQuantity** | **string** |  | 
**SilverPrizeQuantity** | **string** |  | 
**BronzePrizeQuantity** | **string** |  | 
**PnlCondition** | **string** |  | 
**TotalVolumeCondition** | **string** |  | 
**AvgDailyVolumeCondition** | **string** |  | 
**MinimumEquityPercentageCondition** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 
**LastProcessedAt** | Pointer to **time.Time** |  | [optional] 
**Users** | Pointer to **[]string** |  | [optional] 
**UsersCount** | **int32** |  | 
**Qr** | Pointer to [**TradingChallengeQR**](TradingChallengeQR.md) |  | [optional] 
**WorstCaseExposure** | Pointer to **string** | For QR_PROMO, max_users multiplied by initial_user_balance plus max_reward_amount. | [optional] 

## Methods

### NewTradingChallenge

`func NewTradingChallenge(id string, tenantId string, type_ TradingChallengeType, status TradingChallengeStatus, maxUsers int32, startAt time.Time, endAt time.Time, initialUserBalance string, goldPrizeQuantity string, silverPrizeQuantity string, bronzePrizeQuantity string, pnlCondition string, totalVolumeCondition string, avgDailyVolumeCondition string, minimumEquityPercentageCondition int32, createdAt time.Time, usersCount int32, ) *TradingChallenge`

NewTradingChallenge instantiates a new TradingChallenge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradingChallengeWithDefaults

`func NewTradingChallengeWithDefaults() *TradingChallenge`

NewTradingChallengeWithDefaults instantiates a new TradingChallenge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TradingChallenge) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TradingChallenge) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TradingChallenge) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *TradingChallenge) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TradingChallenge) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TradingChallenge) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TradingChallenge) HasName() bool`

HasName returns a boolean if a field has been set.

### GetTenantId

`func (o *TradingChallenge) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *TradingChallenge) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *TradingChallenge) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetType

`func (o *TradingChallenge) GetType() TradingChallengeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TradingChallenge) GetTypeOk() (*TradingChallengeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TradingChallenge) SetType(v TradingChallengeType)`

SetType sets Type field to given value.


### GetStatus

`func (o *TradingChallenge) GetStatus() TradingChallengeStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TradingChallenge) GetStatusOk() (*TradingChallengeStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TradingChallenge) SetStatus(v TradingChallengeStatus)`

SetStatus sets Status field to given value.


### GetMaxUsers

`func (o *TradingChallenge) GetMaxUsers() int32`

GetMaxUsers returns the MaxUsers field if non-nil, zero value otherwise.

### GetMaxUsersOk

`func (o *TradingChallenge) GetMaxUsersOk() (*int32, bool)`

GetMaxUsersOk returns a tuple with the MaxUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsers

`func (o *TradingChallenge) SetMaxUsers(v int32)`

SetMaxUsers sets MaxUsers field to given value.


### GetStartAt

`func (o *TradingChallenge) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *TradingChallenge) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *TradingChallenge) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.


### GetEndAt

`func (o *TradingChallenge) GetEndAt() time.Time`

GetEndAt returns the EndAt field if non-nil, zero value otherwise.

### GetEndAtOk

`func (o *TradingChallenge) GetEndAtOk() (*time.Time, bool)`

GetEndAtOk returns a tuple with the EndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndAt

`func (o *TradingChallenge) SetEndAt(v time.Time)`

SetEndAt sets EndAt field to given value.


### GetInitialUserBalance

`func (o *TradingChallenge) GetInitialUserBalance() string`

GetInitialUserBalance returns the InitialUserBalance field if non-nil, zero value otherwise.

### GetInitialUserBalanceOk

`func (o *TradingChallenge) GetInitialUserBalanceOk() (*string, bool)`

GetInitialUserBalanceOk returns a tuple with the InitialUserBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialUserBalance

`func (o *TradingChallenge) SetInitialUserBalance(v string)`

SetInitialUserBalance sets InitialUserBalance field to given value.


### GetGoldPrizeQuantity

`func (o *TradingChallenge) GetGoldPrizeQuantity() string`

GetGoldPrizeQuantity returns the GoldPrizeQuantity field if non-nil, zero value otherwise.

### GetGoldPrizeQuantityOk

`func (o *TradingChallenge) GetGoldPrizeQuantityOk() (*string, bool)`

GetGoldPrizeQuantityOk returns a tuple with the GoldPrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoldPrizeQuantity

`func (o *TradingChallenge) SetGoldPrizeQuantity(v string)`

SetGoldPrizeQuantity sets GoldPrizeQuantity field to given value.


### GetSilverPrizeQuantity

`func (o *TradingChallenge) GetSilverPrizeQuantity() string`

GetSilverPrizeQuantity returns the SilverPrizeQuantity field if non-nil, zero value otherwise.

### GetSilverPrizeQuantityOk

`func (o *TradingChallenge) GetSilverPrizeQuantityOk() (*string, bool)`

GetSilverPrizeQuantityOk returns a tuple with the SilverPrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSilverPrizeQuantity

`func (o *TradingChallenge) SetSilverPrizeQuantity(v string)`

SetSilverPrizeQuantity sets SilverPrizeQuantity field to given value.


### GetBronzePrizeQuantity

`func (o *TradingChallenge) GetBronzePrizeQuantity() string`

GetBronzePrizeQuantity returns the BronzePrizeQuantity field if non-nil, zero value otherwise.

### GetBronzePrizeQuantityOk

`func (o *TradingChallenge) GetBronzePrizeQuantityOk() (*string, bool)`

GetBronzePrizeQuantityOk returns a tuple with the BronzePrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBronzePrizeQuantity

`func (o *TradingChallenge) SetBronzePrizeQuantity(v string)`

SetBronzePrizeQuantity sets BronzePrizeQuantity field to given value.


### GetPnlCondition

`func (o *TradingChallenge) GetPnlCondition() string`

GetPnlCondition returns the PnlCondition field if non-nil, zero value otherwise.

### GetPnlConditionOk

`func (o *TradingChallenge) GetPnlConditionOk() (*string, bool)`

GetPnlConditionOk returns a tuple with the PnlCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPnlCondition

`func (o *TradingChallenge) SetPnlCondition(v string)`

SetPnlCondition sets PnlCondition field to given value.


### GetTotalVolumeCondition

`func (o *TradingChallenge) GetTotalVolumeCondition() string`

GetTotalVolumeCondition returns the TotalVolumeCondition field if non-nil, zero value otherwise.

### GetTotalVolumeConditionOk

`func (o *TradingChallenge) GetTotalVolumeConditionOk() (*string, bool)`

GetTotalVolumeConditionOk returns a tuple with the TotalVolumeCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalVolumeCondition

`func (o *TradingChallenge) SetTotalVolumeCondition(v string)`

SetTotalVolumeCondition sets TotalVolumeCondition field to given value.


### GetAvgDailyVolumeCondition

`func (o *TradingChallenge) GetAvgDailyVolumeCondition() string`

GetAvgDailyVolumeCondition returns the AvgDailyVolumeCondition field if non-nil, zero value otherwise.

### GetAvgDailyVolumeConditionOk

`func (o *TradingChallenge) GetAvgDailyVolumeConditionOk() (*string, bool)`

GetAvgDailyVolumeConditionOk returns a tuple with the AvgDailyVolumeCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgDailyVolumeCondition

`func (o *TradingChallenge) SetAvgDailyVolumeCondition(v string)`

SetAvgDailyVolumeCondition sets AvgDailyVolumeCondition field to given value.


### GetMinimumEquityPercentageCondition

`func (o *TradingChallenge) GetMinimumEquityPercentageCondition() int32`

GetMinimumEquityPercentageCondition returns the MinimumEquityPercentageCondition field if non-nil, zero value otherwise.

### GetMinimumEquityPercentageConditionOk

`func (o *TradingChallenge) GetMinimumEquityPercentageConditionOk() (*int32, bool)`

GetMinimumEquityPercentageConditionOk returns a tuple with the MinimumEquityPercentageCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumEquityPercentageCondition

`func (o *TradingChallenge) SetMinimumEquityPercentageCondition(v int32)`

SetMinimumEquityPercentageCondition sets MinimumEquityPercentageCondition field to given value.


### GetCreatedAt

`func (o *TradingChallenge) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TradingChallenge) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TradingChallenge) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetLastProcessedAt

`func (o *TradingChallenge) GetLastProcessedAt() time.Time`

GetLastProcessedAt returns the LastProcessedAt field if non-nil, zero value otherwise.

### GetLastProcessedAtOk

`func (o *TradingChallenge) GetLastProcessedAtOk() (*time.Time, bool)`

GetLastProcessedAtOk returns a tuple with the LastProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastProcessedAt

`func (o *TradingChallenge) SetLastProcessedAt(v time.Time)`

SetLastProcessedAt sets LastProcessedAt field to given value.

### HasLastProcessedAt

`func (o *TradingChallenge) HasLastProcessedAt() bool`

HasLastProcessedAt returns a boolean if a field has been set.

### GetUsers

`func (o *TradingChallenge) GetUsers() []string`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *TradingChallenge) GetUsersOk() (*[]string, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *TradingChallenge) SetUsers(v []string)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *TradingChallenge) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetUsersCount

`func (o *TradingChallenge) GetUsersCount() int32`

GetUsersCount returns the UsersCount field if non-nil, zero value otherwise.

### GetUsersCountOk

`func (o *TradingChallenge) GetUsersCountOk() (*int32, bool)`

GetUsersCountOk returns a tuple with the UsersCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersCount

`func (o *TradingChallenge) SetUsersCount(v int32)`

SetUsersCount sets UsersCount field to given value.


### GetQr

`func (o *TradingChallenge) GetQr() TradingChallengeQR`

GetQr returns the Qr field if non-nil, zero value otherwise.

### GetQrOk

`func (o *TradingChallenge) GetQrOk() (*TradingChallengeQR, bool)`

GetQrOk returns a tuple with the Qr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQr

`func (o *TradingChallenge) SetQr(v TradingChallengeQR)`

SetQr sets Qr field to given value.

### HasQr

`func (o *TradingChallenge) HasQr() bool`

HasQr returns a boolean if a field has been set.

### GetWorstCaseExposure

`func (o *TradingChallenge) GetWorstCaseExposure() string`

GetWorstCaseExposure returns the WorstCaseExposure field if non-nil, zero value otherwise.

### GetWorstCaseExposureOk

`func (o *TradingChallenge) GetWorstCaseExposureOk() (*string, bool)`

GetWorstCaseExposureOk returns a tuple with the WorstCaseExposure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorstCaseExposure

`func (o *TradingChallenge) SetWorstCaseExposure(v string)`

SetWorstCaseExposure sets WorstCaseExposure field to given value.

### HasWorstCaseExposure

`func (o *TradingChallenge) HasWorstCaseExposure() bool`

HasWorstCaseExposure returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


