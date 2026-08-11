# CreateTradingChallengeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | **string** |  | 
**Name** | **string** | Trading challenge name | 
**Type** | [**TradingChallengeType**](TradingChallengeType.md) |  | 
**MaxUsers** | **int32** |  | 
**Start** | **time.Time** |  | 
**End** | **time.Time** |  | 
**InitialUserBalance** | **string** |  | 
**GoldPrizeQuantity** | Pointer to **string** |  | [optional] 
**SilverPrizeQuantity** | Pointer to **string** |  | [optional] 
**BronzePrizeQuantity** | Pointer to **string** |  | [optional] 
**PnlCondition** | Pointer to **string** |  | [optional] 
**TotalVolumeCondition** | Pointer to **string** |  | [optional] 
**AvgDailyVolumeCondition** | Pointer to **string** |  | [optional] 
**MinimumEquityPercentageCondition** | Pointer to **int32** |  | [optional] 
**Users** | Pointer to **[]string** |  | [optional] 

## Methods

### NewCreateTradingChallengeRequest

`func NewCreateTradingChallengeRequest(tenantId string, name string, type_ TradingChallengeType, maxUsers int32, start time.Time, end time.Time, initialUserBalance string, ) *CreateTradingChallengeRequest`

NewCreateTradingChallengeRequest instantiates a new CreateTradingChallengeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTradingChallengeRequestWithDefaults

`func NewCreateTradingChallengeRequestWithDefaults() *CreateTradingChallengeRequest`

NewCreateTradingChallengeRequestWithDefaults instantiates a new CreateTradingChallengeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *CreateTradingChallengeRequest) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *CreateTradingChallengeRequest) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *CreateTradingChallengeRequest) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetName

`func (o *CreateTradingChallengeRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateTradingChallengeRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateTradingChallengeRequest) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *CreateTradingChallengeRequest) GetType() TradingChallengeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateTradingChallengeRequest) GetTypeOk() (*TradingChallengeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateTradingChallengeRequest) SetType(v TradingChallengeType)`

SetType sets Type field to given value.


### GetMaxUsers

`func (o *CreateTradingChallengeRequest) GetMaxUsers() int32`

GetMaxUsers returns the MaxUsers field if non-nil, zero value otherwise.

### GetMaxUsersOk

`func (o *CreateTradingChallengeRequest) GetMaxUsersOk() (*int32, bool)`

GetMaxUsersOk returns a tuple with the MaxUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsers

`func (o *CreateTradingChallengeRequest) SetMaxUsers(v int32)`

SetMaxUsers sets MaxUsers field to given value.


### GetStart

`func (o *CreateTradingChallengeRequest) GetStart() time.Time`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *CreateTradingChallengeRequest) GetStartOk() (*time.Time, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *CreateTradingChallengeRequest) SetStart(v time.Time)`

SetStart sets Start field to given value.


### GetEnd

`func (o *CreateTradingChallengeRequest) GetEnd() time.Time`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *CreateTradingChallengeRequest) GetEndOk() (*time.Time, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *CreateTradingChallengeRequest) SetEnd(v time.Time)`

SetEnd sets End field to given value.


### GetInitialUserBalance

`func (o *CreateTradingChallengeRequest) GetInitialUserBalance() string`

GetInitialUserBalance returns the InitialUserBalance field if non-nil, zero value otherwise.

### GetInitialUserBalanceOk

`func (o *CreateTradingChallengeRequest) GetInitialUserBalanceOk() (*string, bool)`

GetInitialUserBalanceOk returns a tuple with the InitialUserBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialUserBalance

`func (o *CreateTradingChallengeRequest) SetInitialUserBalance(v string)`

SetInitialUserBalance sets InitialUserBalance field to given value.


### GetGoldPrizeQuantity

`func (o *CreateTradingChallengeRequest) GetGoldPrizeQuantity() string`

GetGoldPrizeQuantity returns the GoldPrizeQuantity field if non-nil, zero value otherwise.

### GetGoldPrizeQuantityOk

`func (o *CreateTradingChallengeRequest) GetGoldPrizeQuantityOk() (*string, bool)`

GetGoldPrizeQuantityOk returns a tuple with the GoldPrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoldPrizeQuantity

`func (o *CreateTradingChallengeRequest) SetGoldPrizeQuantity(v string)`

SetGoldPrizeQuantity sets GoldPrizeQuantity field to given value.

### HasGoldPrizeQuantity

`func (o *CreateTradingChallengeRequest) HasGoldPrizeQuantity() bool`

HasGoldPrizeQuantity returns a boolean if a field has been set.

### GetSilverPrizeQuantity

`func (o *CreateTradingChallengeRequest) GetSilverPrizeQuantity() string`

GetSilverPrizeQuantity returns the SilverPrizeQuantity field if non-nil, zero value otherwise.

### GetSilverPrizeQuantityOk

`func (o *CreateTradingChallengeRequest) GetSilverPrizeQuantityOk() (*string, bool)`

GetSilverPrizeQuantityOk returns a tuple with the SilverPrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSilverPrizeQuantity

