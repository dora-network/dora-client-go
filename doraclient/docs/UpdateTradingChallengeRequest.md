# UpdateTradingChallengeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to [**UpdateFieldString**](UpdateFieldString.md) | Trading challenge name. | [optional] 
**Type** | Pointer to [**UpdateFieldString**](UpdateFieldString.md) | CASH or TOURNAMENT. Only updatable while the challenge is PENDING. | [optional] 
**MaxUsers** | Pointer to [**UpdateFieldInteger**](UpdateFieldInteger.md) | Must be &gt; 0 and cannot be lowered below the number of users already registered. | [optional] 
**Start** | Pointer to [**UpdateFieldDateTime**](UpdateFieldDateTime.md) | Only updatable while the challenge is PENDING. | [optional] 
**End** | Pointer to [**UpdateFieldDateTime**](UpdateFieldDateTime.md) | Must be after start and in the future. | [optional] 
**InitialUserBalance** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt; 0. Only updatable while the challenge is PENDING. | [optional] 
**GoldPrizeQuantity** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt; 0 for a TOURNAMENT challenge. | [optional] 
**SilverPrizeQuantity** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt;&#x3D; 0. | [optional] 
**BronzePrizeQuantity** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt;&#x3D; 0. | [optional] 
**PnlCondition** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt;&#x3D; 0. Only updatable while the challenge is PENDING. | [optional] 
**TotalVolumeCondition** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt;&#x3D; 0. Only updatable while the challenge is PENDING. | [optional] 
**AvgDailyVolumeCondition** | Pointer to [**UpdateFieldDecimal**](UpdateFieldDecimal.md) | Must be &gt;&#x3D; 0. Only updatable while the challenge is PENDING. | [optional] 
**MinimumEquityPercentageCondition** | Pointer to [**UpdateFieldInteger**](UpdateFieldInteger.md) | In the range [0,100). Only updatable while the challenge is PENDING. | [optional] 

## Methods

### NewUpdateTradingChallengeRequest

`func NewUpdateTradingChallengeRequest() *UpdateTradingChallengeRequest`

NewUpdateTradingChallengeRequest instantiates a new UpdateTradingChallengeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateTradingChallengeRequestWithDefaults

`func NewUpdateTradingChallengeRequestWithDefaults() *UpdateTradingChallengeRequest`

NewUpdateTradingChallengeRequestWithDefaults instantiates a new UpdateTradingChallengeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateTradingChallengeRequest) GetName() UpdateFieldString`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateTradingChallengeRequest) GetNameOk() (*UpdateFieldString, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateTradingChallengeRequest) SetName(v UpdateFieldString)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateTradingChallengeRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *UpdateTradingChallengeRequest) GetType() UpdateFieldString`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *UpdateTradingChallengeRequest) GetTypeOk() (*UpdateFieldString, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *UpdateTradingChallengeRequest) SetType(v UpdateFieldString)`

SetType sets Type field to given value.

### HasType

`func (o *UpdateTradingChallengeRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetMaxUsers

`func (o *UpdateTradingChallengeRequest) GetMaxUsers() UpdateFieldInteger`

GetMaxUsers returns the MaxUsers field if non-nil, zero value otherwise.

### GetMaxUsersOk

`func (o *UpdateTradingChallengeRequest) GetMaxUsersOk() (*UpdateFieldInteger, bool)`

GetMaxUsersOk returns a tuple with the MaxUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsers

`func (o *UpdateTradingChallengeRequest) SetMaxUsers(v UpdateFieldInteger)`

SetMaxUsers sets MaxUsers field to given value.

### HasMaxUsers

`func (o *UpdateTradingChallengeRequest) HasMaxUsers() bool`

HasMaxUsers returns a boolean if a field has been set.

### GetStart

`func (o *UpdateTradingChallengeRequest) GetStart() UpdateFieldDateTime`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *UpdateTradingChallengeRequest) GetStartOk() (*UpdateFieldDateTime, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *UpdateTradingChallengeRequest) SetStart(v UpdateFieldDateTime)`

SetStart sets Start field to given value.

### HasStart

`func (o *UpdateTradingChallengeRequest) HasStart() bool`

HasStart returns a boolean if a field has been set.

### GetEnd

`func (o *UpdateTradingChallengeRequest) GetEnd() UpdateFieldDateTime`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *UpdateTradingChallengeRequest) GetEndOk() (*UpdateFieldDateTime, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *UpdateTradingChallengeRequest) SetEnd(v UpdateFieldDateTime)`

