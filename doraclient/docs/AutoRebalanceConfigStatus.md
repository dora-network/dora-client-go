# AutoRebalanceConfigStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**Enabled** | **bool** |  | 
**MinUtilization** | **string** |  | 
**MaxUtilization** | **string** |  | 
**AvailableUsd** | Pointer to **string** |  | [optional] 
**BorrowedValue** | Pointer to **string** |  | [optional] 
**BorrowLimit** | Pointer to **string** |  | [optional] 
**CurrentUtilization** | Pointer to **NullableString** |  | [optional] 
**AboveMax** | Pointer to **bool** | True when current_utilization is greater than max_utilization. | [optional] 
**InActiveLiquidation** | Pointer to **bool** |  | [optional] 
**LastRebalanceOutcome** | Pointer to **string** | Most recent persisted auto-rebalance attempt status for this account, when available. | [optional] 

## Methods

### NewAutoRebalanceConfigStatus

`func NewAutoRebalanceConfigStatus(accountId string, enabled bool, minUtilization string, maxUtilization string, ) *AutoRebalanceConfigStatus`

NewAutoRebalanceConfigStatus instantiates a new AutoRebalanceConfigStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAutoRebalanceConfigStatusWithDefaults

`func NewAutoRebalanceConfigStatusWithDefaults() *AutoRebalanceConfigStatus`

NewAutoRebalanceConfigStatusWithDefaults instantiates a new AutoRebalanceConfigStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *AutoRebalanceConfigStatus) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AutoRebalanceConfigStatus) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AutoRebalanceConfigStatus) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetEnabled

`func (o *AutoRebalanceConfigStatus) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AutoRebalanceConfigStatus) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AutoRebalanceConfigStatus) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetMinUtilization

`func (o *AutoRebalanceConfigStatus) GetMinUtilization() string`

GetMinUtilization returns the MinUtilization field if non-nil, zero value otherwise.

### GetMinUtilizationOk

`func (o *AutoRebalanceConfigStatus) GetMinUtilizationOk() (*string, bool)`

GetMinUtilizationOk returns a tuple with the MinUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinUtilization

`func (o *AutoRebalanceConfigStatus) SetMinUtilization(v string)`

SetMinUtilization sets MinUtilization field to given value.


### GetMaxUtilization

`func (o *AutoRebalanceConfigStatus) GetMaxUtilization() string`

GetMaxUtilization returns the MaxUtilization field if non-nil, zero value otherwise.

### GetMaxUtilizationOk

`func (o *AutoRebalanceConfigStatus) GetMaxUtilizationOk() (*string, bool)`

GetMaxUtilizationOk returns a tuple with the MaxUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUtilization

`func (o *AutoRebalanceConfigStatus) SetMaxUtilization(v string)`

SetMaxUtilization sets MaxUtilization field to given value.


### GetAvailableUsd

`func (o *AutoRebalanceConfigStatus) GetAvailableUsd() string`

GetAvailableUsd returns the AvailableUsd field if non-nil, zero value otherwise.

### GetAvailableUsdOk

`func (o *AutoRebalanceConfigStatus) GetAvailableUsdOk() (*string, bool)`

GetAvailableUsdOk returns a tuple with the AvailableUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableUsd

`func (o *AutoRebalanceConfigStatus) SetAvailableUsd(v string)`

SetAvailableUsd sets AvailableUsd field to given value.

### HasAvailableUsd

`func (o *AutoRebalanceConfigStatus) HasAvailableUsd() bool`

HasAvailableUsd returns a boolean if a field has been set.

### GetBorrowedValue

`func (o *AutoRebalanceConfigStatus) GetBorrowedValue() string`

GetBorrowedValue returns the BorrowedValue field if non-nil, zero value otherwise.

### GetBorrowedValueOk

`func (o *AutoRebalanceConfigStatus) GetBorrowedValueOk() (*string, bool)`

GetBorrowedValueOk returns a tuple with the BorrowedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowedValue

`func (o *AutoRebalanceConfigStatus) SetBorrowedValue(v string)`

SetBorrowedValue sets BorrowedValue field to given value.

### HasBorrowedValue

`func (o *AutoRebalanceConfigStatus) HasBorrowedValue() bool`

HasBorrowedValue returns a boolean if a field has been set.

### GetBorrowLimit

`func (o *AutoRebalanceConfigStatus) GetBorrowLimit() string`

GetBorrowLimit returns the BorrowLimit field if non-nil, zero value otherwise.

### GetBorrowLimitOk

`func (o *AutoRebalanceConfigStatus) GetBorrowLimitOk() (*string, bool)`

GetBorrowLimitOk returns a tuple with the BorrowLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowLimit

`func (o *AutoRebalanceConfigStatus) SetBorrowLimit(v string)`

SetBorrowLimit sets BorrowLimit field to given value.

### HasBorrowLimit

`func (o *AutoRebalanceConfigStatus) HasBorrowLimit() bool`

HasBorrowLimit returns a boolean if a field has been set.

### GetCurrentUtilization

`func (o *AutoRebalanceConfigStatus) GetCurrentUtilization() string`

GetCurrentUtilization returns the CurrentUtilization field if non-nil, zero value otherwise.

### GetCurrentUtilizationOk

`func (o *AutoRebalanceConfigStatus) GetCurrentUtilizationOk() (*string, bool)`

GetCurrentUtilizationOk returns a tuple with the CurrentUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentUtilization

`func (o *AutoRebalanceConfigStatus) SetCurrentUtilization(v string)`

SetCurrentUtilization sets CurrentUtilization field to given value.

### HasCurrentUtilization

`func (o *AutoRebalanceConfigStatus) HasCurrentUtilization() bool`

HasCurrentUtilization returns a boolean if a field has been set.

### SetCurrentUtilizationNil

`func (o *AutoRebalanceConfigStatus) SetCurrentUtilizationNil(b bool)`

 SetCurrentUtilizationNil sets the value for CurrentUtilization to be an explicit nil

### UnsetCurrentUtilization
`func (o *AutoRebalanceConfigStatus) UnsetCurrentUtilization()`

UnsetCurrentUtilization ensures that no value is present for CurrentUtilization, not even an explicit nil
### GetAboveMax

`func (o *AutoRebalanceConfigStatus) GetAboveMax() bool`

GetAboveMax returns the AboveMax field if non-nil, zero value otherwise.

### GetAboveMaxOk

`func (o *AutoRebalanceConfigStatus) GetAboveMaxOk() (*bool, bool)`

GetAboveMaxOk returns a tuple with the AboveMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAboveMax

`func (o *AutoRebalanceConfigStatus) SetAboveMax(v bool)`

SetAboveMax sets AboveMax field to given value.

### HasAboveMax

`func (o *AutoRebalanceConfigStatus) HasAboveMax() bool`

HasAboveMax returns a boolean if a field has been set.

### GetInActiveLiquidation

`func (o *AutoRebalanceConfigStatus) GetInActiveLiquidation() bool`

GetInActiveLiquidation returns the InActiveLiquidation field if non-nil, zero value otherwise.

### GetInActiveLiquidationOk

`func (o *AutoRebalanceConfigStatus) GetInActiveLiquidationOk() (*bool, bool)`

GetInActiveLiquidationOk returns a tuple with the InActiveLiquidation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInActiveLiquidation

`func (o *AutoRebalanceConfigStatus) SetInActiveLiquidation(v bool)`

SetInActiveLiquidation sets InActiveLiquidation field to given value.

### HasInActiveLiquidation

`func (o *AutoRebalanceConfigStatus) HasInActiveLiquidation() bool`

HasInActiveLiquidation returns a boolean if a field has been set.

### GetLastRebalanceOutcome

`func (o *AutoRebalanceConfigStatus) GetLastRebalanceOutcome() string`

GetLastRebalanceOutcome returns the LastRebalanceOutcome field if non-nil, zero value otherwise.

### GetLastRebalanceOutcomeOk

`func (o *AutoRebalanceConfigStatus) GetLastRebalanceOutcomeOk() (*string, bool)`

GetLastRebalanceOutcomeOk returns a tuple with the LastRebalanceOutcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRebalanceOutcome

`func (o *AutoRebalanceConfigStatus) SetLastRebalanceOutcome(v string)`

SetLastRebalanceOutcome sets LastRebalanceOutcome field to given value.

### HasLastRebalanceOutcome

`func (o *AutoRebalanceConfigStatus) HasLastRebalanceOutcome() bool`

HasLastRebalanceOutcome returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


