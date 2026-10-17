# PnLRankingSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllUsersDailyTradingVolume** | **string** | Sum of daily_trading_volume across all users matching ranking filters before pagination. | 
**AllUsersTotalTradingVolume** | **string** | Sum of total_trading_volume across all users matching ranking filters before pagination. | 
**AllUsersAvgDailyTradingVolume** | **string** | all_users_total_trading_volume divided by the number of distinct UTC days on which any matching user had an executed fill. 0 if there are none. | 
**AllUsersAvgDailyTradingVolumeOnNDays** | **string** | Executed trading volume within [start, end) across all users matching ranking filters, divided by the number of requested days elapsed so far (end clamped to now, partial days rounded up). 0 if start is in the future. | 

## Methods

### NewPnLRankingSummary

`func NewPnLRankingSummary(allUsersDailyTradingVolume string, allUsersTotalTradingVolume string, allUsersAvgDailyTradingVolume string, allUsersAvgDailyTradingVolumeOnNDays string, ) *PnLRankingSummary`

NewPnLRankingSummary instantiates a new PnLRankingSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPnLRankingSummaryWithDefaults

`func NewPnLRankingSummaryWithDefaults() *PnLRankingSummary`

NewPnLRankingSummaryWithDefaults instantiates a new PnLRankingSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllUsersDailyTradingVolume

`func (o *PnLRankingSummary) GetAllUsersDailyTradingVolume() string`

GetAllUsersDailyTradingVolume returns the AllUsersDailyTradingVolume field if non-nil, zero value otherwise.

### GetAllUsersDailyTradingVolumeOk

`func (o *PnLRankingSummary) GetAllUsersDailyTradingVolumeOk() (*string, bool)`

GetAllUsersDailyTradingVolumeOk returns a tuple with the AllUsersDailyTradingVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllUsersDailyTradingVolume

`func (o *PnLRankingSummary) SetAllUsersDailyTradingVolume(v string)`

SetAllUsersDailyTradingVolume sets AllUsersDailyTradingVolume field to given value.


### GetAllUsersTotalTradingVolume

`func (o *PnLRankingSummary) GetAllUsersTotalTradingVolume() string`

GetAllUsersTotalTradingVolume returns the AllUsersTotalTradingVolume field if non-nil, zero value otherwise.

### GetAllUsersTotalTradingVolumeOk

`func (o *PnLRankingSummary) GetAllUsersTotalTradingVolumeOk() (*string, bool)`

GetAllUsersTotalTradingVolumeOk returns a tuple with the AllUsersTotalTradingVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllUsersTotalTradingVolume

`func (o *PnLRankingSummary) SetAllUsersTotalTradingVolume(v string)`

SetAllUsersTotalTradingVolume sets AllUsersTotalTradingVolume field to given value.


### GetAllUsersAvgDailyTradingVolume

`func (o *PnLRankingSummary) GetAllUsersAvgDailyTradingVolume() string`

GetAllUsersAvgDailyTradingVolume returns the AllUsersAvgDailyTradingVolume field if non-nil, zero value otherwise.

### GetAllUsersAvgDailyTradingVolumeOk

`func (o *PnLRankingSummary) GetAllUsersAvgDailyTradingVolumeOk() (*string, bool)`

GetAllUsersAvgDailyTradingVolumeOk returns a tuple with the AllUsersAvgDailyTradingVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllUsersAvgDailyTradingVolume

`func (o *PnLRankingSummary) SetAllUsersAvgDailyTradingVolume(v string)`

SetAllUsersAvgDailyTradingVolume sets AllUsersAvgDailyTradingVolume field to given value.


### GetAllUsersAvgDailyTradingVolumeOnNDays

`func (o *PnLRankingSummary) GetAllUsersAvgDailyTradingVolumeOnNDays() string`

GetAllUsersAvgDailyTradingVolumeOnNDays returns the AllUsersAvgDailyTradingVolumeOnNDays field if non-nil, zero value otherwise.

### GetAllUsersAvgDailyTradingVolumeOnNDaysOk

`func (o *PnLRankingSummary) GetAllUsersAvgDailyTradingVolumeOnNDaysOk() (*string, bool)`

GetAllUsersAvgDailyTradingVolumeOnNDaysOk returns a tuple with the AllUsersAvgDailyTradingVolumeOnNDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllUsersAvgDailyTradingVolumeOnNDays

`func (o *PnLRankingSummary) SetAllUsersAvgDailyTradingVolumeOnNDays(v string)`

SetAllUsersAvgDailyTradingVolumeOnNDays sets AllUsersAvgDailyTradingVolumeOnNDays field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