SetEnd sets End field to given value.

### HasEnd

`func (o *UpdateTradingChallengeRequest) HasEnd() bool`

HasEnd returns a boolean if a field has been set.

### GetInitialUserBalance

`func (o *UpdateTradingChallengeRequest) GetInitialUserBalance() UpdateFieldDecimal`

GetInitialUserBalance returns the InitialUserBalance field if non-nil, zero value otherwise.

### GetInitialUserBalanceOk

`func (o *UpdateTradingChallengeRequest) GetInitialUserBalanceOk() (*UpdateFieldDecimal, bool)`

GetInitialUserBalanceOk returns a tuple with the InitialUserBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialUserBalance

`func (o *UpdateTradingChallengeRequest) SetInitialUserBalance(v UpdateFieldDecimal)`

SetInitialUserBalance sets InitialUserBalance field to given value.

### HasInitialUserBalance

`func (o *UpdateTradingChallengeRequest) HasInitialUserBalance() bool`

HasInitialUserBalance returns a boolean if a field has been set.

### GetGoldPrizeQuantity

`func (o *UpdateTradingChallengeRequest) GetGoldPrizeQuantity() UpdateFieldDecimal`

GetGoldPrizeQuantity returns the GoldPrizeQuantity field if non-nil, zero value otherwise.

### GetGoldPrizeQuantityOk

`func (o *UpdateTradingChallengeRequest) GetGoldPrizeQuantityOk() (*UpdateFieldDecimal, bool)`

GetGoldPrizeQuantityOk returns a tuple with the GoldPrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoldPrizeQuantity

`func (o *UpdateTradingChallengeRequest) SetGoldPrizeQuantity(v UpdateFieldDecimal)`

SetGoldPrizeQuantity sets GoldPrizeQuantity field to given value.

### HasGoldPrizeQuantity

`func (o *UpdateTradingChallengeRequest) HasGoldPrizeQuantity() bool`

HasGoldPrizeQuantity returns a boolean if a field has been set.

### GetSilverPrizeQuantity

`func (o *UpdateTradingChallengeRequest) GetSilverPrizeQuantity() UpdateFieldDecimal`

GetSilverPrizeQuantity returns the SilverPrizeQuantity field if non-nil, zero value otherwise.

### GetSilverPrizeQuantityOk

`func (o *UpdateTradingChallengeRequest) GetSilverPrizeQuantityOk() (*UpdateFieldDecimal, bool)`

GetSilverPrizeQuantityOk returns a tuple with the SilverPrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSilverPrizeQuantity

`func (o *UpdateTradingChallengeRequest) SetSilverPrizeQuantity(v UpdateFieldDecimal)`

SetSilverPrizeQuantity sets SilverPrizeQuantity field to given value.

### HasSilverPrizeQuantity

`func (o *UpdateTradingChallengeRequest) HasSilverPrizeQuantity() bool`

HasSilverPrizeQuantity returns a boolean if a field has been set.

### GetBronzePrizeQuantity

`func (o *UpdateTradingChallengeRequest) GetBronzePrizeQuantity() UpdateFieldDecimal`

GetBronzePrizeQuantity returns the BronzePrizeQuantity field if non-nil, zero value otherwise.

### GetBronzePrizeQuantityOk

`func (o *UpdateTradingChallengeRequest) GetBronzePrizeQuantityOk() (*UpdateFieldDecimal, bool)`

GetBronzePrizeQuantityOk returns a tuple with the BronzePrizeQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBronzePrizeQuantity

`func (o *UpdateTradingChallengeRequest) SetBronzePrizeQuantity(v UpdateFieldDecimal)`