`func (o *CreateTradingChallengeRequest) SetSilverPrizeQuantity(v string)`

SetSilverPrizeQuantity sets SilverPrizeQuantity field to given value.

### HasSilverPrizeQuantity

`func (o *CreateTradingChallengeRequest) HasSilverPrizeQuantity() bool`

HasSilverPrizeQuantity returns a boolean if a field has been set.

### GetBronzePrizeQuantity

`func (o *CreateTradingChallengeRequest) GetBronzePrizeQuantity() string`

GetBronzePrizeQuantity returns the BronzePrizeQuantity field if non-nil, zero value otherwise.

### GetBronzePrizeQuantityOk

`func (o *CreateTradingChallengeRequest) GetBronzePrizeQuantityOk() (*string, bool)`

GetBronzePrizeQuantityOk returns a tuple with the BronzePrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBronzePrizeQuantity

`func (o *CreateTradingChallengeRequest) SetBronzePrizeQuantity(v string)`

SetBronzePrizeQuantity sets BronzePrizeQuantity field to given value.

### HasBronzePrizeQuantity

`func (o *CreateTradingChallengeRequest) HasBronzePrizeQuantity() bool`

HasBronzePrizeQuantity returns a boolean if a field has been set.

### GetPnlCondition

`func (o *CreateTradingChallengeRequest) GetPnlCondition() string`

GetPnlCondition returns the PnlCondition field if non-nil, zero value otherwise.

### GetPnlConditionOk

`func (o *CreateTradingChallengeRequest) GetPnlConditionOk() (*string, bool)`

GetPnlConditionOk returns a tuple with the PnlCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPnlCondition

`func (o *CreateTradingChallengeRequest) SetPnlCondition(v string)`

SetPnlCondition sets PnlCondition field to given value.

### HasPnlCondition

`func (o *CreateTradingChallengeRequest) HasPnlCondition() bool`

HasPnlCondition returns a boolean if a field has been set.

### GetTotalVolumeCondition

`func (o *CreateTradingChallengeRequest) GetTotalVolumeCondition() string`

GetTotalVolumeCondition returns the TotalVolumeCondition field if non-nil, zero value otherwise.

### GetTotalVolumeConditionOk

`func (o *CreateTradingChallengeRequest) GetTotalVolumeConditionOk() (*string, bool)`

GetTotalVolumeConditionOk returns a tuple with the TotalVolumeCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalVolumeCondition

`func (o *CreateTradingChallengeRequest) SetTotalVolumeCondition(v string)`

SetTotalVolumeCondition sets TotalVolumeCondition field to given value.

### HasTotalVolumeCondition

`func (o *CreateTradingChallengeRequest) HasTotalVolumeCondition() bool`

HasTotalVolumeCondition returns a boolean if a field has been set.

### GetAvgDailyVolumeCondition

`func (o *CreateTradingChallengeRequest) GetAvgDailyVolumeCondition() string`

GetAvgDailyVolumeCondition returns the AvgDailyVolumeCondition field if non-nil, zero value otherwise.

### GetAvgDailyVolumeConditionOk

`func (o *CreateTradingChallengeRequest) GetAvgDailyVolumeConditionOk() (*string, bool)`

GetAvgDailyVolumeConditionOk returns a tuple with the AvgDailyVolumeCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgDailyVolumeCondition

`func (o *CreateTradingChallengeRequest) SetAvgDailyVolumeCondition(v string)`

SetAvgDailyVolumeCondition sets AvgDailyVolumeCondition field to given value.

### HasAvgDailyVolumeCondition

`func (o *CreateTradingChallengeRequest) HasAvgDailyVolumeCondition() bool`

HasAvgDailyVolumeCondition returns a boolean if a field has been set.

### GetMinimumEquityPercentageCondition

`func (o *CreateTradingChallengeRequest) GetMinimumEquityPercentageCondition() int32`

GetMinimumEquityPercentageCondition returns the MinimumEquityPercentageCondition field if non-nil, zero value otherwise.

### GetMinimumEquityPercentageConditionOk

`func (o *CreateTradingChallengeRequest) GetMinimumEquityPercentageConditionOk() (*int32, bool)`

GetMinimumEquityPercentageConditionOk returns a tuple with the MinimumEquityPercentageCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumEquityPercentageCondition

`func (o *CreateTradingChallengeRequest) SetMinimumEquityPercentageCondition(v int32)`

SetMinimumEquityPercentageCondition sets MinimumEquityPercentageCondition field to given value.

### HasMinimumEquityPercentageCondition

`func (o *CreateTradingChallengeRequest) HasMinimumEquityPercentageCondition() bool`

HasMinimumEquityPercentageCondition returns a boolean if a field has been set.

### GetUsers

`func (o *CreateTradingChallengeRequest) GetUsers() []string`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *CreateTradingChallengeRequest) GetUsersOk() (*[]string, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *CreateTradingChallengeRequest) SetUsers(v []string)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *CreateTradingChallengeRequest) HasUsers() bool`

HasUsers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


