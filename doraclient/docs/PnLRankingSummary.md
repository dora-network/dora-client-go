# PnLRankingSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllUsersDailyTradingVolume** | **string** | Sum of daily_trading_volume across all users matching ranking filters before pagination. | 
**AllUsersTotalTradingVolume** | **string** | Sum of total_trading_volume across all users matching ranking filters before pagination. | 

## Methods

### NewPnLRankingSummary

`func NewPnLRankingSummary(allUsersDailyTradingVolume string, allUsersTotalTradingVolume string, ) *PnLRankingSummary`

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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