SetBronzePrizeQuantity sets BronzePrizeQuantity field to given value.

### HasBronzePrizeQuantity

`func (o *UpdateTradingChallengeRequest) HasBronzePrizeQuantity() bool`

HasBronzePrizeQuantity returns a boolean if a field has been set.

### GetPnlCondition

`func (o *UpdateTradingChallengeRequest) GetPnlCondition() UpdateFieldDecimal`

GetPnlCondition returns the PnlCondition field if non-nil, zero value otherwise.

### GetPnlConditionOk

`func (o *UpdateTradingChallengeRequest) GetPnlConditionOk() (*UpdateFieldDecimal, bool)`

GetPnlConditionOk returns a tuple with the PnlCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPnlCondition

`func (o *UpdateTradingChallengeRequest) SetPnlCondition(v UpdateFieldDecimal)`

SetPnlCondition sets PnlCondition field to given value.

### HasPnlCondition

`func (o *UpdateTradingChallengeRequest) HasPnlCondition() bool`

HasPnlCondition returns a boolean if a field has been set.

### GetTotalVolumeCondition

`func (o *UpdateTradingChallengeRequest) GetTotalVolumeCondition() UpdateFieldDecimal`

GetTotalVolumeCondition returns the TotalVolumeCondition field if non-nil, zero value otherwise.

### GetTotalVolumeConditionOk

`func (o *UpdateTradingChallengeRequest) GetTotalVolumeConditionOk() (*UpdateFieldDecimal, bool)`

GetTotalVolumeConditionOk returns a tuple with the TotalVolumeCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalVolumeCondition

`func (o *UpdateTradingChallengeRequest) SetTotalVolumeCondition(v UpdateFieldDecimal)`

SetTotalVolumeCondition sets TotalVolumeCondition field to given value.

### HasTotalVolumeCondition

`func (o *UpdateTradingChallengeRequest) HasTotalVolumeCondition() bool`

HasTotalVolumeCondition returns a boolean if a field has been set.

### GetAvgDailyVolumeCondition

`func (o *UpdateTradingChallengeRequest) GetAvgDailyVolumeCondition() UpdateFieldDecimal`

GetAvgDailyVolumeCondition returns the AvgDailyVolumeCondition field if non-nil, zero value otherwise.

### GetAvgDailyVolumeConditionOk

`func (o *UpdateTradingChallengeRequest) GetAvgDailyVolumeConditionOk() (*UpdateFieldDecimal, bool)`

GetAvgDailyVolumeConditionOk returns a tuple with the AvgDailyVolumeCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgDailyVolumeCondition

`func (o *UpdateTradingChallengeRequest) SetAvgDailyVolumeCondition(v UpdateFieldDecimal)`

SetAvgDailyVolumeCondition sets AvgDailyVolumeCondition field to given value.

### HasAvgDailyVolumeCondition

`func (o *UpdateTradingChallengeRequest) HasAvgDailyVolumeCondition() bool`

HasAvgDailyVolumeCondition returns a boolean if a field has been set.

### GetMinimumEquityPercentageCondition

`func (o *UpdateTradingChallengeRequest) GetMinimumEquityPercentageCondition() UpdateFieldInteger`

GetMinimumEquityPercentageCondition returns the MinimumEquityPercentageCondition field if non-nil, zero value otherwise.

### GetMinimumEquityPercentageConditionOk

`func (o *UpdateTradingChallengeRequest) GetMinimumEquityPercentageConditionOk() (*UpdateFieldInteger, bool)`

GetMinimumEquityPercentageConditionOk returns a tuple with the MinimumEquityPercentageCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumEquityPercentageCondition

`func (o *UpdateTradingChallengeRequest) SetMinimumEquityPercentageCondition(v UpdateFieldInteger)`

SetMinimumEquityPercentageCondition sets MinimumEquityPercentageCondition field to given value.

### HasMinimumEquityPercentageCondition

`func (o *UpdateTradingChallengeRequest) HasMinimumEquityPercentageCondition() bool`

HasMinimumEquityPercentageCondition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


