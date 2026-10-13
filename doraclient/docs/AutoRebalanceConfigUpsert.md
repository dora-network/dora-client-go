# AutoRebalanceConfigUpsert

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**Enabled** | **bool** |  | 
**MinUtilization** | **string** | Lower utilization threshold, greater than 0 and less than max_utilization. | 
**MaxUtilization** | **string** | Upper utilization threshold, greater than min_utilization and less than or equal to 1. | 

## Methods

### NewAutoRebalanceConfigUpsert

`func NewAutoRebalanceConfigUpsert(accountId string, enabled bool, minUtilization string, maxUtilization string, ) *AutoRebalanceConfigUpsert`

NewAutoRebalanceConfigUpsert instantiates a new AutoRebalanceConfigUpsert object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAutoRebalanceConfigUpsertWithDefaults

`func NewAutoRebalanceConfigUpsertWithDefaults() *AutoRebalanceConfigUpsert`

NewAutoRebalanceConfigUpsertWithDefaults instantiates a new AutoRebalanceConfigUpsert object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *AutoRebalanceConfigUpsert) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AutoRebalanceConfigUpsert) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AutoRebalanceConfigUpsert) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetEnabled

`func (o *AutoRebalanceConfigUpsert) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AutoRebalanceConfigUpsert) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AutoRebalanceConfigUpsert) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetMinUtilization

`func (o *AutoRebalanceConfigUpsert) GetMinUtilization() string`

GetMinUtilization returns the MinUtilization field if non-nil, zero value otherwise.

### GetMinUtilizationOk

`func (o *AutoRebalanceConfigUpsert) GetMinUtilizationOk() (*string, bool)`

GetMinUtilizationOk returns a tuple with the MinUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinUtilization

`func (o *AutoRebalanceConfigUpsert) SetMinUtilization(v string)`

SetMinUtilization sets MinUtilization field to given value.


### GetMaxUtilization

`func (o *AutoRebalanceConfigUpsert) GetMaxUtilization() string`

GetMaxUtilization returns the MaxUtilization field if non-nil, zero value otherwise.

### GetMaxUtilizationOk

`func (o *AutoRebalanceConfigUpsert) GetMaxUtilizationOk() (*string, bool)`

GetMaxUtilizationOk returns a tuple with the MaxUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUtilization

`func (o *AutoRebalanceConfigUpsert) SetMaxUtilization(v string)`

SetMaxUtilization sets MaxUtilization field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


