# CashReserveResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enforced** | **bool** | Whether the minimum cash reserve guard is active in this environment. | 
**AvailableUsd** | **string** | The user&#39;s currently available USD balance in their Global Account. | 
**CommittedUsd** | **string** | USD still counted in available_usd but already claimed by the user&#39;s open market buy orders on the Global Account, which reserve no funds at submission time. The reserve is evaluated against available_usd minus committed_usd. | 
**RequiredUsd** | **string** | The user&#39;s minimum USD cash reserve requirement. | 
**Satisfied** | **bool** | Whether available_usd minus committed_usd is at least required_usd. | 
**Breakdown** | [**CashReserveBreakdown**](CashReserveBreakdown.md) |  | 

## Methods

### NewCashReserveResponse

`func NewCashReserveResponse(enforced bool, availableUsd string, committedUsd string, requiredUsd string, satisfied bool, breakdown CashReserveBreakdown, ) *CashReserveResponse`

NewCashReserveResponse instantiates a new CashReserveResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCashReserveResponseWithDefaults

`func NewCashReserveResponseWithDefaults() *CashReserveResponse`

NewCashReserveResponseWithDefaults instantiates a new CashReserveResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnforced

`func (o *CashReserveResponse) GetEnforced() bool`

GetEnforced returns the Enforced field if non-nil, zero value otherwise.

### GetEnforcedOk

`func (o *CashReserveResponse) GetEnforcedOk() (*bool, bool)`

GetEnforcedOk returns a tuple with the Enforced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnforced

`func (o *CashReserveResponse) SetEnforced(v bool)`

SetEnforced sets Enforced field to given value.


### GetAvailableUsd

`func (o *CashReserveResponse) GetAvailableUsd() string`

GetAvailableUsd returns the AvailableUsd field if non-nil, zero value otherwise.

### GetAvailableUsdOk

`func (o *CashReserveResponse) GetAvailableUsdOk() (*string, bool)`

GetAvailableUsdOk returns a tuple with the AvailableUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableUsd

`func (o *CashReserveResponse) SetAvailableUsd(v string)`

SetAvailableUsd sets AvailableUsd field to given value.


### GetCommittedUsd

`func (o *CashReserveResponse) GetCommittedUsd() string`

GetCommittedUsd returns the CommittedUsd field if non-nil, zero value otherwise.

### GetCommittedUsdOk

`func (o *CashReserveResponse) GetCommittedUsdOk() (*string, bool)`

GetCommittedUsdOk returns a tuple with the CommittedUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommittedUsd

`func (o *CashReserveResponse) SetCommittedUsd(v string)`

SetCommittedUsd sets CommittedUsd field to given value.


### GetRequiredUsd

`func (o *CashReserveResponse) GetRequiredUsd() string`

GetRequiredUsd returns the RequiredUsd field if non-nil, zero value otherwise.

### GetRequiredUsdOk

`func (o *CashReserveResponse) GetRequiredUsdOk() (*string, bool)`

GetRequiredUsdOk returns a tuple with the RequiredUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredUsd

`func (o *CashReserveResponse) SetRequiredUsd(v string)`

SetRequiredUsd sets RequiredUsd field to given value.


### GetSatisfied

`func (o *CashReserveResponse) GetSatisfied() bool`

GetSatisfied returns the Satisfied field if non-nil, zero value otherwise.

### GetSatisfiedOk

`func (o *CashReserveResponse) GetSatisfiedOk() (*bool, bool)`

GetSatisfiedOk returns a tuple with the Satisfied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSatisfied

`func (o *CashReserveResponse) SetSatisfied(v bool)`

SetSatisfied sets Satisfied field to given value.


### GetBreakdown

`func (o *CashReserveResponse) GetBreakdown() CashReserveBreakdown`

GetBreakdown returns the Breakdown field if non-nil, zero value otherwise.

### GetBreakdownOk

`func (o *CashReserveResponse) GetBreakdownOk() (*CashReserveBreakdown, bool)`

GetBreakdownOk returns a tuple with the Breakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdown

`func (o *CashReserveResponse) SetBreakdown(v CashReserveBreakdown)`

SetBreakdown sets Breakdown field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


